## 🌼 Deployment Options for Java Apps on Azure

- Virtual machines
- Containers
- Azure Kubernetes Service (AKS) is a managed Kubernetes service.
- Azure Red Hat OpenShift is the Red Hat-managed variety of Kubernetes.
- Azure Container Instances is a solution for quick tests, proofs of concept, and sidecar containers.

- Azure App Service
- Azure Spring Apps
- Functions



## Application deployment types
- Virtual machines, containers, or platform as a service
- Whether you use VMs, containers, or a PaaS solution, you can usually deploy your Java applications to the cloud in either of two ways:

Source-code deployment: You commit your source code to a Git repository and the cloud provider runs a process that compiles, builds, and packages the application.
JAR, WAR, or EAR file deployment: You package your application, usually as an executable JAR (Java ARchive) file, but WAR (Web Application ARchive), EAR (Enterprise Application ARchive), and other file formats are also possible. The cloud provider then runs the executable file.
