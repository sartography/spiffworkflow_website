---
title: "How We Compare to the Competition"
subtitle: "See how we measure up, feature by feature, to other leading business workflow engines."
date: 2023-09-27T12:20:00-05:00
draft: false
description: SpiffWorkflow is a feature rich implementation of the BPMN standard, with years of development and testing behind it.  See how we compare to other workflow engines.
cssClass: "section-compare"
---

## How do you compare to Camunda?
Camunda is a leading open source workflow engine, and is based on the same core platform as offerings from IBM, Flowable, Appian and others.  Many of the comparisons here are also applicable to these other systems.

{{< tiles class="compare">}}
{{< tile title="Camunda" icon="java" >}}
**Java Developer Friendly** 
<p>Camunda focuses on supporting professional software engineers, allowing them to use their development environments of choice to write the code behind a BPMN Diagram.  It provides introspection and analytics tools for decision makers within a company.
{{< /tile >}}

{{< tile title="SpiffWorkflow" icon="citizen" class="highlighted">}}
**Citizen Developer Friendly**
<p>We focus on putting automation tools in the hands of decision makers throughout the company.  We use BPMN as a tool for collaboration in an interdisciplinary effort of streamlining your internal processes, engaging everyone in making things work better.
{{< /tile >}}
{{< /tiles >}}

### Feature Comparion Details
See how we compare to Camunda on a number of key elements of a workflow engine ...
* [End To End Process Orchestration](#end-to-end-process-orchestration)
* [Open Standards](#open-standards)
* [Analytics and Optimization](#analytics-and-optimization)
* [Flexible Architecture](#flexible-architecture)
* [Low Cost of Ownership](#low-cost-of-ownership)
* [BPMN Support Details](#bpmn-support)


### End To End Process Orchestration
Both Camunda and SpiffWorkflow provide full end to end process orchestration - we don't solve a small specific problem.  We help you improve your overall process.
{{< compare_table >}}
{{< compare_row title="Human Tasks" sw="true" cm="true">}}
Ability to create web forms that can be completed by end users.  SpiffWorkflow uses an open standard (Json Schema) Camunda uses a proprietary Form Builder.
{{</compare_row>}}
{{< compare_row title="Automated Tasks" sw="true" cm="true">}}
Script, Service, Decision Tables - the ability to define end execute tasks automatically.
{{</compare_row>}}
{{< compare_row title="APIs & MicroServices" sw="true" cm="true">}}
Create and expose new APIs and Micro Services from BPMN Diagrams
{{</compare_row>}}
{{< compare_row title="External Applications" sw="true" cm="true">}}
Connect with external applications through a standard protocol. Spiffworkflow users REST based APIs and Json Schemas, Camunda8 users gRPC
{{</compare_row>}}
{{</compare_table>}}

### Open Standards
Both systems are founded on open standards that have seen substantial research, are backed by well respected international organizations, and are widely across the industry.
{{< compare_table >}}
{{< compare_row title="BPMN 2.0" sw="true" cm="true">}}
BPMN is a flow chart like notation that models the tasks and events within a complete business process.  BPMN 2.0 is maintained by the [OMG](https://www.omg.org/) an international standards body.
{{</compare_row>}}
{{< compare_row title="DMN" sw="true" cm="true">}}
A spreadsheet like notation that describes repeatable business decisions concisely and comprehensively.  DMN is also maintained by the [OMG](https://www.omg.org/).
{{</compare_row>}}
{{< compare_row title="CMMN" sw="" cm="true">}}
Case Management - for describing processes that intrinsically unpredictable, not repeatable, weekly structured.  CMMN is also maintained by the [OMG](https://www.omg.org/).  
{{</compare_row>}}
{{< compare_row title="JSon Schema" sw="true" cm="">}}
SpiffWorkflow users Json Schemas to describe web forms, data stores and other internally modeled systems according to a well established standard.
{{</compare_row>}}
{{</compare_table>}}

### Analytics and Optimization
The ability to track workflow processes as they execute, and to use that information to improve the process over time. 
{{< compare_table >}}
{{< compare_row title="Deep Analytics" sw="true" cm="true">}}
Highly detailed logging of the execution of workflows
{{</compare_row>}}
{{< compare_row title="Data Extraction" sw="true" cm="true">}}
Ability to query and report on details collected within a workflow process
{{</compare_row>}}
{{< compare_row title="Heat Maps" sw="" cm="true">}}
Heatmaps allow you to view all running processes as a single diagram, allow you to quickly pinpoint areas that need improvement.  Heatmaps are a top level item on SpiffWorkflows Roadmap but are not yet available.
{{</compare_row>}}
{{< compare_row title="Issue Resolution" sw="true" cm="true">}}
The ability to suspend, modify, and resume a running process when something going wrong. 
{{</compare_row>}}
{{< compare_row title="Long Running Processes" sw="true" cm="true">}}
Ability to execute workflow processes over days, weeks and months.
{{</compare_row>}}
{{</compare_table>}}

### Flexible Architecture
Both software applications are designed for integration into your organizations infrastructure.  
{{< compare_table >}}
{{< compare_row title="Locally Deployable" sw="true" cm="">}}
While some aspects of Camunda's infrastructure can be deployed in-house, Camunda 8's offering requires that much of the execution happens remotely on their SAAS Platform.
{{</compare_row>}}
{{< compare_row title="Embeddable" sw="true" cm="true">}}
The core SpiffWorkflow library is designed specifically for embedding in any Python based application in any framework.  Some aspects of Camunda are embeddable in Java frameworks, such as Spring.
{{</compare_row>}}
{{</compare_table>}}

### Open Source
Open Source Software is software that is provided along with its source code, with license that permits users to study, change, and improve its design. 
{{< compare_table >}}
{{< compare_row title="Open Source" sw="true" cm="">}}
SpiffWorkflow provides its core source code under an open source license.  While some extensions and plugins are proprietary, the core library, editor extensions, and user interface are released on the LGPL license.
{{</compare_row>}}
{{< compare_row title="Source Available" sw="true" cm="true">}}
"Source Available" licenses permit users to view the source code, but additional restrictions may prevent you from modifying it or using it without permission.  Camunda's core Zeeby engine is released under a restricted license that prohibits use as a 'process automation service', but it does provide the source code for examination.
{{</compare_row>}}
{{< compare_row title="Open Source Contributions" sw="true" cm="true">}}
Both organizations make substantial contributions to the open source community.
{{</compare_row>}}
{{</compare_table>}}

### Low Cost of Ownership
{{< compare_table >}}
{{< compare_row title="Early Assessment" sw="true" cm="true">}}
SpiffWorkflow and Camunda both provide demo sites that allows people to immediately try out the project with freely available videos and documentation.   We encourage you to make a comparison! 
{{</compare_row>}}
{{< compare_row title="Low sloped learning curve" sw="true" cm="">}}
SpiffWorkflow allows a novice user to build and execute a diagram within minutes.  While it can take years to master everything, the basics are easy to learn.  Camunda's structure is more complex, and requires software engineers to create and deploy even a simple diagram.
{{</compare_row>}}
{{< compare_row title="Simple Pricing Model" sw="true" cm="">}}
SpiffWorkflow commercial pricing models are based on features and support contracts, we don't set our prices based on intrusive details about your business, such as the number of processes you execute.   
{{</compare_row>}}
{{</compare_table>}}


## See SpiffWorkflow for yourself 
Schedule a demo with a member of our core team, and we can demonstrate these capabilities live on our demo site.
{{< calendly >}}