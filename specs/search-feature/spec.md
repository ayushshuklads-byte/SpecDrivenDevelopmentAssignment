# Specification

## Functional Requirements

- Add optional `search` query parameter to `/reports`
- Perform case-insensitive partial matching on report titles
- Preserve existing sorting and pagination behavior

## Edge Cases

- Empty search string should behave as no filter
- No matching results should return empty list
- Search should support mixed case input