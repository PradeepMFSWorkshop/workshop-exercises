# CD with CloudBees Core Workshop

This repository contains the instructions and learning materials associated with a hands-on workshop **CD with CloudBees Core Workshop** that is designed to teach the following key concepts:

  * How specific features of CloudBees Core on Kuberenetes will acclerate your CD?
  * Why you should *mostly* use [Declarative](https://jenkins.io/doc/book/pipeline/syntax/#declarative-pipeline) vs [Scripted](https://jenkins.io/doc/book/pipeline/syntax/#scripted-pipeline) pipelines?
  * How to create a reusable template for Jenkins Declarative Pipelines?
  * What are the key features of Declarative Pipelines?


To get started goto the [**Set-up Instructions**](Setup.md).

**The exercises covered in the workshop are available at the following links:**

  * [**Introduction to Pipelines with CloudBees Core**](exercises/intro-pipeline-cb-core.md)
  * [**Pipeline Approvals and Artifact Management with CloudBees Core**](exercises/approvals-artifacts-cb-core.md)
  * [**Parallel and Sequential Stages with CloudBees Core**](exercises/parallel-sequential-cb-core.md)
  * [**Advanced Pipelines with CloudBees Core**](exercises/advanced-pipeline-cb-core.md)

# Training Prerequisites

In order to follow along with the hands on portion of the workshop students should have the following resources available to them:

  * A basic understanding of Jenkins Pipelines: https://jenkins.io/doc/book/pipeline/getting-started/ 
  * Internet access to include access to https://github.com
  * An account on Github.com and a basic understanding of how to use Github to do things like fork a repository, edit files in the web UI, and create pull requests
  * A personal access token for your Github account ([Github-Personal-Access-Token.md](Github-Personal-Access-Token.md)) with the following permissions:
    - repo: all
    - admin:repo_hook: all
    - admin:org_hook
    - user: all
  * Access to a Jenkins server
  
Detailed set-up instructions are available at **[Setup](Setup.md)**

# Disclaimer

Although the code in this repository was originally created by employees of CloudBees, Inc. to use in training customers, your use of this material is not sponsored or supported by CloudBees, Inc.

# Contributors 

* Contributor: [Kurt Madel](https://github.com/kmadel), [Josh Hendrick](https://github.com/jhendrick)
 
# Questions, Feedback, Pull Requests Etc.

If you have any questions, feedback, suggestions, etc. please submit them via issues or, even better, submit a Pull Request!
