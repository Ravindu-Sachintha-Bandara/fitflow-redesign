# FitFlow Redesign

Cross-platform fitness app (iOS / Android / Web) with personalised AI workout plans, social sharing and nutrition tracking. Built for IT3060 Lab Exercise 05.

## Tech stack
- Frontend: Flutter (Dart)
- Backend: NestJS (TypeScript) + WebSocket gateway
- AI service: Python FastAPI
- Data: PostgreSQL 16, Redis, Amazon S3
- Auth: AWS Cognito (OAuth2/OIDC, JWT, MFA)
- Cloud: AWS (ECS Fargate, CloudFront, WAF)

## Documentation
- [Tech stack summary](docs/tech-stack.md)
- [Comparison matrix](docs/comparison-matrix.md)
- [Architecture diagram](docs/architecture/architecture.png)
- [ADR-001](docs/adr/ADR-001-core-stack.md), [ADR-002](docs/adr/ADR-002-ai-microservice.md)

## Contributing
Branch from `main`, open a PR, require 1 review and passing CI.
