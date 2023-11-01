# Workflow Schema
```
{
  "executionType": "1",
  "entryPoint": "gptTranslate",
  "components": [
    {
      "type": 3,
      "id": "systemPrompt",
      "inputs": {
        "promptId": "3919eddc-636b-48e5-9811-a01f80d96ebe"
      }
    },
    {
      "type": 1,
      "id": "gptTranslate",
      "inputs": {
        "model": "gpt-3.5-turbo-16k-0613",
        "userMessage": "Tell me a cool joke"
      },
      "callElementWithId": "presentResponse",
      "dependsOnElementsWithId": [
        "systemPrompt"
      ]
    },
    {
      "type": 2,
      "id": "presentResponse",
      "content": "# Joke\n\n>>> {{response}}"
    }
  ]
}
```

## Root Settings
> **executionType**:
> 	`0`: Workflow that gets triggered, for example by pressing a button
> 	`1`: Workflow that gets executed manually by a user ([/workflow execute]())
> **entryPoint**: The ID of the component that will be the trigger/executed first
> **components**: The list of components


---

## Components
### type
> 	`0`: [DiscordCommandInteractionCreate](./Components/DiscordCommandInteractionCreate) triggers when a Discord command is executed
> 	`1`: [OpenAIGPT](./Components/OpenAIGPT) Call GPT
> 	`2`: [DiscordCommandInteractionFollowUp](./Components/DiscordCommandInteractionFollowUp) follow up with a response to a command interaction
> 	`3`: [LLMPrompt](./Components/LLMPrompt) provide a prompt for a LLM, either by passing it directly, or by fetching it from Proompter by using it's prompt ID/version UUID


---

## Variables & Placeholders
> Outputs get passed to all following components, where they can be used in inputs or responses of components. They can be used like this `{{response}}`, which in the above example gets replaced with the response of the `OpenAIGPT` component (better names and a list of outputs follows).