# `one-variable-per-declaration.md`

Disallows multiple variable definitions in the same declaration statement.

## Rationale

Keeps code consistent and makes merge conflicts less likely.

## Implementation

```json
{
  "rules": {
    "one-variable-per-declaration": [true, "ignore-for-loop"]
  }
}
```

See: https://palantir.github.io/tslint/rules/one-variable-per-declaration/

