---
title: "The Low Code Wall"
subtitle: "Citizen Developers play a critical role in modern software development, but some low-code solutions trap their potential, rather than releasing it. We’ll talk about how to spot low-code solutions that don’t have walls."
date: 2023-01-05T15:06:00-05:00
draft: false
author: Dan Funk
images:
  - /images/articles/lowcode2_thumbnail.png
description: A business-level introduction to SpiffWorkflow and why we adopted this open-source platform and are building a suite of tools around it.
---

![Woman behind bars](low-code-jail.png)

## What is Low-Code / No-Code?

Low Code and No Code describe tools that allow people to create software applications (websites, mobile apps, games, etc...) using graphical tools that don’t require writing code in traditional programming languages.
There are some brilliant examples - and they aren’t new - the idea has been around forever.
We’ve always been trying to make it easier to talk to computers.
Check out MIT’s Scratch, which helps introduce software concepts to young students, or consider what anyone can do these days with WordPress.
In fact, pick up any popular cross-discipline software from 3D modeling (Blender) to clinical research (the delightful R language), and you will find this idea blossoming in every corner.

## Who is this Citizen Developer?

Citizen Developers are people who are authoring software, but whose primary role within a group or organization is not software engineering.
An excellent example might be a postgraduate student in Psychology, building an online study of anxiety, or a small business owner who creates a mobile application to help draw people to her bakery.
Citizen Developers is a term that will, over time, become ubiquitous.
People from all walks of life are creating software these days and nearly everyone is getting some exposure to software as they travel through life.

## What is the Low-Code Wall

The Low-Code Wall is the point at which a well-intentioned tool becomes a hindrance rather than an aid.
It is the moment when a Citizen Developer's aspirations, vision, and abilities exceed the capabilities of the tool.
Some Low-Code tools are carefully designed to offer a clean exit, a way to move beyond their baked-in limitations and assumptions.
In many cases, however, these tools don’t offer a way out.
Maybe it's a malicious vendor lock-in, but mostly it’s just because offering a way out is damn hard.
Like Alice in Wonderland, Citizen Developers drink the “Low Code” potion, and it solves some of their problems – they can get in that rabbit hole, it costs a lot less to fill a tea cup.
But what do they do when they can’t get back to normal without demolishing everything around them?

## Avoiding the Low-Code Wall

Here are a few ways to tell if a “Low-Code” system is building you a golden walkway right into a pile of busted bricks:

1. Look out for terms like **“Build your app in minutes.”** A quick start is like a too-good-looking and too-interested first date – the faster you move in the beginning, the more quickly you may find the assumptions being made aren’t ones you are comfortable with long term.
2. Require direct and clear assertions of a low-code system's ability to address **security vulnerabilities**. One of the things that makes software development hard is making sure it can’t get abused – you don’t want hackers taking over your website, or app explosions (the infamous Shadow-IT) creating security vulnerabilities in your organization.
3. **No-Code At All!** That’s not a real benefit. Sometimes the easiest and simplest way to get something done is to write a little code. Basic scripting is a skill anyone can learn, and it comes with staggering power. If you can’t move the low-code/no-code tool out of the way and add your own code directly, it **is a wall by definition**.
4. **Open Standards**. Avoid proprietary languages owned and controlled by a single organization. Look for low-code tools that are built on top of existing standards that have broad support. A good low-code tool is a stepping stone to doing more things and growing. The absence of open standards is like the absence of doors and windows - you are walking into a prison cell.
5. **SAAS Only** - SAAS or Software As a Service is a wonderful business model - but if you go with a vendor that only offers their services through their website then you didn’t buy a product - the product bought you. You can’t control security, you will be forced into each upgrade cycle on their schedule, you will walk to the beat of their drum, and there is no way to prevent the vendor from throwing away all your efforts and leaving you behind.
6. **Trust the lessons of the industry** - There are tools no software developer can do without. Whether it is low-code or high-code, you need some basic things. A testing framework - a way to test your work and assert it meets specific expectations. A versioning system that allows you to track changes, go back three hours to when things were still working, and collaborate with others. And a debugging environment, so when you ask “Why is the damn thing not working?”, you have some way to dig in and find out. You also want a place to ask questions that aren't restricted to paying clients - like Stack Overflow, an open chat room, or a public message board of some type. Finally, you need a Staging Environment - a place where you can make mistakes and test out ideas before you show your work to the world.

## An alternative to Low-Code for Citizen Developers

### (or “And now a word from our sponsors”)

I’m going to switch gears here and tell you about the open-source project we created that seeks to support Citizen Developers in a way that avoids the pitfalls outlined above.

As an alternative to the largely proprietary low-code systems that exist today, perhaps we could look at ways to better include Citizen Developers in the standard software development process through tools focused on collaboration between the Citizen Developers and an IT Department.
In doing so we can naturally build on the lessons of the industry and avoid some of the common pitfalls outlined above.
And if done right, it creates wide open roads for Citizen Developers to continue to grow, innovate, and expand their contributions.

It is with this vision in mind that we developed SpiffArena - a new open-source tool based on the popular SpiffWorkflow Library.
SpiffArena is a complete web-based application that encourages collaboration between the IT Team and Citizen Developers.
It is a low-code environment that uses visual tools (in this case Flow-Chart like diagrams) and familiar interfaces (like spreadsheets) to create applications.
Citizen Developers can use these tools directly and independently to gather information from end users, make decisions, pass information along to other systems within the organization (anything from Slack Messages to databases to custom API calls).
In the meantime, the core system can be controlled by the IT Department, which can handle critical security concerns and build integration points.

Those Flow-Chart diagrams are a well-established standard called BPMN, and the spreadsheets follow another standard called DMN.
So building skills here are useful beyond the application, and resources abound for learning how to use these tools effectively.
The rest of the system is managed through the delightfully intuitive and powerful Python programming language, which is relatively easy to learn and also exceedingly well documented (it’s one of the most popular programming languages in the world for doing just about anything).

If you would like to learn more, please check out our website at https://www.spiffworkflow.org.
There are tutorials that will help you get started, and a detailed overview of major features and core components.
