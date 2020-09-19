# k3d

A local k8s cluster using [k3d](https://k3d.io/)

## Prerequisite

Below, software/tools are required to run this.

- [homebrew](https://brew.sh/)
- k3d - `brew install k3d` 
- [Go task](https://taskfile.dev/#/) (trust me it will reduce the keystrokes!) `brew install go-task/tap/go-task`

## Usage

Available tasks `task -l`

```shell
task: Available tasks for this project:
* create: 	Create the k8s cluster
* delete: 	Delete the k8s cluster
* start: 	Starts the k8s cluster
* stop: 	Stops the k8s cluster
```