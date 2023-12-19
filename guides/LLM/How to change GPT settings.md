# How to change the GPT settings (Model, Temperatur, TopP etc.)
> You can use the [/profile gpt-settings-global](../../slash-command/profile####/profile%20gpt-settings-global%20set) commands to manage the model, temperature etc.


## Usage
- Use the **/profile gpt-settings-global set** command and pass all [options](../Quickstart/Slash%20Commands##Command%20Option%20Types) you want to change

### Example
```
/profile gpt-settings-global set model:gpt-4-0314 temperature:1.2 top-p:0.3
```
> This will change the model to the march snapshot of `gpt-4`, temperature to `1.2` & the TopP setting to `0.3`


## Limitations
> Due to the current infrastructure we have to limit custom model settings to [private conversations](../../reference/Conversation)
> If you interact with the chatbots in a [public conversations](../../reference/Conversation), the default model (`gpt-3.5-turbo-16k`) is used


> **Note:** Currently it's only possible to change your global settings. That means, they apply to all chatbots. You cannot change your preferences for specific bots/conversations