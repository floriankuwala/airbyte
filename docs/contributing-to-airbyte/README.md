---
description: 'We love contributions to Airbyte, big or small.'
---

# Contributing to Airbyte

Thank you for your interest in contributing! We love community contributions. Contribution guidelines are listed below. If you're unsure about how to start contributing or have any questions even after reading them, feel free to ask us on [Slack](https://slack.airbyte.io) in the \#dev or \#general channel.

However, for those who want a bit more guidance on the best way to contribute to Airbyte, read on. This document will cover what we're looking for. By addressing the points below, the chances that we can quickly merge or address your contributions will increase.

## Code of conduct

Please follow our [Code of conduct](code-of-conduct.md) in the context of any contributions made to Airbyte.

## Airbyte specification

Before you can start contributing, you need to understand [Airbyte's data protocol specification](../architecture/airbyte-specification.md).

## First-time contributors, welcome!

We appreciate first time contributors and we are happy to assist you in getting started. In case of questions, just reach out to us via [email](mailto:hey@airbyte.io) or [Slack](https://slack.airbyte.io)!

Here is a list of easy [good first issues](https://github.com/airbytehq/airbyte/labels/good%20first%20issue) to do.

## Areas for contributing

### **New connectors**

It's easy to add your own connector to Airbyte! **Since Airbyte connectors are encapsulated within Docker containers, you can use any language you like.** Here are some links on how to add sources and destinations. We haven't built the documentation for all languages yet, so don't hesitate to reach out to us if you'd like help developing connectors in other languages.

* See [Building new connectors](building-new-connector/) to get started.
* Since we frequently build connectors in Python, on top of Singer or in Java, we've created generator libraries to get you started quickly: [Build Python Source Connectors](../tutorials/building-a-python-source.md) and [Build Java Connectors](building-new-connector/java-connectors.md)
* Integration tests \(tests that run a connector's image against an external resource\) can be run one of three ways, as detailed [here](building-new-connector/testing-connectors.md)

**Please note that, at no point in time, we will ask you to maintain your connector.** The goal is that the Airbyte team and the community helps maintain the connector.

### **Documentation**

Our goal is to keep our docs comprehensive and updated. If you would like to help us in doing so, we are grateful for any kind of contribution:

* Report missing content
* Fix errors in existing docs
* Help us in adding to the docs

The contributing guide for docs can be found [here](updating-documentation.md).

### **Community content**

We welcome contributions as new tutorials / showcases / articles, or to any of the existing guides on our [tutorials page](https://airbyte.io/tutorials):

* Fix errors in existing tutorials
* Add new tutorials \(please reach out to us if you have ideas to avoid duplicate work\)
* Request tutorials

We have a repo dedicated to community content. Everything is documented [there](https://github.com/airbytehq/community-content/).

Feel free to submit a pull request in this repo, if you have something to add even if it's not related to anything mentioned above.

## Ways you can contribute

### **Adding to the codebase for a connector or issue**

First, a big thank you! A few things to keep in mind when contributing code:

* Please make sure there is an issue associated with the work that you're doing.
* If you're working on an issue, please comment that you are doing so to prevent duplicate work by others also.
* Rebase master with your branch before submitting a pull request.

Here are some details about [our review process](./#review-process).

### **Upvoting issues, feature and connector requests**

You are welcome to add your own reactions to the existing issues. We will take them in consideration in our prioritization efforts, especially for connectors.

❤️ means that this task is CRITICAL to you.  
👍 means it is important to you.

### **Requesting new features**

To request new features, please create an issue on this project.

If you would like to suggest a new feature, we ask that you please use our issue template. It contains a few essential questions that help us understand the problem you are looking to solve and how you think your recommendation will address it. We also tag incoming issues from this template with the "**community\_new**" label. This lets our teams quickly see what has been raised and better address the community recommendations.

To see what has already been proposed by the community, you can look [here](https://github.com/airbytehq/airbyte/labels/community_new).

Watch out for duplicates! If you are creating a new issue, please check [existing open](https://github.com/airbytehq/airbyte/issues), or [recently closed](https://github.com/airbytehq/airbyte/issues?utf8=%E2%9C%93&q=is%3Aissue%20is%3Aclosed%20). Having a single voted for issue is far easier for us to prioritize

### **Requesting new connectors**

This is very similar to requesting new features. The template will change a bit and all connector requests will be tagged with the “**community\_new**” and “**area/integration**” labels.

To see what has already been proposed by the community, you can look [here](https://github.com/airbytehq/airbyte/labels/area%2Fintegration). Again, watch out for duplicates!

### **Reporting bugs**

**‌**Bug reports help us make Airbyte better for everyone. We provide a preconfigured template for bugs to make it very clear what information we need.

‌Please search within our [already reported bugs](https://github.com/airbytehq/airbyte/issues?q=is%3Aissue+is%3Aopen+label%3Atype%2Fbug) before raising a new one to make sure you're not raising a duplicate.

### **Reporting security issues**

Please do not create a public GitHub issue. If you've found a security issue, please email us directly at [security@airbyte.io](mailto:security@airbyte.io) instead of raising an issue.

## **Review process**

**‌‌**If you are considering adding to the codebase or contributing a new connector: a big thank you! We sincerely appreciate your help.

As soon as you are done with your development, just put up a PR. You're also always welcome to reach out during or before development. When we review we look at:

* ‌Does the PR solve the issue?
* Is the proposed solution reasonable?
* Is it tested? \(unit tests or integration tests\)
* Is it introducing security risks?

‌Once your PR passes, we will merge it.

