# Kubernetes The Hard Way
https://hakengineer.xyz/2019/06/28/post-1932/



## Cluster Details

Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication.

* [Kubernetes](https://github.com/kubernetes/kubernetes) 1.12.0
* [docker](https://github.com/docker/docker-ce) 18.09.6
* [calico](https://github.com/projectcalico/calico) v3.7.3
* [etcd](https://github.com/coreos/etcd) v3.3.9
* [CoreDNS](https://github.com/coredns/coredns) v1.2.2

## Labs

This tutorial assumes you have access to the AWS.

* ~~01-Prerequisites~~
* [02-Installing the Client Tools](docs/02-client-tools.md)
* ~~03-Provisioning Compute Resources~~
* [04-Provisioning the CA and Generating TLS Certificates](docs/04-certificate-authority.md)
* [05-Generating Kubernetes Configuration Files for Authentication](docs/05-kubernetes-configuration-files.md)
* [06-Generating the Data Encryption Config and Key](docs/06-data-encryption-keys.md)
* [07-Bootstrapping the etcd Cluster](docs/07-bootstrapping-etcd.md)
* [08-Bootstrapping the Kubernetes Control Plane](docs/08-bootstrapping-kubernetes-controllers.md)
* [09-Bootstrapping the Kubernetes Worker Nodes](docs/09-bootstrapping-kubernetes-workers.md)
* ~~[10-Configuring kubectl for Remote Access]~~
* [11-Provisioning Pod Network Routes](docs/11-pod-network-routes.md)
* [12-Deploying the DNS Cluster Add-on](docs/12-dns-addon.md)
* [13-Smoke Test](docs/13-smoke-test.md)
* ~~[14-Cleaning Up]~~
