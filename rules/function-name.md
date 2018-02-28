# `function-name`

Enforce consistent naming for function, method, private, protected and static.

## Rationale

Helps maintain a consistent, readable style in your codebase.

## Implementation

```json
{
  "rules": {
    "function-name": [
      true,
      {
        "function-regex": /^[a-z$][\w\d]+$/,
        "method-regex": /^[a-z$][\w\d]+$/,
        "private-method-regex": /^[a-z$][\w\d]+$/,
        "protected-method-regex": /^[a-z$][\w\d]+$/,
        "static-method-regex": /^[a-z$][\w\d]+$/
      }
    ]
  }
}
```

See: https://github.com/Microsoft/tslint-microsoft-contrib

