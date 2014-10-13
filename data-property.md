# Collection+JSON Extensions

## 1.0 Additional `data` property

In addition to the properties outlined in section 4.2, the `data` array MAY contain the `type` property.

## 2.0 Properties

### 2.1 `type`

The `type` property MAY be a child element of `data` array elements.

It SHOULD be a `STRING` type and describe the type `value` is. Examples include "date" and "timestamp".
