# A11yTargetWithCache

DEPRECATED: new a11y cache is stored in DB and resolved into the 'cache' field

## Example Usage

```typescript
import { A11yTargetWithCache } from "@momentic/js/models/components";

let value: A11yTargetWithCache = {
  id: 677817,
};
```

## Fields

| Field                                                                                   | Type                                                                                    | Required                                                                                | Description                                                                             |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `id`                                                                                    | *number*                                                                                | :heavy_check_mark:                                                                      | N/A                                                                                     |
| `dataMomenticId`                                                                        | *number*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `selector`                                                                              | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `generatedSelectors`                                                                    | *string*[]                                                                              | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `role`                                                                                  | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `name`                                                                                  | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `numChildren`                                                                           | *number*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `content`                                                                               | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `pathFromRoot`                                                                          | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `serializedForm`                                                                        | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `nodeOnlySerializedForm`                                                                | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `serializedHtml`                                                                        | *string*                                                                                | :heavy_minus_sign:                                                                      | pruned html including 1 neighbor and 1 layer of children. value for text inputs pruned. |
| `nodeOnlySerializedHtml`                                                                | *string*                                                                                | :heavy_minus_sign:                                                                      | outerHtml of the element without any children. value for text inputs pruned.            |
| `screenshotUrl`                                                                         | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `boundingBox`                                                                           | [components.BoundingBox](../../models/components/boundingbox.md)                        | :heavy_minus_sign:                                                                      | css pixel bounding box                                                                  |
| `inputDescription`                                                                      | *string*                                                                                | :heavy_minus_sign:                                                                      | the description that generated this cache                                               |
| `targetSource`                                                                          | [components.TargetSource](../../models/components/targetsource.md)                      | :heavy_minus_sign:                                                                      | N/A                                                                                     |
| `targetUpdateTime`                                                                      | *string*                                                                                | :heavy_minus_sign:                                                                      | N/A                                                                                     |