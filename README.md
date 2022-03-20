# Kubernetes-owncloud
<h1 align=Left>Microservice orchestration platforms<br>
Using Kubernetes<br/>
<h2 align=Left>Implementation of the ownCloud system based on the<br/>Kubernetes cluster</h2>
  
## Description
- The aim of this exercise is to design and deploy production-ready (in terms of reliability,
  security, and efficiency) Kubernetes cluster hosting system of ownCloud services hereinafter
  referred to as system services.
- The system should be composed of software components and publicly available images
  encapsulating services necessary to implement the following features.

## Solution
<h3>Following features have been implemented:</h3>

- [x] system services are available at the dedicated DNS name or at least exposed locally
- [x] all configuration is contained in a dedicated namespace
- [x] database service is not available from outside the cluster
- [x] data persistence is ensured (i.e. data is stored independently of the system services
  container(s))
- [x] system services instances are multiplied to achieve basic availability
- [x] basic cluster monitoring is deployed (e.g. Kuberbetes Dashboard)


---
