# Setup Kubernetes with Kubeadm
This page will contain a step-plan to setup Kubernetes on a 3-node (one master, two workers) cluster on VirtualBox.

# Pre-Requisites
To follow the steps you'll need to have applied the following pre-requisites

* [Vagrant](https://developer.hashicorp.com/vagrant/downloads), current version 2.3.4+ installed
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads), current version 7.0.6+ installed
* [VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads), current version 7.0.6+ installed
* [Vagrant - Oracle Linux 8 - Kubernetes GitHub Project](https://github.com/makker-nl/vagrant-ol-kubernetes) cloned 

# Vagrant - Oracle Linux 8 - Kubernetes GitHub Project
For the purpose of this workshop I created a [Vagrant - Oracle Linux 8 - Kubernetes GitHub Project](https://github.com/makker-nl/vagrant-ol-kubernetes), that will bring up three VirtualBox VMs. One is meant for the Kubernetes Master node, and two for the worker-nodes.
I wrote an article on it to do a functional description on this Vagrant project: [Modularizing Multi-machine Vagrant projects](https://martien-van-den-akker.medium.com/a-configurable-multi-machine-vagrant-project-70aff34f1415).
The actual [GitHub Project](https://github.com/makker-nl/vagrant-ol-kubernetes), describes it in more technical detail.