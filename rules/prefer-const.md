# `prefer-const`

Require that variable declarations use `const` instead of `let` and `var` if possible.

## Rationale

If a variable is only assigned to once when it is declared,
it should be declared using ‘const’

## Implementation

```json
{
  "rules": {
    "prefer-const": true
  }
}
```

See: https://palantir.github.io/tslint/rules/prefer-const/

