# TASK (TASK TITLE)

## Objective

[Clearly describe the goal]

---

## Scope (optional)

Work ONLY on:

- [file/path.ts]
- [file/path.ts]

If not provided, infer the minimal required scope.

---

## Context (optional)

[Only essential information for this task]

---

## API Integration (optional)

If this task involves an external API, provide:

### API Reference

- Endpoint(s): [e.g. POST /orders]
- Base URL: [e.g. https://api.example.com]
- Method(s): [GET, POST, etc.]

### Request Details

- Headers: [Authorization, Content-Type, etc.]
- Params / Query: [if applicable]
- Body schema:

  {
  "field": "type"
  }

### Response Example

    {
      "id": "string",
      "status": "string"
    }

### Auth

- Type: [Bearer token, API key, OAuth, etc.]
- How to obtain/use token

### Rules / Constraints

- rate limits
- idempotency requirements
- required headers
- error handling patterns

### Notes (optional)

- edge cases
- known quirks from provider
- links to docs (if needed)

---

## Constraints

- do not modify unrelated code
- do not change architecture without clear need
- ask if any requirement is unclear

---

## Acceptance Criteria (optional)

- [expected outcome]
- [expected behavior]
