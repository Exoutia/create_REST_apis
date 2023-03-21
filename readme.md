- Build a base Flask Project with a REST api
- Handle HTTP requests with Connexion
- Define API end points using OpenAPI spcification
- Interact with your API to manage data
- Build API documentation with Swagger UI

## Refresher
### REST Architecture
REST stands for representational state transfer ans is a software architecture style that defines a pattern for client and server communications over a network. REST provides a set of constraints for software architecture to promote performance, scalability, simplicity and reliability in the system.

REST defines the following architecutural constraints:
- stateless: the server won't maintain any state between requests from the client.
- Client-Server: The client and server must be decoupled from each other, allowing each to develop independently.
- Cacheable: The data retrieved from the server should be cachable either by the client or by the server.
- Uniform interface: The server will provide a uniform interface for accessing resources without defining their representation.
- Layerd system: The client may access the resources on the server indirectly through other layers such as proxy or load balancer.
- Code on demand(optional)