[wdio-wait-for](../README.md) / [Modules](../modules.md) / element/numberOfElementsToBeLessThan

# Module: element/numberOfElementsToBeLessThan

## Table of contents

### Functions

- [numberOfElementsToBeLessThan](element_numberofelementstobelessthan.md#numberofelementstobelessthan)

## Functions

### numberOfElementsToBeLessThan

▸ **numberOfElementsToBeLessThan**(`selectorOrElementArray`: *string* \| *Promise*<WebdriverIO.ElementArray\>, `expectedNumber`: *number*): *function*

A condition for checking number of elements with given selector being less than defined number

**`example`** 
browser.waitUntil(numberOfElementsToBeLessThan('a', 2));

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `selectorOrElementArray` | *string* \| *Promise*<WebdriverIO.ElementArray\> | The selector or elements array to check |
| `expectedNumber` | *number* | The selector to check |

**Returns:** () => *Promise*<boolean\>

An expected condition that returns a promise
    representing whether the element length is less than defined number.

Defined in: [element/numberOfElementsToBeLessThan.ts:14](https://github.com/elaichenkov/wdio-wait-for/blob/074de0f/src/element/numberOfElementsToBeLessThan.ts#L14)
