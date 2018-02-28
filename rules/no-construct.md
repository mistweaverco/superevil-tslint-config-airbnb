# `no-construct`

Disallow access to the constructors of `String`, `Number`, and `Boolean`.

Disallows constructor use such as `new Number(foo)`,
but does not disallow `Number(foo)`.

## Rationale

There is little reason to use `String`, `Number`, or `Boolean` as constructors.
In almost all cases, the regular function-call version is more appropriate.

[More details](http://stackoverflow.com/q/4719320/3124288) are available
on StackOverflow.

## Implementation

```json
{
  "rules": {
    "no-construct": true
  }
}
```

See: https://palantir.github.io/tslint/rules/no-construct/

