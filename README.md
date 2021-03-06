

# Pipelines

We use [pipelines](https://github.com/tektoncd/pipeline/tree/master/docs#usage) to illustrate a continuous input and continuous delivery (CI/CD) workflow. This repository provides a set of default tasks and pipelines that can be associated with application stacks. These pipelines validate the application stack is active, build the application stack, publish the image to a container registry, scan the published image, and then deploy the application to a cluster. You can also create your own tasks and pipelines and customize the pre-built pipelines and tasks. All tasks and pipelines are activated by a standard Kubernetes operator.

To learn more about the tasks and pipelines and how to run the pipelines, please visit the [working with pipelines guide](https://kabanero.io/guides/working-with-pipelines/).
