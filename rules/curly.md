# `curly`

Enforce braces for `if/for/do/while` statements.

## Rationale

```javascript
if (foo === bar)
    foo++;
    bar++;
```

In the code above,
the author almost certainly meant for both
`foo++` and `bar++` to be executed only if `foo === bar`.

However, he forgot braces and `bar++` will be executed no matter what.
This rule could prevent such a mistake.

## Implementation

```json
{
  "rules": {
    "curly": [true, "ignore-same-line"]
  }
}
```

See: https://palantir.github.io/tslint/rules/curly/

