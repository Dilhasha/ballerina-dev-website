---
layout: release-note
title: Release note
---
### Overview of jBallerina {{ site.data.stable-latest.metadata.version }}

The jBallerina {{ site.data.stable-latest.metadata.version }} patch release improves upon the {{ site.data.stable-latest.metadata.version }} release by introducing the features listed below and addressing a number of [bugs](https://github.com/ballerina-platform/ballerina-lang/issues?q=is%3Aissue+milestone%3A%22Ballerina+{{ site.data.stable-latest.metadata.version }}%22+label%3AType%2FBug+is%3Aclosed) and [improvements](https://github.com/ballerina-platform/ballerina-lang/issues?q=is%3Aissue+milestone%3A%22Ballerina+{{ site.data.stable-latest.metadata.version }}%22+is%3Aclosed+label%3AType%2FImprovement).

You can use the [update tool](/learn/keeping-ballerina-up-to-date/) to update to jBallerina {{ site.data.stable-latest.metadata.version }} as follows.

**For existing users:**

If you are already using jBallerina version 1.2.0, or above, you can directly update your distribution to jBallerina {{ site.data.stable-latest.metadata.version }} by executing the following command:

> $ ballerina dist update

However, you need to use the following commands instead of the above if you have installed:

- jBallerina 1.2.0 but switched to a previous version: `$ ballerina dist pull jballerina-{{ site.data.stable-latest.metadata.version }}`
- a jBallerina version below 1.1.0: install via the [installers](/downloads/)

**For new users:**

If you have not installed jBallerina, then download the [installers](/downloads/) to install.

#### Code to Cloud

##### Azure Functions

The fix for [Pure HTTP Functions Not Working](https://github.com/ballerina-platform/module-ballerinax-azure.functions/issues/33). For more information, see [Azure Functions](/learn/deployment/azure-functions/).

##### AWS Lambda

Added the support for domain-specific event types. For more information, see [AWS Lambda](/learn/deployment/aws-lambda/).