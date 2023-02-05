
# What is **Cloud Native Applications**?
The **Cloud Native Applications** platform provides a comprehensive set of pre-prepared templates to simplify the creation of cloud-based applications. These templates are designed to streamline the development process and make building cloud native applications a breeze.

# Motivation and Inspiration
The **Cloud Native Applications** templates are built with a strong focus on the following principles and best practices:

* Emphasis on cloud native principles and practices.
* Adherence to the 12 Factors App methodology.
* Utilization of development containers for seamless and consistent development.
* Prioritizing the use of best practices for cloud development.
* Automated Continuous Integration and Continuous Deployment (CI/CD).
* Adoption of GitOps for managing production environments.


# Features
The **Cloud Native Applications** templates come equipped with the following components and features to assist in the development process:

* Development Containers manifest:
    * The Development Containers manifest, included in the **Cloud Native Applications** templates, provides a consistent development environment for developers.
    * Development container manifrst provides a centralized configuration for the development environment, including the definition of development containers. This allows for consistent and seamless development among different developers, ensuring that everyone is working with the same set of tools and dependencies.
* The source code of the selected application framework:
    * This includes the core code of the chosen framework, providing a solid foundation for building your cloud native application.
* Docker image build file:
    * This file specifies how to build the Docker image for the application, providing a consistent and portable environment for development and deployment.
* Kubernetes deployment manifests:
    * These manifests describe how the application should be deployed on a Kubernetes cluster, providing a simple and scalable way to run your application in the cloud.
    * The **Cloud Native Applications** templates utilize Helm for templating and packaging the application into a Helm chart. This provides a simple and effective way to manage the deployment of your cloud native application on a Kubernetes cluster.
    * Alternatively, the **Cloud Native Applications** templates utilize Kustomize for templating the Kubernetes deployment manifests. This allows for a more flexible and customizable way to manage the Kubernetes deployment manifests.
* Cloud development manifest:
    * For the cloud development manifests, we use the popular and widely-used cloud development platform called Okteto.
    * Okteto provides developers with an efficient way to develop, test, and debug their cloud applications directly in a Kubernetes cluster in the cloud, without having to worry about setting up and maintaining local development environments. This results in faster development times and better collaboration between developers.
* Continuous Integration and Continuous Deployment (CI/CD) files:
    * These files define the automated processes for continuous integration and deployment, ensuring a smooth and efficient pipeline for releasing new updates to your application.

This comprehensive set of components and features provides developers with a robust and ready-to-use foundation for building cloud native applications.
