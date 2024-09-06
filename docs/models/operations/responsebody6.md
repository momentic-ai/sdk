# ResponseBody6

## Example Usage

```typescript
import { ResponseBody6 } from "momentic/models/operations";

let value: ResponseBody6 = {
    id: "2e9817ee-17cb-4e61-a6b7-b95bc0ab3c20",
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `thoughts`                                                                                                                     | *string*                                                                                                                       | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `id`                                                                                                                           | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | unique identifier to this step, used for step cache                                                                            |
| `useSelector`                                                                                                                  | *boolean*                                                                                                                      | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `useXY`                                                                                                                        | *boolean*                                                                                                                      | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `force`                                                                                                                        | *boolean*                                                                                                                      | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `disableCache`                                                                                                                 | *boolean*                                                                                                                      | :heavy_minus_sign:                                                                                                             | disable element caching for this step                                                                                          |
| `iframeUrl`                                                                                                                    | *string*                                                                                                                       | :heavy_minus_sign:                                                                                                             | url or url regex for the iframe                                                                                                |
| `cache`                                                                                                                        | [operations.GetNextCommandResponseBodyResponse200Cache](../../models/operations/getnextcommandresponsebodyresponse200cache.md) | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `target`                                                                                                                       | *operations.GetNextCommandResponseBodyResponse200Target*                                                                       | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |
| `type`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `deltaY`                                                                                                                       | *number*                                                                                                                       | :heavy_minus_sign:                                                                                                             | N/A                                                                                                                            |