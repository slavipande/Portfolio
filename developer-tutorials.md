---
title: Developer Tutorials
layout: page
icon: fa-check
hide: true
---

<ul class="breadcrumb">
  <li><a href="./#" class="icon fa-home">  Home</a></li>
  <li><a href="./#portfolio" class="icon fa-briefcase">  Portfolio</a></li>
  <li>Developer Tutorials</li>
</ul>


{% include image.html max-width="100%" height="auto" background-size="cover" file="assets/images/undraw_Programming_re_kg9v.png" alt="Dev Tutorials Illustration" %}


### Context
These tutorials guide developers through the steps of development, deployment in the cloud, and extension of a sample app in accordance with the [SAP Business Technology Platform (BTP) Developers' Guide](https://help.sap.com/docs/btp/btp-developers-guide/tutorials-for-sap-cloud-application-programming-model?version=Cloud) and following the [SAP Cloud Application Programming Model (CAP)](https://cap.cloud.sap/docs/about/). The tutorials are divided into groups and published to the [SAP Tutorial Navigator](https://developers.sap.com/tutorial-navigator.html).

### Links
- [Develop a Full-Stack CAP Application Following SAP BTP Developer’s Guide](https://developers.sap.com/group.cap-application-full-stack.html) 
  > Tutorials focus on developing a CAP app from scratch using [SAP Business Application Studio](https://help.sap.com/docs/bas), including creating the data model and services, adding SAP Fiori elements UIs and some custom logic, adding authorization, test cases, and a local launch page for the app, and preparing the app for productive deployment.
- [Deploy a Full-Stack CAP Application in SAP BTP, Cloud Foundry Runtime Following SAP BTP Developer’s Guide](https://developers.sap.com/group.deploy-full-stack-cap-application.html)      
  > Tutorials focus on admin tasks such as adding entitlements and creating service intances in SAP BTP, setting up the app for deployment to the SAP BTP, Cloud Foundry runtime, adding user roles post deployment, setting up authorization workflows, and setting up a CI/CD pipeline so the app is redeployed whenever it's updated.
- [Deploy a Full-Stack CAP Application in SAP BTP, Kyma Runtime Following SAP BTP Developer’s Guide](https://developers.sap.com/group.deploy-full-stack-cap-kyma-runtime.html)
  > Tutorials focus on admin tasks such as adding entitlements and creating service intances in SAP BTP, using VS Code locally to set up the app for deployment to the SAP BTP, Kyma runtime, adding user roles post deployment, setting up authorization workflows, and setting up a CI/CD pipeline so the app is redeployed whenever it's updated.
  - [Consume Remote Services from a Mock Server in Your Full-Stack CAP Application Following the SAP BTP Developer's Guide and Deploy in SAP BTP, Cloud Foundry Runtime](https://developers.sap.com/group.sap-mock-consume-remote-services.html)
  > Tutorials focus on extending and integrating the CAP app with an external service definition from SAP Business Accelerator Hub, testing the app locally with mocked data, deploying a mock server, creating a destination so that the app connects to the mock server, and testing if the app fetches data from the mock server.
  - [Consume Remote Services from S/4HANA Cloud in Your Full-Stack CAP Application Following the SAP BTP Developer's Guide and Deploy in SAP BTP, Cloud Foundry Runtime](https://developers.sap.com/group.sap-s4hana-consume-remote-services.html)
  > Tutorials focus on extending and integrating the CAP app with an external service definition from SAP Business Accelerator Hub, testing the app locally with mocked data, adding an SAP S/4HANA Cloud system to SAP BTP, configuring the app, and testing if the app fetches data from the SAP S/4HANA Cloud system.


<!-- 
- [Create an SAP Fiori Elements-Based Analytical UI for your CAP Application](https://developers.sap.com/tutorials/btp-app-analytics-setup-use.html)
-->

### My role

More often than not, great documentation comes as a result of the collaboration of several people with different profiles. I worked on these tutorials as part of a small team consisting of myself, several developers, and an information architect. Here's how I contributed:

- Pick up raw tutorial drafts from the developers.
- Review and edit the tutorial from a language perspective.
- Install and configure any required tools to prepare my development environment for testing. 
- Test the tutorial step by step.
- Check code samples for correctness and compare with my testing project.
- Add prerequisites, steps, notes, tips, screenshots, and more context as needed.
- Note down any errors from the testing.
- Search through internal and external community discussions to find solutions for the errors and adjust the tutorial.
- Discuss tutorial scenario, structure, and any unsolved errors with the team.
- Make changes as needed and test again.
- Get a peer review. 
- Publish.


### Tools

- VS Code
- MkDocs with Material for MkDocs
- VitePress
- Snagit
- Git and GitHub
- Bash
