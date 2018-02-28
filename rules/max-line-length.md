# `max-line-length`

Require lines to be under a certain max length.

**We use a max length of 100 characters.**

## Rationale

Limiting the length of a line of code improves code readability.
It also makes comparing code side-by-side easier and
improves compatibility with various editors,
IDEs, and diff viewers.

## Implementation

```json
{
  "rules": {
    "max-line-length": [true, 100]
  }
}
```

See: https://palantir.github.io/tslint/rules/max-line-length/

