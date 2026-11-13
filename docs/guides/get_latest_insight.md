---
page_title: "get_latest_insight"
description: |-
  Get Latest Insight
---

# get_latest_insight

See the [`scalegrid_operation` resource documentation](../resources/operation#get_latest_insight) for the full reference.

**HTTP:** `GET /scalegridserviceclusters/{scalegridServiceClusterUid}/insights/latest`

## Terraform Example

```terraform
resource "scalegrid_operation" "example" {
  operation_id = "get_latest_insight"
  path_params = {
    scalegridServiceClusterUid = "00000000-0000-0000-0000-000000000001"
  }
}
```
