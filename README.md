# Mohit Shakya

Backend engineer, seven years on telecom and banking systems. Spring Boot, Kafka,
and the unglamorous work of making them fast again once they are not.

I take freelance and contract work — building services, fixing slow ones, and
lately getting AI features into Java codebases that were never designed for them.
Fixed prices, agreed before I start: **[mohitshaky.github.io](https://mohitshaky.github.io)**

---

### What I actually do

Most of what I get called in for falls into four buckets:

**Build a service properly.** REST APIs, Kafka pipelines, BPMN-driven workflows.
Tests, Swagger, Docker and a runbook, so your team can take it over without me.

**Make it fast.** Consumer lag that never recovers, p99 that has doubled over two
releases, queries nobody has looked at since they were written. I measure first,
change second, and measure again.

**Make it visible.** Tracing, metrics and logs that let the next incident be
diagnosed from a dashboard instead of by reading log files line by line.

**Add AI without breaking the compliance story.** Retrieval over your own
documents, running inside your existing Spring estate, with citations, guardrails
and a cost ceiling.

---

### Repositories worth your time

| | |
|---|---|
| **[enterprise-rag-service](https://github.com/mohitshaky/enterprise-rag-service)** | RAG built like a real service, not a notebook. Spring AI over pgvector, multi-tenant isolation proved by test, a grounding check that refuses rather than fabricates, versioned prompts, per-tenant token budgets. |
| **[order-lifecycle-bpmn](https://github.com/mohitshaky/order-lifecycle-bpmn)** | Telecom order orchestration where the BPMN process definition is the source of truth rather than sequencing scattered across services. |
| **[banking-account-service](https://github.com/mohitshaky/banking-account-service)** | Append-only account events with an audit projection that can be rebuilt from the log alone. |
| **[offer-promo-engine](https://github.com/mohitshaky/offer-promo-engine)** | Promotion eligibility on the request path, where cache design and rule ordering decide whether you make the latency budget. |

---

### Tools

Java 17 / 21 · Spring Boot 3 · Spring AI · Apache Kafka · Flowable BPMN ·
PostgreSQL · pgvector · MongoDB · MySQL · Redis · Docker · Kubernetes ·
Prometheus · OpenTelemetry · Gradle

---

### Getting hold of me

Currently taking new work. The quickest route is the contact form on
[mohitshaky.github.io](https://mohitshaky.github.io), or
[LinkedIn](https://linkedin.com/in/mohit-shakya-9ab944110).

If your system is slow and you are not sure why, tell me what it does and what it
is doing wrong. I will tell you honestly whether it is worth paying anyone to
look at it.
