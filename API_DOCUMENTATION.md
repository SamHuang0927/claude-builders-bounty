# API Documentation

## Overview
API documentation for feat(bounty-4): claude-review — CLI PR reviewer via Claude API [$150]

## Endpoints

### GET /api/resource
**Description**: Retrieve resource information

**Parameters**:
- `id` (required): Resource identifier
- `format` (optional): Response format (json/xml)

**Response**:
```json
{
  "id": "string",
  "name": "string",
  "status": "active"
}
```

### POST /api/resource
**Description**: Create new resource

**Request Body**:
```json
{
  "name": "string",
  "type": "string"
}
```

## Error Codes
- 400: Bad Request
- 404: Resource Not Found
- 500: Internal Server Error
