# Welcome to the Common Core Library Project!

The Common Core Library is a comprehensive set of features, libraries, and guidelines designed to streamline the development process for REST API Services based on the Spring Framework. It addresses common challenges and repetitive tasks that developers face, such as security, data access, validation, and error handling. By building on top of widely-used core frameworks and libraries, the Common Core Library provides a cohesive structure that promotes best practices and consistency across projects.

The Common Core Library is essential because it reduces the complexity and effort involved in developing and maintaining large-scale software systems. It offers a standardized approach that simplifies the organization, deployment, and operation of applications, making it easier for teams to collaborate and scale their projects.

## Getting Started

Follow these instructions to set up and use the project.

### Prerequisites

Ensure you have the following prerequisites installed:

* Java Development Kit (JDK) 21 or higher
* Spring Boot
* Maven

### Installation

The Common Core Library includes numerous features. To include this library in your project, add the following dependency to your build tool's configuration file. Replace `${libraryVersion}` with the appropriate version number.

**Maven**

Add the following dependency to your `pom.xml` file:

```xml
<dependency>
    <groupId>com.mq</groupId>
    <artifactId>common-core-lib</artifactId>
    <version>${libraryVersion}</version>
</dependency>
````

**Gradle**

Add the following dependency to your `build.gradle` file:

```groovy
// Gradle
implementation "com.mq:common-core-lib:$libraryVersion"
```

## Contributing

Our project welcomes contributions from any member of our community. To get started, please see our [Contributing Guide] (https://<link>/CONTRIBUTING.md)


## Scope

The Common Core Library implements a comprehensive set of features, including authentication/authorization, data access, identifier generation, error handling, and utilities. These features are implemented through widely-adopted frameworks and libraries such as Spring Security, Spring Data JPA, and JWT libraries. The architecture is designed to be modular and scalable, ensuring ease of integration and maintenance.

### In Scope

The Common Core Library is intended to provide a standardized framework for developing, deploying, and maintaining REST API services. As such, the project implements or has implemented:

  * **Core:**

      * **Base Classes:** Provides main parent classes for entities and Data Transfer Objects (DTOs), such as `BaseEntity` and `AbstractDto`.
      * **Error Handling:** Standard logic for consistent error handling, including `ApiExceptionHandler`, `DataExceptionResolver`, and a suite of custom `RestException` classes.
      * **Configuration:** Standard configurations for web services and security, including auto-configuration for JWT and service properties.
      * **Dependencies:** Manages standard dependencies to provide cross-cutting concerns and integrations.

  * **Auth (Authentication/Authorization):**

      * Powered by Spring Security with JSON Web Token (JWT) integration.
      * Includes components like `AuthenticationFilter`, `JwtAuthResolver`, and `HmacJwsProvider` for token creation and validation.
      * Supports user identity and authority management via components like `AuthHolder` and `AuthorizationProcessor`.

  * **Data Access:**

      * Supports data access and auditing with Spring Data JPA.
      * Provides base entity classes (`BaseEntity`, `AuditEntity`) with automatic tracking of creator, updater, and timestamps.
      * Includes `JpaAuditorAware` for integration with Spring Security to identify the current user.

  * **Identifier Generation:**

      * Provides a ULID (Universally Unique Lexicographically Sortable Identifier) implementation for generating unique, time-sortable identifiers.
      * Includes `UlidGenerator` for automatic ID generation in Hibernate.

  * **Web/REST Support:**

      * Provides standard filters like `CustomCorsFilter` and `RequestLoggingFilter` for handling HTTP requests.
      * Manages request context with `RequestContext` and `RequestInfo` for tracing and logging.
      * Standardized response structure using `ActionResult` and `ErrorResponse`.

  * **Validation:**

      * Provides utilities for data validation using `ValidateUtils` and `ChainValidator`.
      * Supports custom validation annotations like `@EmailAddress`, `@Password`, `@UuidCode`, and `@UlidCode` to enforce data rules.

  * **Utilities:**

      * **String Utils:** Provides a set of helper functions for manipulating strings.
      * **Collection Utils:** Provides a set of helper functions for manipulating collections.
      * **DateTime Utils:** Provides a set of helper functions for manipulating dates and times.
      * **Hash Utils:** Provides functions to generate MD5 and SHA-256 hashes.
      * **IO Utils:** Provides helper functions for file I/O operations.
      * **Correlation Utils:** Manages correlation IDs for request tracing.

### Out of Scope

N/A

## Communications

  * User Mailing List: mqc@gmail.com
  * Developer Mailing List: mqc@gmail.com
  * MS Teams Channel: N/A
  * Public Meeting Schedule and Links: N/A
  * Social Media: N/A
  * Other Channel(s), If Any: N/A

## Resources

  * Resource Allocation: N/A
  - Dev team: "Cao Minh Quang" <mqc@gmail.com>
  - Test team: "Cao Minh Quang" <mqc@gmail.com>.
  * Onboarding and supporting: "Cao Minh Quang" <mqc@gmail.com>.

## Documents

  * Guideline: N/A

## License
N/A
