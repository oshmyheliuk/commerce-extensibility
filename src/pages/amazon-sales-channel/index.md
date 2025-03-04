---
title: Amazon Sales Channel on App Builder overview
description: Learn how you can use Amazon Sales Channel on App Builder as a reference app to build your own Adobe Commerce apps.
keywords:
  - App Builder
  - Extensibility
---

# Amazon Sales Channel on App Builder overview

Amazon Sales Channel on App Builder is a flagship reference app developed by Adobe Commerce to accelerate merchant and partner adoption of out-of-process extensibility.

This app showcases how Adobe Developer App Builder can create integrations and extensions without modifying the core Commerce application. [Amazon Sales Channel on App Builder](https://github.com/adobe/amazon-sales-channel-app-builder) focuses on demonstrating how to develop key capabilities and extensibility use cases with App Builder. Partners and developers can leverage the application code, best practice guides, and documentation to confidently create their own next-generation extensions and integrations.

The application presents many common use cases for extending Adobe Commerce, including:

* Integration with a 3rd-party system
* Product catalog synchronization
* UI extensibility

Amazon Sales Channel on App Builder is based on an existing PHP extension (Amazon Sales Channel) that was internally developed by Adobe Commerce. This specific integration was chosen because of the breadth of the use cases required, the existing internal familiarity with connecting to Amazon, and the ability to directly compare how capabilities are implemented between the two free, publicly accessible applications.

<InlineAlert variant="warning" slots="text" />

This app is not intended or supported for production use. While the provided capabilities are robust, they are only to be used as a reference to build your own applications. Merchants looking to connect and synchronize their Amazon store with Commerce should use the existing [Amazon Sales Channel PHP extension](https://marketplace.magento.com/magento-module-amazon.html), which can be acquired through Commerce Marketplace, or implement another integration.

To install this app, clone the [aio-amazon-sales-channel](https://github.com/adobe/amazon-sales-channel-app-builder) repo and follow the procedures described in [Prequisites](prerequisites.md) and [Install the Amazon Sales Channel app](installation.md).

## Application functionality

Amazon Sales Channel on App Builder connects Adobe Commerce and Amazon to unify and synchronize your selling platforms. This type of integration allows merchants to manage their product and order data from a single, up-to-date experience. The sample app functionality represents only a subset of the original PHP extension's capabilities. We chose this subset of functionality based on the value provided to partners and developers looking to understand and use our next generation extensibility capabilities.

The central goal of this reference app is to build confidence in the App Builder framework and deliver reusable, Commerce-specific patterns for accelerating implementations.

## Merchant documentation

You can use the [PHP extension user guide](https://experienceleague.adobe.com/docs/commerce-channels/amazon/guide-overview.html) to understand the reference app behaviors. Note that Amazon Sales Channel on App Builder does not feature order management, listing and pricing rules, and several other capabilities of the PHP application.

In general, the sample app looks and feels like the PHP extension. However, some capabilities and behaviors are not exactly the same. Partners and developers should view Amazon Sales Channel on App Builder as a learning tool to enable building high-quality, out-of-process apps with confidence.

## Additional resources

* Join the [#app-builder-community slack channel](https://github.com/AdobeDocs/commerce-extensibility/pull/49/magentocommeng.slack.com) in the Commerce Engineering Slack workspace to ask questions directly to teams and partners working with App Builder.

* Review [Common Troubleshooting](https://developer.adobe.com/app-builder/docs/getting_started/common_troubleshooting/) in the App Builder _Getting Started_ guide for the latest debugging tips.
