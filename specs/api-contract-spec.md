# API Contract Spec — Trip Planner

> Status: Draft | Owner: <name> | Last updated: <YYYY-MM-DD>
> This document is the source of truth between frontend and backend.

## 1. General Conventions
- Base URL: `/api/v1`
- Protocol / format: REST + JSON
- Authentication: <!-- e.g. `Authorization: Bearer <token>` -->
- Naming convention (camelCase / snake_case):
- Date/time format: <!-- e.g. ISO 8601 UTC -->
- Pagination: <!-- e.g. `?page=1&limit=20` -->
- Filtering / sorting:
- Versioning strategy:

## 2. Standard Response Shapes
### Success
```json
{
  "data": {}
}
```

### Error
```json
{
  "error": {
    "code": "STRING_CODE",
    "message": "Human readable message",
    "details": []
  }
}
```

### Status Codes
| Code | Meaning | When Used |
|------|---------|-----------|
| 200  | OK      |           |
| 201  | Created |           |
| 400  | Bad Request |       |
| 401  | Unauthorized |      |
| 403  | Forbidden |         |
| 404  | Not Found |         |
| 409  | Conflict |          |
| 422  | Validation Error |  |
| 500  | Server Error |      |

## 3. Shared Types / Schemas
<!-- Define reusable objects referenced by endpoints. -->
### <TypeName>
```json
{
}
```

## 4. Endpoint Summary
| Method | Path | Auth | Description |
|--------|------|------|-------------|
|        |      |      |             |

## 5. Endpoint Details
<!-- Repeat this block for each endpoint. -->
### `METHOD /path`
- **Description:**
- **Auth required:** Yes / No
- **Path params:**
- **Query params:**

**Request body**
```json
{
}
```

**Response `200`**
```json
{
}
```

**Errors**
| Status | Code | When |
|--------|------|------|
|        |      |      |

---

## 6. Changelog
| Date | Change | Author |
|------|--------|--------|
|      |        |        |
