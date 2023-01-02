---
title: "Parallel Approval Processes"
subtitle: "How to create a multi-person approval process"
date: 2023-01-02T14:09:00-05:00
draft: false
author: Alex Herron & Dan Funk
thumbnail: /images/articles/parallel_approval_thumbnail.png
---

Felix on the [SpiffWorkflow Discord Channel](https://discord.gg/F6Kb7HNK7B) asked:

> hey all, I am designing an approval process using spiff-workflow, a multi instances user task has 3 assignees, the task should complete if more than 2 users approve. Is SpiffWorkflow able to do this?

Alex (our modeling and business analysis expert) built the following diagram to think through how best to describe a set of parallel tasks that can interrupt each other in a way that would support Felix's questions.  

Details are below, but here a video as well, that might be a little easier to follow.
{{< video "/videos/parallel_approval.mp4" "my-5" >}}

Here is how the diagram looks in SpiffArena in our Process Instance Viewer.  It is worth studying. Even though the diagram for each lane is identical, they each executed very differently.
![Image of a completed process](./completed_process.png)

1. The top lane is the "instigating user" the person that started the process.  Their first two tasks are grayed out as completed.  It's the lanes below that are important ...
2. In the Approver 1 lane, the Approval happens (through a manual task) then we check a data store (Data Stores are single global variables across the whole running processes) to see how many approvals were completed.  In this case only one approval has happened, so that path of the parallel process is complete.   
3. In the Approver 2 lane, we do the same, only this time when the approval is complete and we increment the total approvals, it is enough to cause our event to fire.
4. When the event fires, it cancels the final waiting approval, it doesn't need to complete. So it skips the final steps.
5. At this point all three parallel paths are complete and the diagram closes out. 

Here is the original BPMN file if you would like to try it out yourself.  
[Download Diagram](./multi-approvals-1.bpmn "download")
