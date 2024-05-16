# End-to-End Continuous Integration and Continuous Deployment based on GitOps using GitHub Actions and Argo CD 🚀

This repository contains the code of the Deployment and service files.

**The architecture of the project is explained below:**

This is the Manifest Repository that contains the Kubernetes manifests for the application. And our Argo CD will be watching this repository for changes. **Once the image tag is updated in the Manifest Repository, Argo CD will automatically deploy the new version of the application to the Kubernetes cluster**.

## Architecture
![Architecture Diagram](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*4c7Sh3uq-myCRQ16bs0ktg.png)
