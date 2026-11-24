![108 monogram drawn with circuit traces](assets/profile-cover.svg)

# Andrey Romanov · Software Engineer

I build backend services and APIs in **Go** and **Java**. I have 4+ years of professional experience, including work in insurance and fintech.

## Selected work

- **Home assistance** — As the sole backend developer, I worked directly with the business team to build a service that let customers request help from their phones. It moved about **200 requests a day** out of the call center.
- **Motor insurance** — I built workflows around a shared, versioned API contract. The team estimated that onboarding a new product went from **4–6 weeks to 1–2 weeks**.
- **Credit decisioning** — I helped move credit strategies out of a monolith into services the team could deploy independently. This cut the time to launch a strategy from **10 business days to 3**.

## How I work

I work with domain experts to understand how a business process works, then design the service boundaries and API contracts around it. One question I ask early is whether a team can change a rule and ship it without coordinating a release with every system that uses it.

I stay involved after deployment. For event-driven workflows, I use a transactional outbox to keep database changes and outgoing events together, and idempotent consumers so a retry can’t create a second request. I also work on delivery pipelines and use logs, metrics, and traces to diagnose failures in production.

[Email](mailto:ravdev108@gmail.com) · [LinkedIn](https://www.linkedin.com/in/andrey-romanov-software-engineer)

## Technical stack

- **Go** · pgx, sqlc, Goose, Testify, golangci-lint
- **Java** · Java 17/21, Spring Boot, Spring Data JPA, Hibernate, JUnit 5, Mockito
- **APIs & contracts** · REST, OpenAPI, ogen, gRPC, Protocol Buffers, Buf
- **Data & messaging** · PostgreSQL, MySQL, Redis, Apache Kafka, RabbitMQ
- **Integration testing** · Testcontainers for Go and Java

### DevOps & observability

- **Infrastructure as code & configuration management** · Terraform, Ansible
- **Containers & orchestration** · Docker, Docker Compose, Kubernetes, OpenShift
- **CI/CD** · GitHub Actions, GitLab CI, Jenkins, Argo CD
- **Metrics, logs & tracing** · Prometheus, Grafana, Loki, Tempo, Graylog
