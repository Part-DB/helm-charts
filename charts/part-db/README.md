# Part-DB

## TL;DR;

```console
$ helm install part-db
```

## Introduction

This chart bootstraps an part-db service deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites
  - Kubernetes 1.4+ with Beta APIs enabled

## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release part-db
```

The command deploys ednme on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The following table lists the configurable parameters of the part-db chart and their default values.

Parameter | Description | Default
--- | --- | ---

```console
$ helm install part-db --name my-release \
    --set controller.stats.enabled=true
```

Alternatively, a YAML file that specifies the values for the parameters can be provided while installing the chart. For example,

```console
$ helm install part-db --name my-release -f values.yaml
```

> **Tip**: You can use the default [values.yaml](values.yaml)
