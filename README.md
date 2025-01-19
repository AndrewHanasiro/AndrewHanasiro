# Andrew Hanasiro

Over those 6 years, I learned to build reliable and maintainable systems using SOLID, 12 factors as a guide for my choices. I started with the front end with React (at the time it was class-based) and then I tried Vue, both with Firebase for the back end. A while later I learned more about the backend which comes with database types, microservice trade-offs, observability concepts, etc.

On the front end, I learned about how the browser works with DOM, critical rendering path, responsive design, SEO, client storage (local storage. session storage, and cookie) virtual DOM, component life-cycle, state management (Redux), Hook (useState, useEffect, useContext, etc) and a little bit of UX with 10 heuristics of Nielsen
 
On the back end, I learned about how to implement SOLID principles in code, 12 factors for structuring our application to behave equally regarding the environment, Testing best practices with the independence of each test, mocking for unit tests, and intercepting for integration. Also worked with Queue to execute asynchronous jobs and Message Brokers as RabbitMQ (can guarantee order) and Kafka to event-driven architecture. For containers with Docker, I learned to build custom images with multi-stages, diff between alpine/slim/buster, etc.

On database concepts, I learned a lot about relational databases (Postgres, MariaDB) as constraints, indexes, procedures, and transactions, On the NoSQL database (Redis, MongoDB) I learned of high availability and partitioning. But most of all, the important thing is when to use each kind of database.

On microservice concepts, I learned about dividing concerns into multiple services for the benefit of scalability, independent deployments, stack diversity, etc but at the cost of consistency, interface between services, tracing complexity, etc.

On Observability concepts, I learned a lot about metrics (Counter. Gauge, and Histogram) trace (event and distributed tracing), and logging (level, transporter)

## Auth+

This project below is still in progress but already has a lot of my knowledge and experience. Since each of those systems is quite big, I just put the link. Each one of them has a detailed description. This project should simulate  a real organization as a Startup! All those projects must challenge me in a way: language, concepts, or tools.

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

Auth+ has a small startup as a target, offering all kinds of systems at low cost, but also offering support to customize. Monetizing for each system that the client wants to subscribe

### Repositories

1. [Authentication](https://github.com/auth-plus/auth-plus-authentication) (Typescript/Express/winston/Knex/Mocha/ts-mockito/casual)
2. [Notification](https://github.com/auth-plus/auth-plus-notification) (Go/Gin/Zap/Testify/Gock/Faker)
3. [Billing](https://github.com/auth-plus/auth-plus-billing) (Rust/Actix/sqlx/Mockall/Fake)
4. [Client](https://github.com/auth-plus/auth-plus-client)(Typescript/Svelte/Vite/Playwright)
5. [Monetization](https://github.com/auth-plus/auth-plus-monetization) (Python/FastAPI/SQLAlchemy/Pytest)
6. [Infra](https://github.com/auth-plus/auth-plus-infra) (Pulumi)
7. [Symphony](https://github.com/auth-plus/auth-plus-symphony) (Prometheus/Zipkin/ELK/Kafka)

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


