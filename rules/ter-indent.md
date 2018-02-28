# `ter-indent`

Enforce consistent indentation.

## Rationale

Using only one of tabs or spaces for indentation leads to
more consistent editor behavior,
cleaner diffs in version control,
and easier programmatic manipulation.

## Implementation

```json
{
  "rules": {
    'ter-indent': [
      true,
      2,
      { "SwitchCase": 1 }
    ]
  }
}
```

See: https://github.com/buzinas/tslint-eslint-rules/blob/master/src/docs/rules/terIndentRule.md

