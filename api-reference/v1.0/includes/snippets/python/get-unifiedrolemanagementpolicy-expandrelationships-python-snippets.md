---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = UnifiedRoleManagementPolicyRequestBuilder.UnifiedRoleManagementPolicyRequestBuilderGetQueryParameters(
		expand = ["effectiveRules","rules"],
)

request_configuration = UnifiedRoleManagementPolicyRequestBuilder.UnifiedRoleManagementPolicyRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.policies.role_management_policies.by_role_management_policie_id('unifiedRoleManagementPolicy-id').get(request_configuration = request_configuration)


```