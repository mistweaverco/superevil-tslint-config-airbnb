# `triple-equals`

Require `===` and `!==` in place of `==` and `!=`.

## Rationale

Enforces code consistency and avoids merge conflicts.

## Implementation

```json
{
  "rules": {
    "triple-equals": [true, "allow-null-check"]
  }
}
```

See: https://palantir.github.io/tslint/rules/triple-equals/

