# $hasVar
Check if there is a variable in the database.

### Parameters:
| Name        | Type        | Description                          | Optional |
| ----------- | ----------- | ------------------------------------ | -------- |
| name        | String      | The variable name to check.            | false    |

### Example:
```js
$setVar[Test;Hello]
$hasVar[Test] // true
```

!> You need to setup the database to use this function. Check [tips](tips.md?id=using-database)


