# Webhooks, apis, vsts, and github
Slides and Readme for Decoded Conference 2016 Session

This repository contains slides and links to the code repositories demonstrated

## Session Slides

Here is the main PPTX: [slides](./slides/cicoria-vsts-integration-devops.pptx)


## Vsohelper
This is the simple nodejs app that provides the relay to/from VSTS and GitHub.

https://github.com/pct-tr22/vsohelper
and here: https://github.com/cicorias/vsohelper


## VsoExtension
This is the custom VSTS extension that provides the custom Tasks for build start notification and build complete notification.

Note that it uses vsohelper as the relay.

https://github.com/cicorias/vsoext

## VSTS Debug Extension in NodeJS
This is the Market place extension source that emits the environment variables to help in debugging

https://github.com/cicorias/vstsdebug

you can install from here direct: https://marketplace.visualstudio.com/items?itemName=cicorias.vsts-debug


## Example VSTS Tasks

- [X] Simple make
- [X] Sleep - used for demo

https://github.com/cicorias/tfx-tasks

## VsoHelper as Azure Functions
Here is the Work in progress of moving vsohelper to Azure Functions - for a serverless experience... 

https://github.com/cicorias/vso-function


