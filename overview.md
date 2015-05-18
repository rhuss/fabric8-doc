## Overview

Fabric8 provides a number of [applications](fabric8Apps.html) on top of [Kubernetes](http://kubernetes.io) for :

* [Management](management.html) to help you visualise, understand and manage your software
* [Continuous Delivery](cdelivery.html) to help teams delivery software in a faster and more reliable way 
* [iPaaS](ipaas.html) provides an _Integration Platform As A Service_  

If you have an installation of [OpenShift V3 0.5 or later](http://www.openshift.org/)then [install Fabric8 On OpenShift](fabric8OnOpenShift.md)

### Supported Platforms

Fabric8 works great with [Docker](http://www.docker.com/) and implementations of Kubernetes such as [OpenShift V3](http://openshift.github.io/), [Project Atomic](http://www.projectatomic.io/) and [Google Container Engine](https://cloud.google.com/container-engine/).

For non-linux platforms which don't yet support native Docker we have [Jube](jube.html) which is an open source pure Java implementation of Kubernetes.

Kubernetes is supported on Google and Microsofts clouds, by OpenShift V3 (on premise and public cloud), by Project Atomic and VMware; so it's increasingly becoming the standard API to PaaS and _Container As A Service_ on the open hybrid clouds. [Jube](jube.html) then helps extend Kubernetes to run Java based middleware on any operating system which supports Java 7.

