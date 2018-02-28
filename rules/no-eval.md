# `no-eval`

Disallow use of `eval`.

## Rationale

`eval()` is dangerous as it allows arbitrary code execution with full privileges.
There are alternatives for most of the use cases for `eval()`.


## Implementation

```json
{
  "rules": {
    "no-eval": true
  }
}
```

See: https://palantir.github.io/tslint/rules/no-eval/

