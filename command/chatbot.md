#### /chatbot create
> Create a new chatbot
> Either `version-uuid`, `prompt-id`, `prompt-file` or `prompt` needs to be passed
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name of the chatbot
- **`allowed-channels`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of channels where the chatbot can be used, separated by semicolon
- **`version-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the prompt version this chatbot uses as system prompt
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- **`prompt-file`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The textfile this chatbot uses as system prompt
- **`prompt`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The system prompt for this chatbot
- **`model`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Default: gpt-3.5-turbo-16k-0613*
- **`temperature`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`top-p`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`presence-penalty`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`frequency-penalty`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`max-tokens`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this bot can only be used by it's creator
- **`balance`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Default: 10*
  - How much balance this bot starts with
- **`existing-role`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the system will try to find a role with the chatbot name instead of creating a new one
- **`disable-automention`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, this chatbot will not be able to mention other chatbots

#### /chatbot inspect
> Get details about a chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- **`chatbot-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the chatbot

#### /chatbot list
> List all chatbots

#### /chatbot delete
> Delete a chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- **`chatbot-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the chatbot

#### /chatbot manage
> Manage a existing chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- **`chatbot-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the chatbot
- **`balance`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - Set the balance of this chatbot
- **`name`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name of the chatbot
- **`allowed-channels`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of channels where the chatbot can be used, separated by semicolon
- **`version-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the prompt version this chatbot uses as system prompt
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- **`prompt-file`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The textfile this chatbot uses as system prompt
- **`prompt`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The system prompt for this chatbot
- **`model`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Default: gpt-3.5-turbo-16k-0613*
- **`temperature`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`top-p`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`presence-penalty`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`frequency-penalty`**
  - *[Optional, Number](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`max-tokens`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this bot can only be used by it's creator
- **`disable-automention`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, this chatbot will not be able to mention other chatbots
- **`is-active`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, this chatbot will be set to inactive, which means he cannot be called anymore (role gets deleted)

#### /chatbot download-settings
> Allows to download the settings of all/a specific chatbot in a .csv file
- **`chatbot-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - If not set, settings of all chatbots will be downloaded

#### /chatbot import-settings
> Import chatbot settings from a .csv file
- **`csv-file`**
  - *[Required, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - A .csv file containing the chatbot settings

#### /chatbot update-library-post
> Update the library post of a specific chatbot
> When this command is executed in a chatbot library post, it will automatically take said chatbot, in that case `chatbot-role` and `chatbot-uuid` don't need to be provided. But, if you're outside of the chatbot library, either option is necessary
- **`chatbot-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the chatbot
