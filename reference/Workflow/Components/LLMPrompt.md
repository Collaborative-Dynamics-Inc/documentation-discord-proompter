# LLMPrompt
```
{
  "type": 3,
  "id": "systemPrompt",
  "inputs": {
    "promptId": "3919eddc-626b-48f5-9811-a01f80d96ebe"
  }
}
```

> - **type**: [`LLMPrompt`](Workflow%20Schema.md###type)
> - **id**: The ID of this component
> - **inputs**: *Either one of the following options need to be passed*
> 	- **promptId**: The ID of the prompt to fetch (returns the latest version)
> 	- **versionUUID**: The UUID of the specific prompt version to fetch
> 	- **prompt**: The prompt to provide
