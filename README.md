# TODO Backend with .NET 8

## Description

This project is a backend solution for a TODO application, following the Domain-Driven Design (DDD) principles to ensure clean architecture and maintainability. It leverages the Command Query Responsibility Segregation (CQRS) pattern to separate read and write operations, enhancing performance and scalability.

## Technologies

- **.NET 8**: The latest iteration of the .NET framework, enabling high-performance, cross-platform applications.
- **Entity Framework**: An object-relational mapper (ORM) for .NET, used for data access.
- **Serilog**: A diagnostic logging library for .NET, providing a simple, structured logging solution.
- **Redis**: An in-memory data structure store, used as a database, cache, and message broker.
- **Fluent Validation**: A library for building strongly-typed validation rules.
- **MediatR**: A simple, unambitious mediator implementation in .NET for in-process messaging.

## Setup

To get the project up and running on your local machine, follow these steps:

1. Ensure you have [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) installed.
2. Clone the repository to your local machine.
3. Navigate to the project directory and restore the dependencies:
