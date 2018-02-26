# `no-trailing-whitespace`

Disallow trailing whitespace at the end of a line.

## Rationale

Keeps version control diffs clean
as it prevents accidental whitespace from being committed.

## Implementation

```json
{
  "rules": {
    "no-trailing-whitespace": [true, "ignore-template-strings"],
  }
}
```

See: https://palantir.github.io/tslint/rules/no-trailing-whitespace/

