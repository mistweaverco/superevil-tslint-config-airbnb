# `radix`

Require the radix parameter to be specified when calling `parseInt`.

## Rationale

From [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt):

> Always specify this parameter to eliminate reader confusion and
> to guarantee predictable behavior.
> Different implementations produce different results when a
> radix is not specified, usually defaulting the value to 10.

## Implementation

```json
{
  "rules": {
    "radix": true
  }
}
```

See: https://palantir.github.io/tslint/rules/radix/

