---
title: "Why we adopted SpiffWorkflow"
subtitle: "The future of business software is drawn in the code"
date: 2021-12-01T13:15:00-05:00
draft: false
author: Dan Funk
thumbnail: images/articles/lowcode_thumbnail.png
---

![Silly picture of my dog](/images/articles/lowcode.png)

(originally posted on [Medium](https://medium.com/@danfunk/a-visual-workflow-library-for-python-d19e1387653))

SpiffWorkflow allows your python application to process BPMN diagrams (think of them as very powerful flow charts) to accomplish what would otherwise require writing a lot of complex business logic in your code. You can use these diagrams to accomplish a number of tasks, such as:

* Creating an online questionnaire which changes depending on the answers to previous questions;
* Building a complex approval process that needs to be handed off between multiple people;
* Allowing non-developers to make iterative changes to the flow of an application over time;
SpiffWorkflow can do all of this while drastically improving communication within multidisciplinary teams, allowing more people to contribute to your application, and making it more resilient to changing requirements.

## Visualizing Code is the Future

Visual software development environments are key for handling many of the business problems we need to solve over the coming decade. While there are tons of marketing sites touting “low-code” solutions of nominal value, there are a handful of elegant real-world success stories. I’ve seen them most clearly through the eyes of my son. His introduction to programming was [Scratch](https://scratch.mit.edu/) where basic programming constructs work like building blocks you can stack together. It feels a little like playing with legos, you can build chunks, then stick them together in different ways to see what happens. From there my son moved on to [Blender](https://www.blender.org/), which uses visual tools for the complex process of building 3D animations, taking a dual disciple problem, and providing intuitive visual representation of what is definitely programming. Low-Code using visualization tools is very much a real thing, and it will reshape the way we work with computers in the future to solve complex problems.

## What are Workflows and BPMN

The term “Workflow” can mean many things in software. Our focus is on Business Processes — such as the complex approval process necessary for launching a medical research study at a university (our core use case at the moment). There is a well established standard for visualizing business processes called BPMN (Business Process Modeling Notation) that looks a heck of a lot like a flow chart (see image below). Version 2.0 published in 2010 was designed to be executable. This is important.

{{< figure src="/images/articles/lowcode_diagram.png" caption="Not to delve too deeply, but the arrows in the diagram above dictate motion from one task to the next. The boxes with people are User Tasks, and are often powered by user interfaces that allow real people to provide input. The X’s are crossroads where different paths can be taken. The script tasks (with the piece of curvy paper) are where we can inject brief bits of code to make calculations and call out to other software systems and APIs. This is a very small example of all that is possible within the enormous 538 page BPMN standard, but it is a valid example, and demonstrates that powerful diagramming tools can still be intuitive." >}}

What’s great about BPMN is that you can potentially create software even a CEO can understand. Imagine having a board meeting where everyone around the table actually knew what they were talking about. This is the glorious promise of BPMN. A diagram that doesn’t roughly abstract the general meaning of what we think the software does. It’s a diagram that IS the software.

## What is SpiffWorkflow

BPMN diagrams don’t just run. You need an interpreter that is capable of executing the diagram, in the same way that you need to have the python interpreter to run a python program. SpiffWorkflow is an interpreter for BPMN, that makes the diagram runnable as a part of your Python application.

SpiffWorkflow is open source, and released under the GNU Lesser General Public License.

Two years ago we were searching for an open source workflow library in Python that could handle BPMN. We found SpiffWorkflow, a project founded by Samuel Abels (@knipknap) in 2010. Over the last two years we’ve made thousands of contributions to the code base as we started using it to manage dozens of complex real-world workflows. Earlier this year we released a new version of SpiffWorkflow with all of our contributions, and released a set of new bug fixes just this past week. It is not perfect, but it is definitely battle hardened, and ready for others to pick up, try out, and potentially contribute to.

