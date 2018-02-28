# `ter-arrow-parens`

Discourage the use of parens (in arrow functions) when they are not required.

## Rationale

Arrow functions can omit parentheses when they have exactly one parameter.
In all other cases the parameter(s) must be wrapped in parentheses.
This rule enforces the consistent use of parentheses in arrow functions.

## Implementation

```json
{
  "rules": {
    "ter-arrow-parens": [
      true,
      "as-needed",
      { "requireForBlockBody": true }
    ]
  }
}
```

See: https://github.com/buzinas/tslint-eslint-rules/blob/master/src/docs/rules/terArrowParensRule.md

