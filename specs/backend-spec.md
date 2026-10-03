# Backend Spec — Trip Planner

> Status: Draft | Owner: <name> | Last updated: <YYYY-MM-DD>
> Related: [goal-spec.md](./goal-spec.md) · [api-contract-spec.md](./api-contract-spec.md)

## 1. Overview
<!-- Summary of the backend's responsibilities. -->

## 2. Tech Stack
- Language / runtime:
- Framework:
- Database:
- ORM / query builder:
- Auth:
- Caching:
- Background jobs / queues:
- Testing:

## 3. Architecture
<!-- Layering (routes → controllers → services → repositories), monolith vs services, diagram. -->

## 4. Data Model
<!-- Repeat for each entity. -->
### 4.x <Entity Name>
| Field | Type | Constraints | Description |
|-------|------|-------------|-------------|
| id    |      | PK          |             |

### Relationships
- 

### Indexes
- 

## 5. Business Logic / Services
| Service | Responsibility | Key Rules |
|---------|----------------|-----------|
|         |                |           |

## 6. Authentication & Authorization
- Auth mechanism (JWT, session, OAuth):
- Password policy / hashing:
- Roles & permissions:
- Resource ownership rules:

## 7. Validation
- 

## 8. Error Handling
- Error format (see api-contract-spec.md):
- Logging of errors:

## 9. External Integrations
| Service | Purpose | Rate Limits / Notes |
|---------|---------|---------------------|
|         |         |                     |

## 10. Security
- Input sanitization:
- CORS policy:
- Rate limiting:
- Secrets management:

## 11. Logging & Monitoring
- 

## 12. Performance & Scalability
- 

## 13. Testing Strategy
- Unit:
- Integration:
- Contract tests (against api-contract-spec.md):

## 14. Folder Structure
```
backend/
  src/
```

## 15. Environment Variables
| Name | Description | Example |
|------|-------------|---------|
|      |             |         |

## 16. Deployment
- Environments (dev/staging/prod):
- Migrations:
- CI/CD:

## 17. Open Questions
- 
