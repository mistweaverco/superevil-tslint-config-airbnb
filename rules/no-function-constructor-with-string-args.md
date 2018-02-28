# `no-function-constructor-with-string-args`

Do not use the version of the `Function` constructor
that accepts a string argument to define the body of the function	

## Rationale

Who in his/her right mind, would do such a thing?
We have to make sure nobody does such evil things!

## Implementation

```json
{
  "rules": {
    "no-function-constructor-with-string-args": true
  }
}
```

See: https://github.com/Microsoft/tslint-microsoft-contrib

