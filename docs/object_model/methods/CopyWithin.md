---
title: CopyWithin
parent: Methods
---

# CopyWithin
### Inspiration
* http://www.ecma-international.org/ecma-262/10.0/index.html#sec-array.prototype.copywithin
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin

### Description
The `CopyWithin()` method shallow copies part of an array to another location in the same array and returns it without modifying its length. The copyWithin method takes up to three arguments target, start and end.

### Note
*The end argument is optional with the length of the this object as its default value. If target is negative, it is treated as length + target where length is the length of the array. If start is negative, it is treated as length + start. If end is negative, it is treated as length + end.*

### Arguments
#### `Target` (Long)
The index at which to copy the sequence to. If negative, `Target` will be counted from the end.
If `Target` is at or greater than the array's `Length` property, nothing will be copied. If `Target` is positioned after `StartIndex`, the copied sequence will be trimmed to fit the array's `Length` property.
#### *Optional* `StartIndex` (Long)
The index at which to start copying elements from. If negative, `StartIndex` will be counted from the end.
If `StartIndex` is omitted, `CopyWithin` will copy from the LowerBound index of the array. 
#### *Optional* `EndIndex` (Long)
The index at which to end copying elements from. `CopyWithin` copies up to but not including `EndIndex`. If negative, `EndIndex` will be counted from the end.
If `EndIndex` is omitted, `CopyWithin` will copy until the last index (default to the array's `Length` property).
### Returns
#### (Variant)
The modified array.

# [Back to Docs](https://senipah.github.io/VBA-Better-Array/)