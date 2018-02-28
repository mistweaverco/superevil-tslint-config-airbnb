# `no-this-assignment`

Disallow unnecessary references to `this`.

## Rationale

Assigning a variable to `this` instead of properly using arrow lambdas
may be a symptom of pre-ES6 practices or not manging scope well.

## Implementation

```json
{
  "rules": {
    "no-this-assignment": true
  }
}
```

See: https://palantir.github.io/tslint/rules/no-this-assignment/

