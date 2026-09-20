# ADR-001: Adopt Flutter + NestJS + PostgreSQL + Cognito
- Status: Accepted (20 Sep 2026)
- Context: Seamless iOS/Android/web experience, secure health data, real-time and AI features, mid-sized team.
- Decision: Flutter clients; NestJS core API and real-time gateway; PostgreSQL (RDS) + Redis + S3; AWS Cognito; ECS Fargate.
- Alternatives: React Native + Node/MongoDB + Auth0 (3.41); Flutter + Firebase (3.82); Native + Go + DynamoDB (3.43).
- Consequences: single client codebase and strong compliance posture; Dart skills and AWS configuration effort needed; Flutter web SEO limits.
