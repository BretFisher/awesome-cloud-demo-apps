<!--lint disable awesome-contributing awesome-git-repo-age awesome-toc awesome-list-item-->
# Awesome DevOps Demo Apps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An awesome list of example server apps used for learning and demoing DevOps, cloud, and distributed computing technologies.

These apps are not for learning to code, but rather how to build, test, and deploy code to servers and the cloud. They are often used in workshops, courses, and conference talks for demoing something else in DevOps and infrastructure management.

This Awesome List is maintained by [@BretFisher](https://github.com/BretFisher). This is a curated list of *working* and *awesome* sample server apps.

## Contents<!-- omit from toc -->

- [Other lists of apps](#other-lists-of-apps)
- [Simple Apps (1-3 independent services/apps in solution)](#simple-apps-1-3-independent-servicesapps-in-solution)
- [Complex Apps (4+ independent services/apps in solution)](#complex-apps-4-independent-servicesapps-in-solution)
- [Serverless Functions (might be purely serverless)](#serverless-functions-might-be-purely-serverless)
- [IOT and Edge Computing](#iot-and-edge-computing)
- [LLMs and Machine Learning](#llms-and-machine-learning)
- [Chat and Forums](#chat-and-forums)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

## Other lists of apps

- [DevOps Demo Apps](https://github.com/devopsdemoapps)
- [AWS Samples](https://github.com/aws-samples)

## Simple Apps (1-3 independent services/apps in solution)

- [RealWorld example apps](https://github.com/gothinkster/realworld) - A collection of example Medium.com clones that adhere to the RealWorld API spec
- [Worthsmith](https://github.com/dockersamples/wordsmith) - A traditional Web + API + DB app for randmoly generating words. Has Docker Compose and Kubernetes example YAML.
- [Browncoat](https://github.com/BretFisher/browncoat) - A server app designed to fail in various ways for testing orchestration, healthchecks, and recovery. "It aims to misbehave"
- [Stress](https://github.com/BretFisher/stress) - A simple set of container images for stressing CPU and memory. Useful for testing autoscaling and monitoring.
- [Spring PetClient Sample Application](https://github.com/spring-projects/spring-petclinic) - The Spring PetClinic is an open-source sample application developed to demonstrate the database-oriented capabilities of Spring Boot, Spring MVC, and the Spring Data Framework. It’s based on this Spring stack and built with Maven.  [Blog Post](https://www.docker.com/blog/containerizing-a-legendary-petclinic-app-built-with-spring-boot/)  

## Complex Apps (4+ independent services/apps in solution)
Bl
- [Google Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo) - A cloud-native microservices demo app for Google Cloud Platform (GCP). Has Dockerfiles, Kubernetes manifests, and Helm charts.
- [Sock Shop](https://github.com/microservices-demo/microservices-demo) - A microservices demo application that was maintained by Weaveworks. It's now deprecated, but should still work. Has Docker Compose and Kubernetes example YAML. Also has logging and monitoring YAML.
- [Voting App](https://github.com/dockersamples/example-voting-app) - A distributed application that runs across multiple Docker containers. Has Docker Compose and Kubernetes example YAML.
- [Azure Microservices Reference Implementation](https://github.com/mspnp/microservices-reference-implementation) - A reference implementation, along with additional demos like [AKS Fabrikam Drone Delivery demo](https://github.com/mspnp/aks-fabrikam-dronedelivery) that demonstrates a microservices architecture based on Azure Kubernetes Service (AKS).
- [Microservices version of the Spring PetClinic](https://github.com/spring-petclinic/spring-petclinic-microservices) - Distributed version of Spring Petclinic built with Spring Cloud and Netflix Eureka Server.  Also has Zipkin for Tracing, Prometheus & Grafana.  Grafana and Prometheus are included in the docker-compose.yml configuration, and applications have been instrumented with [MicroMeter](https://micrometer.io/) to collect JVM and custom business metrics. A JMeter load testing script is available to stress the application and generate metrics.

## Serverless Functions (might be purely serverless)


## IOT and Edge Computing


## LLMs and Machine Learning


## Chat and Forums

- [Discord - Cloud Native DevOps](https://discord.gg/devops) - Maintained by [@BretFisher](https://github.com/BretFisher) and friends.<!--lint ignore double-link-->

## Related Awesome Lists

While this list is focused on Docker Swarm resources, general resources such as ones for Docker or Docker Compose can be helpful. The following keeps track of related awesome lists focused on this.

- [awesome-docker](https://github.com/veggiemonk/awesome-docker) - A list of awesome Docker tools.
- [awesome-compose](https://github.com/docker/awesome-compose) - A list of awesome Docker Compose samples.


## Contributing

This list thrives on contributions from the community. The Maintainers can't do it alone. We need DevOps/Cloud fans to help us find the best demo apps.

Want to contribute? Please read the [contribution guidelines](contributing.md). You can also ask questions in the [GitHub Discussions](./discussions), or our [Discord - Cloud Native DevOps](https://discord.gg/devops).

Guidelines for submitting demos to this list:

- Must be a working example app that can be deployed to a server or cloud
- Must have a public repo with an open-source license
- Must and instructions on how to build and run
- Ideally, has a deployment tutorial with it (but not required)
- Can exist in multiple categories if it fits
