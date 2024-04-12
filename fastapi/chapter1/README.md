
## Services and APIs

- application programming interfaces (APIs) that connect things
- An API is a contract, similar to a database schema
-

### RESTful, with these characteristics

#### Representational State Transfer (REST)—an architectural style for HTTP use

- Uses HTTP and client-server protocol
- Stateless (each connection is independent)
- Cacheable
- Resource-based

#### The HTTP verbs are pretty CRUDdy

- POST =Create (write)
- PUT = Modify completely (replace)
- PATCH = Modify partially (update)
- GET =  Um, get (read, retrieve)
- DELETE = Uh, delete

#### A client sends a request to a RESTful endpoint with data in one of the following areas of an HTTP message

- Headers
- The URL string
- Query parameters
- Body values

#### HTTP Resposnes

- An integer status code indicating the following:

  - 100s = Info, keep going
  - 200s = Success
  - 300s = Redirection
  - 400s = Client error
  - 500s = Server error

- Various headers
- A body, which may be empty, single, or chunked (in successive pieces)

#### JSON and API Data Formats

- JavaScript Object Notation (JSON)
- the default web service input and output format

#### JSON:API

#### GraphQL

### Concurrency

Reduce these:

- Latency = The up-front wait time
- Throughput = The number of bytes per second between the service and its callers

Concepts:

- concurrency mostly avoids busy waiting (idling the CPU until a response is delivered)

- Asynchronous systems provide an event loop

### Layers

- Web = Input/output layer over HTTP, which assembles client requests, calls the Service Layer, and returns responses
- Service = The business logic, which calls the Data layer when needed
- Data = Access to data stores and other services
- Model = Data definitions shared by all layers
- Web client = Web browser or other HTTP client-side software
- Database = The data store, often an SQL or NoSQL server
