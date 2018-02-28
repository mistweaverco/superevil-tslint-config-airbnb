# `object-literal-sort-keys`

Checks ordering of keys in object literals.

## Rationale

Useful in preventing merge conflicts.

## Implementation

```json
{
  "rules": {
    "object-literal-sort-keys": [
      true,
      "ignore-case",
      "match-declaration-order",
      "shorthand-first"
    ]
  }
}
```

See: https://palantir.github.io/tslint/rules/object-literal-sort-keys/

