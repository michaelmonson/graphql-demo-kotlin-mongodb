
# GraphQL QuickStart with Spring Boot, Kotlin and MongoDB

GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

In this article, we’ll see what is GraphQL, the benefits of using GraphQL by building a simple GraphQL server with Spring Boot and MongoDB, and its benefits over REST implementation.

## How GraphQL solves REST API drawbacks:

* GraphQL provides the flexibility to consumers to request for the attributes as needed i.e., it provides dynamic data in request. The REST API response is always fixed, as it sends the entire JSON object for every request.
* REST API has over-fetching and under-fetching problems.
* Better performance with lesser code.
* GraphQL exposes a single endpoint for all the operations with Query and Mutation and its HTTP POST method. In REST, every operation has a separate API using different HTTP verbs(GET, PUT, POST, DELETE) as per the requirement.
* GraphQL depends on Schema file defined for the application. Only Properties or operations specified on Schema file will be exposed to consumers.

### LINK: https://medium.com/geekculture/graphql-quickstart-with-spring-boot-kotlin-and-mongodb-c16f301b8aeb

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.6.7/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.6.7/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.6.7/reference/htmlsingle/#boot-features-developing-web-applications)
* [Spring Data MongoDB](https://docs.spring.io/spring-boot/docs/2.6.7/reference/htmlsingle/#boot-features-mongodb)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
