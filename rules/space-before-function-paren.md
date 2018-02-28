# `space-before-function-paren`

Require or disallow a space before function parenthesis.

## Rationale

Enforce consistent code. Make merge conflicts less likely.

## Implementation

```json
{
  "rules": {
    "space-before-function-paren": [
      true,
      {
        "anonymous": "always",
        "named": "never"
      }
    ]
  }
}
```

See: https://palantir.github.io/tslint/rules/space-before-function-paren/

