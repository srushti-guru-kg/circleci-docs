---
layout: server-docs
title: "Tutorials"
description: "Tutorials and 2.0 Sample Apps with Guides"
---

Use the tutorial associated with your platform to learn about the customization that is possible in a [`.circleci/config.yml`]({{ site.baseurl }}/2.0/configuration-reference/).

Platform Guide | Description
----|----------
<a href="{{ site.baseurl }}/2.0/project-walkthrough/">Linux Project Tutorial</a> | Complete walkthrough of setting up a Python project with Flask to build with CircleCI 2.0.
<a href="{{ site.baseurl }}/2.0/ios-tutorial/">iOS Project Tutorial</a> | Full example of setting up an iOS project in CircleCI 2.0.
<a href="{{ site.baseurl }}/2.0/language-android/">Android Project Tutorial</a> | Full example of setting up an Android project in CircleCI 2.0.
[Windows Project Tutorial]({{ site.baseurl }}/2.0/hello-world-windows/) | Full example of setting up a .NET project in CircleCI 2.0.
{: class="table table-striped"}

## Sample Projects with Companion Guides

Refer to the Sample Projects to get help with building the language and framework in which your application is written.

{% include snippets/language-guides.md %}

## Sample Workflows

Workflow Example | GitHub Repo
------|-----------
Parallel | [parallel-jobs](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/parallel-jobs/.circleci/config.yml)
Sequential | [sequential-branch-filter](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/sequential-branch-filter/.circleci/config.yml)
Fan-in / Fan-out | [fan-in-fan-out](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/fan-in-fan-out/.circleci/config.yml)
Workspace Forwarding | [workspace-forwarding](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/workspace-forwarding/.circleci/config.yml)
{: class="table table-striped"}

## CircleCI Public Repos

GitHub Repo | Description | config.yml link
------|-----------|------------
circleci-docs | A static website generated by Jekyll for CircleCI documentation. | [.circleci/config.yml](https://github.com/circleci/circleci-docs/blob/master/.circleci/config.yml)
circleci frontend | Mirror of the code that is running CircleCI's frontend. | [.circleci/config.yml](https://github.com/circleci/frontend/blob/master/.circleci/config.yml)
circleci-images | Contains the official set of images that CircleCI maintains. | [.circleci/config.yml](https://github.com/circleci/circleci-images/blob/master/.circleci/config.yml)
circleci image-builder | Uses Docker for building container images. | [.circleci/config.yml](https://github.com/circleci/image-builder/blob/master/.circleci/config.yml)
{: class="table table-striped"}

## See Also

Use the Hello World document and sample `config.yml` files to start configuring your build.

Document | Description
----|----------
<a href="{{ site.baseurl }}/2.0/hello-world/">Hello World</a> | Simple steps to get started with a `config.yml` file template for an app that prints Hello World.
<a href="{{ site.baseurl }}/2.0/sample-config/">Sample `config.yml` Files</a> | Four sample `config.yml` files using concurrent Workflows, sequential Workflows, fan-in/fan-out Workflows, and building Linux and iOS in one configuration file.
{: class="table table-striped"}