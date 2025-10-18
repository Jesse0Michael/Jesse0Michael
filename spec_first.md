# Spec-First Development

Before rushing to implementation, design the spec of the system first. The spec is the contract between services. It is structured and defined by those implementing it and those consuming it. It is the source of truth for how the system should behave. The specification for a feature should be thought through first and should be the most critically reviewed PR of a system.

[OpenAPI](https://swagger.io/specification/) | 
[Protocol Buffers](https://developers.google.com/protocol-buffers) |
[AsyncAPI](https://www.asyncapi.com/) |
[JSON Schema](https://json-schema.org/)

> *Weeks of programming can sometimes save you hours of planning.*

### Shared Understanding
Everyone involved in the project (frontend, backend, QA, and PM) will be aligned on what the feature is and how its going to be used.

Misunderstandings are surfaced *before* code is written.

Issues around 'what problem does this solve?' or 'why do we need this field?' are caught early and wasteful work is avoided.

### Parallel Work
With a well defined API spec, all teams involved can begin work in parallel instead of waiting for backend implementation to be finished.
- Backend can implement the logic, validating against the spec.
- Frontend can generate mock clients or fake servers, knowing exactly what to expect.
- QA can build tests against the spec before backend is finished.

### Built in Documentation
A spec is as much documentation as it is a contract. It describes the shape of requests and responses, error codes, authentication methods, and more. It can be referenced by anyone on the team to understand how the system works.

### Tooling
There are many code generation tools for different spec formats that can generate server stubs, clients, and mocks. This reduces boilerplate code and ensures consistency between implementation and spec.

[oapi-codegen](https://github.com/deepmap/oapi-codegen) | 
[buf.build](https://buf.build)

## References
- [5 Principles of API-First Development](https://www.algolia.com/blog/product/the-5-principles-of-api-first-development-and-what-does-api-first-even-mean)
- [Guide to API-First](https://www.postman.com/api-first/)
