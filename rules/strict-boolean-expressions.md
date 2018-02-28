# `strict-boolean-expressions`

Restrict the types allowed in boolean expressions.
By default only booleans are allowed.

## Rationale

Code consistency and maintainability.

## Implementation

```json
{
  "rules": {
    "strict-boolean-expressions": [
      true,
      "allow-null-union",
      "allow-undefined-union",
      "allow-string",
      "allow-mix"
    ]
  }
}
```

See: https://palantir.github.io/tslint/rules/strict-boolean-expressions/

