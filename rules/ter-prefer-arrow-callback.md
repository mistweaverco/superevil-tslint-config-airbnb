# `ter-prefer-arrow-callback`

require arrow functions as callbacks

## Rationale

Arrow functions are suited to callbacks, because:

- `this` keywords in arrow functions bind to the upper scope’s.
- The notation of the arrow function is shorter than function expression’s.

## Implementation

```json
{
  "rules": {
    "ter-prefer-arrow-callback": [true]
  }
}
```

See: https://github.com/buzinas/tslint-eslint-rules/blob/master/src/docs/rules/terPreferArrowCallbackRule.md

