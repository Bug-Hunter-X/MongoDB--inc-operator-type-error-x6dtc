# MongoDB $inc operator type error
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment a numeric field, but if a string value is provided, it will not work as expected and may throw an error.

**Bug:** Using `$inc` with a string value.

**Solution:** Ensure that the value used with `$inc` is a number.