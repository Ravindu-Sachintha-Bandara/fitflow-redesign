# ADR-002: Isolate AI in a Python FastAPI microservice
- Status: Accepted (20 Sep 2026)
- Context: ML libraries are Python-based; AI has different scaling and release cadence.
- Decision: Internal-only FastAPI service via OpenAPI/gRPC; queue for long tasks; minimal pseudonymised data.
- Alternatives: ML inside NestJS; client calling third-party AI directly.
- Consequences: independent scaling and privacy control; extra runtime and network hop.
