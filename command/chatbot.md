#### /chatbot create
> Create a new chatbot
> Either `version-uuid`, `prompt-id`, `prompt-file` or `prompt` needs to be passed
- **`name`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The name of the chatbot
- **`allowed-channels`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - A list of channels where the chatbot can be used, separated by semicolon
- **`version-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The UUID of the prompt version this chatbot uses as system prompt
- **`prompt-id`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- **`prompt-file`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - The textfile this chatbot uses as system prompt
- **`prompt`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The system prompt for this chatbot
- **`model`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - *Default: gpt-3.5-turbo-16k-0613*
- **`temperature`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`top-p`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`presence-penalty`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`frequency-penalty`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`max-tokens`**
  - *[Optional, Integer](../reference/Slash%20Commands####Integer)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- **`is-public`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If false, this bot can only be used by it's creator
- **`balance`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Default: 10*
  - How much balance this bot starts with
- **`existing-role`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, the system will try to find a role with the chatbot name instead of creating a new one
- **`disable-automention`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, this chatbot will not be able to mention other chatbots

#### /chatbot inspect
> Get details about a chatbot
- **`chatbot-role`**
  - *[Optional, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The UUID of the chatbot
> Either `chatbot-role` or `chatbot-uuid` needs to be passsed

#### /chatbot list
> List all chatbots

#### /chatbot delete
> Delete a chatbot
- **`chatbot-role`**
  - *[Optional, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot
- **`chatbot-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The UUID of the chatbot
> Either `chatbot-role` or `chatbot-uuid` needs to be passsed

#### /chatbot manage
> Manage a existing chatbot
- **`chatbot-role`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot you want to edit
- **`balance`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - Set the balance of this chatbot
- **`name`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The name of the chatbot
- **`allowed-channels`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - A list of channels where the chatbot can be used, separated by semicolon
- **`version-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The UUID of the prompt version this chatbot uses as system prompt
- **`prompt-id`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The ID of the prompt this chatbot uses as system prompt. Always takes the latest version
- **`prompt-file`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - The textfile this chatbot uses as system prompt
- **`prompt`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The system prompt for this chatbot
- **`model`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - *Default: gpt-3.5-turbo-16k-0613*
- **`temperature`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`top-p`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- **`presence-penalty`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`frequency-penalty`**
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- **`max-tokens`**
  - *[Optional, Integer](../reference/Slash%20Commands####Integer)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- **`is-public`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If false, this bot can only be used by it's creator
- **`disable-automention`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, this chatbot will not be able to mention other chatbots

#### /chatbot download-settings
> Allows to download the settings of all/a specific chatbot in a .csv file
- **`chatbot-role`**
  - *[Optional, Role](../reference/Slash%20Commands####Role)*
  - If not set, settings of all chatbots will be downloaded

#### /chatbot import-settings
> Import chatbot settings from a .csv file
- **`csv-file`**
  - *[Required, Attachment](../reference/Slash%20Commands####Attachment)*
  - A .csv file containing the chatbot settings
