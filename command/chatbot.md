</chatbot create:1134802420359250051>
> Create a new chatbot
> Either `version-uuid`, `prompt-id`, `prompt-file` or `prompt` needs to be passed
- __**`name`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The name of the chatbot
- __**`allowed-channels`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of channels where the chatbot can be used, separated by semicolon
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the prompt version this chatbot uses as system prompt
- __**`prompt-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- __**`prompt-file`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The textfile this chatbot uses as system prompt
- __**`prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The system prompt for this chatbot
- __**`model`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: gpt-3.5-turbo-16k-0613*
- __**`temperature`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`top-p`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*


- __**`presence-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`frequency-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`max-tokens`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this bot can only be used by it's creator
- __**`balance`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: 10*
  - How much balance this bot starts with
- __**`existing-role`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, the system will try to find a role with the chatbot name instead of creating a new one
- __**`disable-automention`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, this chatbot will not be able to mention other chatbots


_ _
</chatbot inspect:1134802420359250051>
> Get details about a chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- __**`chatbot-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot
- __**`chatbot-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the chatbot

</chatbot list:1134802420359250051>
> List all chatbots

</chatbot delete:1134802420359250051>
> Delete a chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- __**`chatbot-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot
- __**`chatbot-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the chatbot


_ _
</chatbot manage:1134802420359250051>
> Manage a existing chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- __**`chatbot-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot
- __**`chatbot-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the chatbot
- __**`balance`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set the balance of this chatbot
- __**`name`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The name of the chatbot
- __**`allowed-channels`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of channels where the chatbot can be used, separated by semicolon
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the prompt version this chatbot uses as system prompt
- __**`prompt-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- __**`prompt-file`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The textfile this chatbot uses as system prompt

- __**`prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The system prompt for this chatbot
- __**`model`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: gpt-3.5-turbo-16k-0613*
- __**`temperature`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`top-p`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`presence-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`frequency-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`max-tokens`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses


- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this bot can only be used by it's creator
- __**`disable-automention`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, this chatbot will not be able to mention other chatbots
- __**`is-active`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, this chatbot will be set to inactive, which means he cannot be called anymore (role gets deleted)


_ _
</chatbot download-settings:1134802420359250051>
> Allows to download the settings of all/a specific chatbot in a .csv file
- __**`chatbot-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If not set, settings of all chatbots will be downloaded

</chatbot import-settings:1134802420359250051>
> Import chatbot settings from a .csv file
- __**`csv-file`**__
  - *[Required, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A .csv file containing the chatbot settings

</chatbot update-library-post:1134802420359250051>
> Update the library post of a specific chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- __**`chatbot-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot
- __**`chatbot-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the chatbot
