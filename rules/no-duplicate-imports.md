# `no-duplicate-imports`

Disallow multiple import statements from the same module.

## Rationale

Using a single import statement per module will make the code clearer
because you can see everything being imported from that module on one line.

## Implementation

```json
{
  "rules": {
    "no-duplicate-imports": true
  }
}
```

See: https://palantir.github.io/tslint/rules/no-duplicate-imports/

