---
title: Working with Workflows
seo-title: Working with Workflows
description: Workflows in AEM allow you to automate a series of steps that are performed on a page or asset.
seo-description: Workflows in AEM allow you to automate a series of steps that are performed on a page or asset.
contentOwner: Guillaume Carlino
products: SG_EXPERIENCEMANAGER/6.5/SITES
content-type: reference
topic-tags: site-features
---

# Working with Workflows {#working-with-workflows}

AEM Workflows allows you to automate a series of steps that are performed on (one or more) pages and/or assets.

For example, when publishing, an editor has to review the content - before a site administrator activates the page. A workflow that automates this example notifies each participant when it is time to perform their required work:

1. The author applies the workflow to the page.
1. The editor receives a work item that indicates that they are required to review the page content. When finished, they indicate that their work item is complete.
1. The site administrator then receives a work item that requests the activation of the page. When finished, they indicate that their work item is complete.

Typically:

* Content authors apply workflows to pages as well as participate in workflows.
* The workflows that you use are specific to the business processes of your organization.

The following pages cover:

* [Applying Workflows to Pages](/help/sites-cloud/authoring/workflows/applying.md)
* [Participating in Workflows](/help/sites-cloud/authoring/workflows/participating.md)
