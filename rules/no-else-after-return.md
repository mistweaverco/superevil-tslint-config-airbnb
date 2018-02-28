# `no-else-after-return`

If an `if` block contains a `return` statement,
the `else` block becomes unnecessary.

## Rationale

Avoid unnecessary blocks of code.

## Implementation

```json
{
  "rules": {
    "no-else-after-return": true
  }
}
```

See: https://eslint.org/docs/rules/no-else-return

