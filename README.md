[![Docker Repository on Quay](https://quay.io/repository/citrix/citrix-k8s-ingress-controller/status "Docker Repository on Quay")](https://quay.io/repository/citrix/citrix-k8s-ingress-controller)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./license/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/citrix/citrix-k8s-ingress-controller.svg)](https://github.com/citrix/citrix-k8s-ingress-controller/stargazers)
[![HitCount](http://hits.dwyl.com/citrix/citrix-k8s-ingress-controller.svg)](http://hits.dwyl.com/citrix/citrix-k8s-ingress-controller)


# **Description**

This repository contains the Citrix NetScaler Ingress Controller built around  [Kubernetes Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/). This controller automatically configures one or more Citrix NetScaler ADC based on Ingress resource configuration.
Learn more about using Ingress on [k8s.io](https://kubernetes.io/docs/concepts/services-networking/ingress/) 

# **What is an Ingress Controller?**

An Ingress Controller is a controller that watches the Kubernetes API server for updates to the Ingress resource and reconfigures the Ingress load balancer accordingly.

The Citrix Ingress Controller can be deployed either by directly using [yamls](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/deployment/baremetal) or by [helm charts](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/charts).

# **Citrix Ingress Controller Features**

Features supported by Citrix Ingress Controller can be found [here](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/deployment)

# **Deployment Solutions**

Citrix Ingress Controller can be deployed in many platforms. detailed information can be found [here](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/deployment)

# **Examples**

Deploy the Guestbook application and use the [Citrix CPX](https://www.citrix.com/products/citrix-adc/cpx-express.html) to provide the Ingress
* [Quick Deploy using yaml](./example).
* [Quick Deploy using Helm](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/charts/examples).
* [Deployment in Google Cloud](https://github.com/citrix/citrix-k8s-ingress-controller/blob/master/deployment/gcp)
* [Deployment in Azure Cloud](https://github.com/citrix/citrix-k8s-ingress-controller/tree/master/deployment/azure)

# **Questions**
For questions and support the following channels are available:
* [Citrix Discussion Forum](https://discussions.citrix.com/forum/1657-netscaler-cpx/). 
* [NetScaler CPX Slack Channel](https://citrixadccloudnative.slack.com/)

# **Issues**
Describe the Issue in Details, Collects the logs and  Use the forum mentioned below
```
   https://discussions.citrix.com/forum/1657-netscaler-cpx/
  
   Get Logs: kubectl logs citrix-k8s-ingress-controller > log_file
```

# **Code of Conduct**
This project adheres to the [Kubernetes Community Code of Conduct](https://github.com/kubernetes/community/blob/master/code-of-conduct.md). By participating in this project you agree to abide by its terms.

# **License**
[Apache License 2.0](./license/LICENSE)
