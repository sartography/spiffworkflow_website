---
title: "Features"
subtitle: "Here are just a handful of the major features available ..."
date: 2022-12-27T16:05:00-05:00
draft: false
---

### User Tasks -- gather information from people
Using the excellent and feature complete open source schema from React [Json Form Schema](https://react-jsonschema-form.readthedocs.io/en/latest/) - you can create highly complex web forms to gather information from end users - ingesting this information into your workflow process.  

### Service Tasks -- Send and retrieve information from other software 
Service Tasks allow you to configure connections to third party applications.  You can pull live data from an AWS DynamoDB Server, or push a message out to a Slack channel.  Following a basic pattern, you can add new connectors to your own software services by writing a small bit of python code.  Many connectors are in the works (AWS services, Postgres) and new ones are easy to create.

![Services Video](../../images/features/services.gif)

### Lanes -- Who is in charge right now?
Lanes clearly and accurately describe the handoff of authority between groups of people making it crystal clear who is responsible for what tasks, and when.  This is great for approval processes:  "Does Jason deserve that Heavy Metal Cruise Ship vacation in February?" (he definitely does) -- or the hand off of a complex job -- field crew is done, time for Steve to do the computations ...

### Timer Events - Watching the clock
Computers watch clocks.  On the average, one could say that is pretty much all they do. Rather than have the computers constantly remind us of what time it is, perhaps they could just deal with the problem, kick off the process, make the request, check the feedback, send the reminder. 
"The Field Crew completed the survey, it's been on Steve's desk for 2 days ... time to ping Agnes and get this back on track ..."

![Timer Video](../../images/features/timer.gif)

### Messages - Listening to the World
Service tasks are how SpiffWorkflow speaks to the world,  Messages are how SpiffWorkflow listens.  Using Message Events you can start new processes, cancel existing processes, or pause processes and wait for some external communication.  "We told our finance software to fire off an API call to SpiffWorkflow whenever a payment is processed -- then SpiffWorkflow does all the leg work of letting people know when they will get paid in whatever way they like to get notified - email, phone, slack, text, and it creates the paper trail so there is record of what went down ...."

### Perspectives -- Custom Reporting Tools
It doesn't always make sense to do things in the order they were received.  Urgent requests may need to be prioritized and "urgent" can be defined in many ways.  Perspectives allow you to report on running processes in custom ways.  You can extract important information from the workflow as it executes, and make this available in your lists, so you can easily find which tasks you should pick up next.

![Timer Video](../../images/features/perspectives.gif)


### Decision Tables
Decision tables (DMN / Decision Model Notation) look at bit like spreadsheets, and allow you to articulate core business rules in a way that is as easy to understand, update, and maintain, and can be directly embedded and referenced from your diagrams.
![Markdown Video](../../images/features/decisions.gif)


### Granular Permissions and OpenId
SpiffArea can be connected to any OpenID system - using public systems like Google and Facebook or private configurations with products like KeyCloak it is possible to manage user authentication outside SpiffWorkflow.
At the same time, SpiffArena comes with a permission system that can grow with you.  You can use the same diagram tools described above to control permissions for all of your  users - setting up permission tables that can be simple (everyone can start any process) to very specific (this API endpoint is only accessible to the accounting department lead)

### Builtin Editors
With editors for Python, Markdown, and Json - you can quickly jump from drawing the diagram to incorporating the small bits of code, documentation, and end user instructions in a way that is fast, simple and intuitive.

![Markdown Video](../../images/features/markdown.gif)


### Data Encapsulation
SpiffWorkflow supports BPMN's Data Objects, Data Inputs and Data Outputs, allowing you to visually control what data is accessible to which components.  When composing diagrams within diagrams you can declare the expected variables that will be provided, and the ones that will return, keeping your workflows clean, consistent, and easy to understand.

### Python Editor with builtin unit tests
A robust python editor allows you to write small bits of code that help modify data (say user input on a form) to fit a different purpose (sending a formatted message to Slack).  To make these modifications you can use script tasks.  And to make sure they are working correctly we provided a way to test them in place to make sure they do what you expect them to do!
![python editor](../../images/features/scripts.gif)



