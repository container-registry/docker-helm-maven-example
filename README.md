# Working with Maven, Container and Helm Charts.

This is a fully functional end to end project to demonstrate a best practice  setup when working on Java Maven projects that use Container and Helm Charts and are deployed to Kubernetes.   

This project uses a Spring Boot Web as an application, but this can be easily swapped for anything else.  

# Getting Started


## The Usual Workflow without Maven

```shell
elastic-dijkstra helm repo add --username='robot$example' --password='...'  examples https://8gears.container-registry.com/chartrepo/examples
"examples" has been added to your repositories

```

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.4.1/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.4.1/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.4.1/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

