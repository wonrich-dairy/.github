# Wonrich Dairy — Quality Monitoring & Traceability System

A microservices-based quality-monitoring and traceability platform for **Wonrich Dairy (Pvt) Ltd**, built as a SLIIT 3rd-year Case Study Project.

## Repositories

| Repository | Purpose |
|---|---|
| [mcc-intake-service](https://github.com/wonrich-dairy/mcc-intake-service) | MCC & Intake Service — raw milk quality metrics, bowser dispatch notes, factory-intake condition logging |
| [quality-lab-service](https://github.com/wonrich-dairy/quality-lab-service) | Quality Lab Service — laboratory test results and quality grading |
| [processing-service](https://github.com/wonrich-dairy/processing-service) | Processing Service — pasteurisation, homogenisation, and production batch tracking |
| [traceability-dashboard-service](https://github.com/wonrich-dairy/traceability-dashboard-service) | Traceability Dashboard Service — end-to-end batch traceability and reporting |
| [frontend](https://github.com/wonrich-dairy/frontend) | React frontend — unified UI for all services |
| [shared-test-panel](https://github.com/wonrich-dairy/shared-test-panel) | Shared Test Panel — reusable test-parameter library consumed by multiple services |

## Tech Stack

- **Backend:** ASP.NET Core + Entity Framework
- **Database:** MySQL (one per service)
- **Frontend:** React
- **Messaging:** Apache Kafka
- **Hosting:** Azure App Service (staging + production)
- **CI/CD:** GitHub Actions
- **Containers:** Docker / docker-compose for local development

## Branching Strategy

All repositories follow the same convention:
- `main` — protected, production-ready code
- `develop` — protected integration branch
- `feature/SCRUM-<key>-<description>` — work branches, merged into `develop` via reviewed PR (1 approving review required)

## Team

SLIIT 3rd Year — Group 16
