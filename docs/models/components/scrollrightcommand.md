# ScrollRightCommand

## Example Usage

```typescript
import { ScrollRightCommand } from "@momentic/js/models/components";

let value: ScrollRightCommand = {
  id: "a9de2460-1374-4e5e-9f73-4c4679f35451",
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `thoughts`                                                                   | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `id`                                                                         | *string*                                                                     | :heavy_check_mark:                                                           | unique identifier to this step, used for step cache                          |
| `useSelector`                                                                | *boolean*                                                                    | :heavy_minus_sign:                                                           | N/A                                                                          |
| `useXY`                                                                      | *boolean*                                                                    | :heavy_minus_sign:                                                           | N/A                                                                          |
| `force`                                                                      | *boolean*                                                                    | :heavy_minus_sign:                                                           | N/A                                                                          |
| `disableCache`                                                               | *boolean*                                                                    | :heavy_minus_sign:                                                           | disable element caching for this step                                        |
| `iframeUrl`                                                                  | *string*                                                                     | :heavy_minus_sign:                                                           | url or url regex for the iframe                                              |
| `cache`                                                                      | [components.SingleTargetCache](../../models/components/singletargetcache.md) | :heavy_minus_sign:                                                           | N/A                                                                          |
| `target`                                                                     | *components.ElementTarget*                                                   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `type`                                                                       | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `deltaX`                                                                     | *number*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |