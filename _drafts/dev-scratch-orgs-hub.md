---
title: DevOps - Scratch Orgs for Energy & Utilities Cloud
date: 2024-02-09 08:00:00 +5000
categories: [Dev, Scratch Orgs]
tags: [trial, energy-cloud, devops, scratch]   
mermaid: true
img_path: /assets/img/screenshots/devhub/
---

# Scratch Orgs

This is not an introduction to Scratch Orgs. This is the start of an explanation on how to use Scratch Orgs with Energy & Utilities Cloud if you would like to.

There are some foundation steps required to use Scratch Orgs which we will move through quickly to start this guide. After that we will look at how to install the Energy & Utilities Cloud managed package from command line (sf cli).

## Set up a Dev Hub

The Developer Hub is the org you will use to create scratch orgs. It will not contain any of your actual config or packages etc. More info [here](https://developer.salesforce.com/docs/atlas.en-us.pkg1_dev.meta/pkg1_dev/dev_hub_intro.htm).

You can use any org to start. Training Org from Trailhead, Developer org or a Salesforce Trial Org. In this case we will sign up for a [free developer org](https://developer.salesforce.com/signup).

Fill out the form and login to your new Developer Org.

![trial org](dev-org.png){: w="700" h="400" }
_Salesforce Trial Org_

Navigate to 'Setup > Dev Hub' and toggle the 'Enable Dev Hub' switch.

![dev hub toggle](dev-hub-toggle.png{: w="700" h="400" }
_Enabling Dev Hub_

That was easy! 

## Set up Visual Studio Code

Open VS Code. If you have not already install the [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode).

Let's start by creating an empty project. Launch command pallette (CMD + Shift + P) and select SFDX: Create Project. Select 'empty' at the prompt then give your project a name.

## Authorize Dev Heb

Launch command pallette again and select SFDX: Authorize a Dev Hub. Enter an alias for your Dev Hub, a window will open with a Salesforce login screen. Login using your Developer Org credentials and click 'Allow'. 

We know have a Dev Hub linked to a project. The final step is to create a Scratch Org Definition File that will contain the configuration for Scratch Orgs that are created.

## Scratch Org Definition File

There are many options available ([docs](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_scratch_orgs_def_file.htm)) but we will focus on Energy & Utilities Cloud. 

In the config folder of you project make a copy of the project-scratch-def.json file. Name it something Energetic like: euc-scratch-def.json

Note that by keeping *scratch-def.json in the name creating scratch orgs will be possible using the VS Code Extensions.



