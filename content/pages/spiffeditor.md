---
title: "SpiffEditor (and other open source projects)"
subtitle: "More tools for working with SpiffWorkfow and SpiffArena"
date: 2022-12-27T16:05:00-05:00
draft: false
description: A brief description of SpiffEditor - extensntions to BPMN.js that customize this popular diagram editor so it can work well with SpiffWorkflow and SpiffArena.
---

The following tools are available as a part of SpiffArena, but can also be used independently.  They are all open source, and we welcome contributions.

## SpiffEditor
We've built a number of extensions to the excellent open source [BPMN.js](https://bpmn.io/toolkit/bpmn-js/) editor, specifically for SpiffWorkflow.  Here are few of the major features:

* **Data Objects, Inputs and Outputs**:  Improved support for adding, referencing and updating data references, providing a standards based way to manage data within a diagram.
* **Call Activities**: Offers tight integration with SpiffArena so you can quickly navigate to diagrams referenced within other diagrams. 
* **Custom Properties Panel**: A new properties panel with multiple features including: custom editors for Python, Markdown and Json; the ability to add short pre- and post- scripts to any task; and a Python Unit Testing editor, among many other enhancements.
* **Messages**: We added support for the BPMN Messaging standard to ensure you can easily create Messages and associated conversation elements (correlation properties and keys).

## Connector Proxy and Connectors
Connector Proxies provide a discoverable, plug-in style architecture for adding connections to third party applications that work seamlessly with SpiffWorkflow, SpiffArena, and the SpiffEditor.  We created a [Demo Connector Proxy](https://github.com/sartography/connector-proxy-demo) that you can use to get started.

Each Connector included in the Connector Proxy is itself a small standalone Python application. Check out our [AWS Connector](https://github.com/sartography/connector-aws) for an example.  Adding new plugins is relatively easy, and we welcome contributions here.

## License
All of the above applications fall under the 
GNU LESSER GENERAL PUBLIC LICENSE.


