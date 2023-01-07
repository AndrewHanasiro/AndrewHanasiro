# Andrew Hanasiro

Over those 5 years, I learned to build reliable and maintainable systems using SOLID, 12 factors as a guide for my choices. I started with the front end with React (at the time it was class-based) and then I tried Vue, both with firebase for the back end. A while later I learned more about the backend which comes with database types, microservice trade-offs, observability concepts and etc.

On the front end, I learned about how the browser works with DOM, critical rendering path, responsive design, SEO, client storage (local storage. session storage, and cookie) virtual DOM, component life-cycle, state management (Redux), Hook (useState, useEffect, useContext and etc) and a little bit of UX with 10 heuristics of Nielsen
 
On the back end, I learned about how to implement SOLID principles in code, 12 factors for struct our application to behave equally in regard to the environment, Testing best practices with independency of each test, mocking for unit tests, and intercept for integration. Also worked with Queue to execute asynchronous jobs and Message Brokers as RabbitMQ (can guarantee order) and Kafka to event-driven architecture. For containers with Docker, I learned to build custom images with multi-stages, diff between alpine/slim/buster and etc.

On database concepts, I learned a lot about relational databases (Postgres, MariaDB) as constraints, indexes, procedures, and transactions, On the NoSQL database (Redis, MongoDB) I learned of high availability and partitioning. But most of all, the important thing is when to use each kind of database.

On microservice concepts, I learned about dividing concerns into multiple services toward scalability, independent deployments, stack diversity and etc but at cost of consistency, interface between services, tracing complexity and etc.

On Observability concepts, I learned a lot of metrics (Counter. Gauge, and Histogram) trace (event and distributed tracing), and logging (level, transporter)

## Auth+

This project below is still in progress but already has a lot of my knowledge and experience. Since, each of those systems is quitely big, I just put the link. Each one of them has a detailed description. This project should simulate  a real organization as a Startup! All those projects must challenge me in a way: language, concepts, or tools.

### Pitch Deck

A lot of startups have a dilemma: should I create from zero **or** should I pay to use? The trade-off is simple,

- Cons of Creating a new one
  - time to waste
  - the human effort to code
  - the risk of making incorrect/mistakes
  - maintenance after done
- Cons of integration
  - a high cost
  - the effort to integrate.
  - a high cost to customize if necessary

Auth+ has small startup as a target, offering all kind of system at low cost, but also offering support to customize. Monetizing for each system that the client wants to subscribe

### Competitors

#### Authentication

- <https://authrocket.com/plans>
- <https://auth0.com/pricing>
- <https://www.onelogin.com/>
- <https://aws.amazon.com/pt/cognito/pricing/>

#### Notification

- <https://sendgrid.com/pricing>
- <https://mailchimp.com/pt-br/pricing/marketing/>
- <https://onesignal.com/pricing>
- <https://aws.amazon.com/pt/sns/pricing/>
- <https://www.braze.com/>

#### Billing

- <https://recurly.com/plans/>
- <https://www.chargebee.com/pricing/?ref=navbar>
- <https://www.zuora.com/>

### Repositories

1. [Authentication](https://github.com/auth-plus/auth-plus-authentication)
2. [Notification](https://github.com/auth-plus/auth-plus-notification)
3. [Billing](https://github.com/auth-plus/auth-plus-billing)
4. [Tools](https://github.com/auth-plus/auth-plus-tools)
5. [Infra](https://github.com/auth-plus/auth-plus-infra)
