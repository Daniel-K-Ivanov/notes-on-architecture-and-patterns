# Notes on Architecture and Patterns
In this repo you can find some useful notes on Software Architecture and design patterns that I stumbled upon that I think are worth writing down.

## Useful websites:

- Blog of Martin Fowler - [https://martinfowler.com/videos.html](https://martinfowler.com/videos.html)

## Tech Notes:

### Event-driven Architecture

([https://www.youtube.com/watch?v=STKCRSUsyP0](https://www.youtube.com/watch?v=STKCRSUsyP0)) 

- Events are generally used to reverse the dependencies between 2 systems. When we have events, we have a "thing" an object that we can talk about.
- The price paid on Availability is lack of consistency - a.k.a Eventual Consistency

### Microservices

([https://www.youtube.com/watch?v=wgdBVIX9ifA](https://www.youtube.com/watch?v=wgdBVIX9ifA))

- Don't get to microservices if you don't understand your module boundaries well

**Important Characteristics**
- Componentization via Services
- Organized around Business Capabilities
- Products not Projects
- Smart endpoints and dumb pipes
- Decentralized Governance
- Decentralized Data Management
- Infrastructure Automation
- Design for failure
- Evolutionary Design
- Choreography over orchestration

**Mandatory things for microservices:**

1. Rapid provisioning
2. Monitoring
3. Rapid Application Deployment
4. DevOps culture

**Netflix Principles:**
- Buy vs Build - use of-the-shelf-components; only build what you have to
- Services must be stateless (except for persistence and caching layers)
- Scale out instead of Scale up

**Good enought Architecture**:
- There is no good or bad architecture without context; architecture needs to take specific quality attributes into account
- Highly specific code is preferable to sophisticated configuration
- Small is not always beautiful
- Centralised responsibility hurts
- Lack of standartization leads to vast differences in API style, formats, documentation etc -> which creates needles extra work. 

