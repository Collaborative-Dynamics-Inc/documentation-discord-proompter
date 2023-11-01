# OpenAIGPT
```
{
  "type": 1,
  "id": "gptTranslate",
  "inputs": {
    "model": "gpt-3.5-turbo-16k-0613",
    "userMessage": "Please translate the following message into {{target_lang}}. Elide pre- and post- text providing the translation only:"
  },
  "callElementWithId": "presentResponse",
  "dependsOnElementsWithId": [
    "systemPrompt"
  ]
}
```

> - **type**: [`OpenAIGPT`](Workflow%20Schema.md###type)
> - **id**: The ID of this component
> - **inputs**:
> 	- **model**: The specific GPT model to use
> 	- **userMessage**: The message that gets added after the system prompt
> 	- **maxTokens**: Maximum amount of response tokens
> 	- **temperature**: The temperatur of this GPT request (0-2)
> - **callElementWithId**: The ID of the component to execute after this one
> - **dependsOnElementsWithId**: *(Optional)* The ID of the components to execute before this one
