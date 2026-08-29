# Mohit Shakya

I fix Kafka pipelines and Spring Boot services that are falling behind in production.

Seven years of that on telecom and banking systems — the kind that move money and
provision networks, where falling behind is an incident rather than a ticket. I work
independently now, with fintech and telecom teams who need that experience for a few
weeks rather than as a permanent hire.

Fixed prices with the engineering hours stated: **[mohitshaky.github.io](https://mohitshaky.github.io)**

---

### What I get called in for

**Consumers that can't keep up.** Lag climbs under load and never fully recovers.
Usually partitioning, poison messages, or work being done inside the poll loop.

**Latency that has drifted.** p99 doubled across two releases and nobody can point at
the change. Typically connection pools, N+1 access, or GC pressure.

**Systems nobody can see into.** An incident happens and the team reads logs line by
line. Tracing, metrics that map to user impact, and an agreed error budget fix that.

**AI stuck in a prototype.** A notebook demo works, but nobody can get it into a
regulated Java platform with citations, guardrails and a cost ceiling.

---

### Read the code before you decide anything

| | |
|---|---|
| **[order-lifecycle-bpmn](https://github.com/mohitshaky/order-lifecycle-bpmn)** | Telecom order orchestration where the BPMN process definition is the source of truth. Asynchronous provisioning over Kafka, so a slow downstream system never occupies a thread. Multi-tenant with tenant as the partition key. |
| **[banking-account-service](https://github.com/mohitshaky/banking-account-service)** | Append-only account events with an audit projection rebuildable from the log alone. Idempotent consumers that survive at-least-once redelivery without double-applying a transfer. |
| **[offer-promo-engine](https://github.com/mohitshaky/offer-promo-engine)** | Promotion eligibility on the checkout path. Checks ordered by cost so the cheap rejections happen first; definitions cached, usage counts deliberately not — that boundary is where the classic promo-engine bug lives. |
| **[subscription-workflow-service](https://github.com/mohitshaky/subscription-workflow-service)** | Subscription lifecycle as an explicit, versioned process rather than implicit sequencing between services, with compensating paths for failed provisioning. |
| **[enterprise-rag-service](https://github.com/mohitshaky/enterprise-rag-service)** | Retrieval-augmented generation built as an ordinary Spring service. Multi-tenant isolation proved by integration test, a grounding policy that refuses instead of fabricating, versioned prompts, per-tenant token budgets. Spring AI over pgvector. |

---

### Working hours, in your clock

09:00–17:00 CET every working day · 08:00–12:00 ET Monday to Thursday · a full working
day with Dubai, Riyadh and Doha · 5+ hours with Singapore.

I work the Gulf week — available Sunday through Thursday.

---

### Tools

Java 17 / 21 · Spring Boot 3 · Apache Kafka · Flowable BPMN · Spring AI · PostgreSQL ·
pgvector · MongoDB · MySQL · Redis · Docker · Kubernetes · Prometheus · OpenTelemetry ·
Testcontainers · Gradle

---

### Getting hold of me

Currently taking work, two clients at a time. Fastest route is the contact form on
[mohitshaky.github.io](https://mohitshaky.github.io), or
[LinkedIn](https://linkedin.com/in/mohit-shakya-9ab944110).

Send me one repository or one endpoint that is too slow and I will send back three
specific fixes, written down, within two working days. Free, two a week, no obligation —
take the findings to your own team if you like.
