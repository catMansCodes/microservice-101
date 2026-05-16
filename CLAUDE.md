# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **documentation-only repository** — a structured learning roadmap for mastering Microservices Architecture from beginner to production level. There is no application code, build system, or test suite. The entire content is in `README.md`.

## Repository Content

`README.md` is a 20-chapter roadmap covering:

- **Foundations**: Microservices fundamentals, Spring Boot service construction
- **Communication**: REST (OpenFeign/WebClient), Resilience4j patterns (circuit breaker, retry, bulkhead)
- **Infrastructure**: Eureka service discovery, Spring Cloud Config, Spring Cloud Gateway
- **Security**: JWT, OAuth2, Spring Security resource/authorization servers
- **Observability**: ELK stack, distributed tracing (Zipkin/Jaeger), Prometheus + Grafana
- **Event-Driven**: Kafka deep dive, Saga pattern, CQRS, event sourcing
- **Deployment**: Docker, Kubernetes, CI/CD (GitHub Actions/Jenkins), cloud platforms

**Recommended tech stack** from the roadmap: Spring Boot + Eureka + Spring Cloud Gateway + OpenFeign + Kafka + PostgreSQL + Redis + Spring Cloud Config + Prometheus/Grafana + ELK + Docker + Kubernetes.

## Working in This Repo

Tasks here will almost exclusively involve editing `README.md` — adding sections, reorganizing content, fixing formatting, or expanding topic coverage. Keep the existing emoji-based section heading style and `---` horizontal rule separators consistent with the current document structure.
