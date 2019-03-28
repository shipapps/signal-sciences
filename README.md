# Signal Sciences Agent


<a target="_blank" href="https://replicated.com/watch/create/init?upstream=github.com%2Fshipapps%2Fsignal-sciences"><img height="30" src="https://www.replicated.com/images/ship/oss/dws-green.svg" alt="Deploy"></a><br>

This [Ship](https://github.com/replicatedhq/ship) application provides an easy and repeatable way to deploy the SignalSciences agent using a GitOps workflow. Ship supports creating patches (add, edit and delete) using [Kustomize](https://kustomize.io).

## Quick Start

These instructions will guide you through setting up the SignalSciences Agent to run as a DaemonSet in a Kubernetes Cluster. We encourage a GitOps workflow to deploy, and therefore recommend using Bitnami's excellent [SealedSecret](https://github.com/bitnami-labs/sealed-secrets) controller to manage your SignalSciences credentials through the GitOps process.

### Ship Cloud

The quickest and easiest way to prepare the SignalSciences Agent for deployment to Kubernetes is to use Ship Cloud. Visit [https://www.replicated.com/watch/create/init?upstream=github.com/shipapps/signal-sciences](https://www.replicated.com/watch/create/init?upstream=github.com/shipapps/signal-sciences) and click the green Ship Init button.

### MacOS

If you are on Mac OS, you can install Ship and use the open source application to configure the SignalSciences Agent. You can then commit the generated YAML to any existing deployment tool for deployment. To get started:

```shell
brew install ship
ship init github.com/shipapps/signal-sciences
```
