[wdio-wait-for](../README.md) / [Modules](../modules.md) / element/elementToBeClickable

# Module: element/elementToBeClickable

## Table of contents

### Functions

- [elementToBeClickable](element_elementtobeclickable.md#elementtobeclickable)

## Functions

### elementToBeClickable

▸ **elementToBeClickable**(`selectorOrElement`: *string* \| *Promise*<WebdriverIO.Element\>): *function*

A condition for checking an element is visible and clickable

**`example`** 
browser.waitUntil(elementToBeClickable('.links'));

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `selectorOrElement` | *string* \| *Promise*<WebdriverIO.Element\> | The selector or element to check |

**Returns:** () => *Promise*<boolean\>

An expected condition that returns a promise
    representing whether the element is clickable.

Defined in: [element/elementToBeClickable.ts:13](https://github.com/elaichenkov/wdio-wait-for/blob/074de0f/src/element/elementToBeClickable.ts#L13)
