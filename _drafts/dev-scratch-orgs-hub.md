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