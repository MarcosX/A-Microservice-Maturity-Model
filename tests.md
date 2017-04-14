

1. **Isolated testing:Each service is tested on its own, with unit tests using doubles or component tests using doubles or in-memory storage**

2. **Integrated testing:Services are tested considering the communication paths and interaction between components, including their contracts**

3. **Consumer-driven Contract testing:Services are continuously tested against the contract provided by their consumers, ensuring they work as expected by external clients**

4. **Cross functional testing:Traits like response time, availability, load, security are tested across all services ensuring the cross functional requirements are met**

5. **Production monitoring through tests:Tests are continuously made in production to find bottlenecks and fix issues before customer even sees them, making the system antifragile.**


