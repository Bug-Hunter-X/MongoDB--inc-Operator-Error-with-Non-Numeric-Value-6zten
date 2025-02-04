# MongoDB $inc Operator Error
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment numeric fields, and attempting to use it on a non-numeric field will result in an error.

## Bug
The provided code attempts to increment the `field` in a document where the `field` is a string rather than a number.

## Solution
The solution shows the correct way to use the $inc operator, ensuring that the field to be incremented is a number.