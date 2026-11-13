---
page_title: "get_primary_instance"
description: |-
  Get Primary Instance
---

# get_primary_instance

See the [`scalegrid_operation` resource documentation](../resources/operation#get_primary_instance) for the full reference.

**HTTP:** `GET /scalegridserviceclusters/{scalegridServiceClusterUid}/primary`

## Terraform Example

```terraform
resource "scalegrid_operation" "example" {
  operation_id = "get_primary_instance"
  path_params = {
    scalegridServiceClusterUid = "00000000-0000-0000-0000-000000000001"
  }
}
```
