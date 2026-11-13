# Application programming interface api

Interaction layer api's, networked application communication, often but not always mediated over http protocol, 

See also
* DDS
* EIN

## Notes
Concerned with H2M M2H M2M service level interface api's, web service interfaces concern

Objectives
* API's for the AGW project
* Consentrate on interaction layer api protocols and api architecture styles

Comments
* Not concerned here with code level component interface api's, software engineering concern
* Not concerned here with pub/sub broker/hub message queing interface api's, systems integration concern

## Status
TODO
* <todo: consider, install HTTPie cli tool first REST tool evaluation >
* <todo: consider, install Hurl cli testing frist microservice, already have curl installed what is the delta? Hurl has a dependency on libcurl, regression testing cli, >

DONE
* <done: consider, intent to commit>

## Libs

Software - api development, linux, foss, dev + smoke testing, api client app dev env
* Bruno, desktop, git native workflow integration, stored files in git repository, first microservice dev, 
* Insomnia, desktop, native support for gRPC, WebSockets with no paid upgrade, widest protocol support, pros nice ui, cons, electron bloat
* others tbd

Software - api testing, linux, foss, full regression and contract testing frameworks
* <todo: consider, microservice stack suggested by Brave AI to be validated, look for other options, >
* HTTPie, docs [WS](https://httpie.io/), cli, rest only, terminal scripting, one off line add hoc checks, helper tool, dependency python, http/https only - first microservice call
* Hurl, docs [WS](https://hurl.dev/), cli, single static binary rust, plain text tests, dependecy libcurl, http/https only - first microservice regression contract test
* Pact, MIT JS, Apache 2.0 JVM, contracts - second service talks to first
* Schemathesis, MIT, schema - have openAPi spec
* k6, AGPL-3.0, load - require load numbers
* WireMock, Apache 2.0, mocking - stub a service downstream
* Karate, MIT, regression
* REST Assured, Apache 2.0, regression
* Keploy, Apache 2.0, auto-gen, Linux-native, zero-code, 

Protocols - tool support
* REST, request response, JSON/XML
* SOAP, request response, XML
* GraphQL, request response, JSON
* SSE, server sent events, real time streaming
* WebSockets, real time streaming
* gRPC, remote procedure call, 
* MQTT, message queing, message queing telemetry transport, nice to have, but outlier as this is more integration focused than interaction

Technology standards
* JSON
* XML
* ...

Programming languages
* Java, enterprise, Spring Boot, mature ecosystem
* Node.js, JavaScript/TypeScript, I/O intensive server side, 
* Python, RAD, Python3, data driven, machine learning, 
* GO, Goland, cloud native, 
* Rust, extreme performance, binary
* Kotlin, reduced JVM boilerplate, 
* TypeScript, type saftey, 

Libs
* Spring Boot, Java, client side
* Node.js, JavaScript/TypeScript, server side 
* ...

## References

* API
* REST
* WebService

News Papers - architecture styles
* The 6 API Architecture Styles: REST, RESTful, GraphQL, SOAP, gRPC, WebSockets, and MQTT, [WS](https://dev.to/ivannalon/the-6-api-architecture-styles-rest-restful-graphql-soap-grpc-websockets-and-mqtt-2a9h),  14 October 2024, Ivan Nalon
