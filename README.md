# CSI WekaFS Driver

This repository hosts the CSI WekaFS driver and all of its build and dependent configuration files to deploy the driver.

## Pre-requisite
- Kubernetes cluster
- Running version 1.13 or later
- Access to terminal with `kubectl` installed
- For Kubernetes 1.17 or later, the VolumeSnapshot beta CRDs and Snapshot Controller must be installed as part of the cluster deployment (see Kubernetes 1.17+ deployment instructions)

## Deployment
Deployment varies depending on the Kubernetes version your cluster is running:
- [Deployment for Kubernetes 1.17 and later](docs/deploy.md)

## Building the binaries
If you want to build the driver yourself, you can do so with the following command from the root directory:

```shell
make
```

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](http://kubernetes.io/community/).

You can reach the maintainers of this project at:

- [Slack](http://slack.k8s.io/)
- [Mailing List](https://groups.google.com/forum/#!forum/kubernetes-dev)

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).

[owners]: https://git.k8s.io/community/contributors/guide/owners.md
[Creative Commons 4.0]: https://git.k8s.io/website/LICENSE
