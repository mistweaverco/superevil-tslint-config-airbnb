# `no-var-keyword`

Disallows usage of the `var` keyword.

## Rationale

Use `let` or `const` instead, because they are more suitable and are block scoped.

## Implementation

```json
{
  "rules": {
    "no-var-keyword": true
  }
}
```

See: https://palantir.github.io/tslint/rules/no-var-keyword/

