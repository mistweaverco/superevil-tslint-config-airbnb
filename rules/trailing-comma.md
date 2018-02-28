# `trailing-comma`

Requires or disallows trailing commas in array and object literals,
destructuring assignments, function typings, named imports and
exports and function parameters.  

**We require trailing commas on multiline-, but disallow them on singleline
statements**

## Rationale

Helps maintain a consistent, readable style in your codebase.

## Implementation

```json
{
  "rules": {
    "trailing-comma": [
      true,
      {
        multiline: "always",
        singleline: "never"
      }
    ]
  }
}
```

See: https://palantir.github.io/tslint/rules/trailing-comma/

