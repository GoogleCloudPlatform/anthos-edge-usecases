# Point of Sale (PoS)

**Point of Sale** is a sample application that simulates a retail store kiosk
used to submit and track orders and payments.

This application is used by Google to demonstrate use cases where
[Anthos](https://cloud.google.com/anthos) clusters are installed and run outside
of Google Cloud Platform _(i.e. on premise bare metal infrastructure)_. The
application is representative of **edge deployments** like that of retail
store-front devices.

This repository also hosts a collection of samples and walkthroughs that enables
learning and experimenting with [Anthos](https://cloud.google.com/anthos) for
edge use cases. All of the samples and walkthroughs are built around the
**Point of Sale** application.

> 👓 **Note:** Anthos clusters means Kubernetes clusters that are managed by Anthos.

If you’re using this app, please ★Star the repository to show your interest!

> 👓 **Note to Googlers:** Please fill out the form at [go/using-pos](http://go/using-pos) if you are using this application.

<p align="center">
    <img src="docs/images/pos.png">
</p>

### Edge computing

Edge computing is a distributed computing paradigm that brings computation and
data storage closer to the location where the action is, to improve response
times and save bandwidth. Multiple industries _(e.g. Retail, Telecommunication,
Manufacturing and Energy)_ are facing a growing demand to provide localized,
consistent, low latency services that expose compute services. Workloads range
from order management, ML for images/traffic analysis/safety, device management
like refrigeration, fryers, etc. [Anthos clusters on Bare Metal](https://cloud.google.com/anthos/clusters/docs/bare-metal) and [Anthos cluster on VMware](https://cloud.google.com/anthos/clusters/docs/on-prem)
are unique solutions for deploying and managing workloads on clusters
distributed across customer data centers and device fleets.

---

### Resources
- _(Quickstart)_ [Deploy this application to a cluster](/docs/quickstart.md)
- [Run the entire application in a VM](/extras/anthos-vmruntime/README.md)

#### External use cases of this application
- _(Solution guide)_ [VM based PoS deployed in an Anthos cluster using Anthos VMRuntime](https://github.com/GoogleCloudPlatform/anthos-samples/tree/main/anthos-vmruntime)
- _(Solution guide)_ [Edge deployment of PoS using Anthos on bare metal](https://cloud.google.com/bare-metal/docs/tutorials/abm-edge-at-scale)
- _(Tutorial)_ [PoS deployed in an Anthos bare metal cluster inside Openstack](https://cloud.google.com/anthos/clusters/docs/bare-metal/latest/installing/openstack-abm-install)

---

### Development and Contributing
- Read the [CONTRIBUTING guide](/CONTRIBUTING.md) for instructions on how to contribute
- Follow the [local development guide](/docs/local-dev.md) to learn how to run and develop this app locally

---
### Releases
This repository follows [semantic-versioning](https://semver.org/) to version
its files. Please read [`Releasing a new version of the Point of Sale Application`](/docs/release.md)
for detailed explanation on how to cut a release for this repository.