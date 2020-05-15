# IBM Monitoring Prometheus Extension Operator

IBM Monitoring Prometheus Extension Operator is used for installing Prometheus and Alertmanager by extending [community prometheus operator](https://github.com/coreos/prometheus-operator).

The operator is part of IBM Monitoring Operator stack. It provides easier way to install Prometheus and Alertmanager with RBAC and TLS enabled. IBM Monitoring Operator stack is integrated in IBM Cloud Paks and installed as a part of Common Services, but they can also be deployed separately with Operator Lifecycle Manager. Please check the documentation below for any prerequisites required to run the standalone Operator.

## Supported platforms

- x86_64
- ppc64le
- s390x

## Operator versions

- 1.8.0

## Prerequisites

This operator is part of IBM Common Services. You can use OLM or ODLM to install. Other dependencies are as below:

- IBM Cert Manager service for TLS certification management
- IBM Ingress service for access control
- IBM IAM service for RBAC
For the details, please refer to the CRD.

## SecurityContextConstraints Requirements

- privileged SCC for operands
- restricted SCC for operator

## Documentation

For installation and configuration, see [IBM Knowledge Center link](http://ibm.biz/cpcsdocs).

### Developer guide

Information about building and testing the operator.
- Dev quick start
- Debugging the operator

