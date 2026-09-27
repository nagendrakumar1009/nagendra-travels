# API Contract Spec

## 1. General Conventions
- Base URL:
- Versioning:
- Content type:
- Auth header:
- Date/time format:
- Pagination:

## 2. Standard Error Format
```json
{
  "error": { "code": "", "message": "", "details": [] }
}
```

## 3. Endpoints

### <METHOD> <path>
- **Description:**
- **Auth required:**
- **Path params:**
- **Query params:**
- **Request body:**
```json
{}
```
- **Success response (status):**
```json
{}
```
- **Error responses:**
| Status | Code | When |
|--------|------|------|
| | | |

<!-- Repeat the endpoint block for each endpoint. Group by resource: Auth, Users, Trips, Itinerary, etc. -->

## 4. Shared Schemas / Types
<!-- Reusable object definitions used across endpoints. -->

## 5. Status Code Summary
<!-- Which codes are used and what they mean. -->

## 6. Rate Limits & Constraints
