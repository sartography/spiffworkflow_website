---
title: "SpiffEditor (and other open source projects)"
subtitle: "Here are few more tools for working with SpiffWorkfow and SpiffArena"
date: 2022-12-27T16:05:00-05:00
draft: false
---

## SpiffEditor
We've built a number of extensions to the excellent open source [BPMN.js](https://bpmn.io/toolkit/bpmn-js/) editor specifically for SpiffWorkflow.  Here are few of the major features:

* **Data Objects, Inputs and Outputs**:  Improved support of adding, referencing and updating Data references, providing a standards based way to manage data within a diagram.
* **Call Activities**: Offers tight integration with SpiffArena so you can quickly navigate to diagrams referenced from within other diagrams. 
* **Custom Properties Panel**: A SpiffWorkflow native properties panel to allow opening up custom editors for Python, Markdown and Json. Ability to add short pre and post scripts to any task, Support for SpiffWorkflows Python Unit Testing framework, among many other tools. 
* **Messages**: We added support for the BPMN Messaging standard, to assure you can easily create Messages and their associated converation elements (correlation properties and keys)

## Connector Proxy, and Connectors
Connector Proxies provide a Discoverable / Plug-In style architecture for adding connections to third party applications that will work seamlessly with SpiffWorkflow, SpiffArena and the SpiffEditor.  We created a [Demo Connector Proxy](https://github.com/sartography/connector-proxy-demo) that you can use to get started. 

Each Connector included in the Connector Proxy is itself a small standalone python application written to the Plug-In standard -- Checkout our [AWS Connector](https://github.com/sartography/connector-aws) for an example.  Adding new plugins should be easy, and we hope to see many contributions here in the future.

## SpiffWorkflow Backend and Frontend
SpiffArena's two major components are a flask API ([SpiffWorkflow Backend](https://github.com/sartography/spiffworkflow-backend)) and a React FrontEnd application ([SpiffWorkflow Frontend](https://github.com/sartography/spiffworkflow-frontend)).  


## License
All of the applications above fall under the 
GNU LESSER GENERAL PUBLIC LICENSE


