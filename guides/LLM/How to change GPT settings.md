# How to change the GPT settings (Model, Temperatur, TopP etc.)
> You can use the [/profile gpt-settings-global](<https://discord.com/channels/1100933695986208849/1153688751260840108>) commands to manage the model, temperature etc.


## Usage
- Use the **</profile gpt-settings-global set:1153117013506543626>** command and pass all [options](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278821565079614>) you want to change

**Example**
```
/profile gpt-settings-global set model:gpt-4-0314 temperature:1.2 top-p:0.3
```
> This will change the model to the march snapshot of `gpt-4`, temperature to `1.2` & the TopP setting to `0.3`


## Limitations
There are certain limitations about how settings are applied
- [Public conversations](<https://discord.com/channels/1100933695986208849/1168754593434439700>)
> Settings are not applied at all
- [Private conversations](<https://discord.com/channels/1100933695986208849/1168754593434439700>)
> If you are an admin of the conversation, the settings will be applied, otherwise not



> **Note:** Currently it's only possible to change your global settings. That means, they apply to all chatbots. You cannot change your preferences for specific bots/conversations