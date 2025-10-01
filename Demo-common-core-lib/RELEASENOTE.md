# Release Notes - Version 0.1.17 - 31 Mar 2025

## 🚀 New Features

- **Sample App**:
    - batch-common: This library contains common projects and utilities for batch processing. It includes shared
      components and functionalities that can be reused across different batch applications, ensuring consistency and
      reducing redundancy.
    - batch-chunk: This sample library showcases the chunk-oriented processing model within our framework. It provides
      examples of how to divide large datasets into manageable chunks and process them in parallel, optimizing
      performance and scalability.
    - batch-tasklet: This sample library illustrates the tasklet-oriented processing model within our framework. It
      includes examples of how to define and execute small, discrete tasks within a batch job, offering flexibility and
      simplicity in batch processing.

## 🛠️ Improvements

## 🐞 Bug Fixes

## 🔧 Maintenance

## 🔒 Security Fixes

## 📚 Documentation

## 🧑‍💻 Contributors

- List the major contributors or teams who worked on this release.
    - **COMMON Java Team** - Primary contributor.

---

# Release Notes - Version 2.0.11 - 06 Mar 2025

## 🚀 New Features

- **Health**: Introduces functionalities to monitor, track, and manage health-related data.
- **FeignClient**: Simplifies HTTP requests in Java applications using Netflix's declarative HTTP client.
- **ValidationJapan**: Ensures string fields or parameters contain only specific Japanese characters.
- **Sample App**:
    - API: Demonstrates the implementation and usage of our framework within a simple skeleton and API.
    - Microservice Demo: Provides a structured approach to building scalable and maintainable microservices.
    
## 🛠️ Improvements

## 🐞 Bug Fixes

## 🔧 Maintenance

- **Fix Sonar**: Addressed issues detected by Sonar.
- **Fix coverity**: Resolved issues identified by Coverity.

## 🔒 Security Fixes

## 📚 Documentation

## 🧑‍💻 Contributors

- List the major contributors or teams who worked on this release.
    - **COMMON Java Team** - Primary contributor.

---

# Release Notes - Version 2.0.9 - 27 Dec 2024

## 🚀 New Features

- **JWT**: Supports jwt securities.


## 🔧 Maintenance

- **Core API**: Enhancements for error handling, request/response formatting, and base class functionalities.
    - **Error Handling**: Improved error response formatting.
    - **Request/Response**: Standardized API request and response formats.
    - **Base Class**: Foundational class with common functionalities.
- **Execution Context**: Manages metadata and context for requests, transactions, or user sessions.
- **Validation**: Provides annotations and utilities for input validation.
- **Logging**: Comprehensive logging with SLF4J2 and MDC, including log masking for sensitive data.
- **JPA**: Handles entity auditing, including tracking changes to entities and maintaining audit logs.
- **Internationalization (I18n)**: Supports multiple languages and regional settings to make the application accessible
  to a global audience.
- **Mybatis**: Simplifies MyBatis integration with automatic configuration, transaction support, useful methods, and
  multi-database support.
- **Utilization**:
    - **Datetime Utils**: Provides utility functions for handling and manipulating date and time values.
    - **Excel Utils**: Offers tools for reading from and writing to Excel files.
    - **Csv Utils**: Includes utilities for processing CSV files, such as reading, writing, and parsing.

## 📚 Documentation

- **ADD (Architecture Design Document)**: Provides a detailed architecture design, including system components, their
  interactions, and design
  decisions. [Link]( /
- **SRS (Software Requirements Specification)**: Describes the software's functionality, performance, and constraints,
  serving as a blueprint for
  development. [Link]( /
- **Technical Design and Guideline**: Each library has a markdown file detailing its design and usage guidelines.
- **Developer Portal**: Centralized platform providing tools, resources, and documentation for
  developers. [Link]()

## 🧑‍💻 Contributors

- List the major contributors or teams who worked on this release.
    - **COMMON Java Team** - Primary contributor.

---

> For detailed information on this release, refer to the full documentation
>
at: [Release Note Folder]( /

## Versioning Information

- **Version**: 0.1.17
- **Release Date**: 31 Mar 2025
