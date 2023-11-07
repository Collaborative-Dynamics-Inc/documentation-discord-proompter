#### /profile bookmarked-messages list
- List all bookmarked messages

#### /profile bookmarked-messages add
- Bookmark a message
- __**`message-url`**__
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The Discord link to the message
- __**`note`**__
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A note to quickly identify the message when listing them

#### /profile bookmarked-messages remove
- Remove a bookmarked message
- __**`message-url`**__
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The Discord link to the message

#### /profile bookmarked-messages clear
- Remove all bookmarked messages



#### /profile favorite-prompts
> Shows a list of prompts you have reacted to



#### /profile templates set
> Set templates which are used to [download a conversation](proompter-documentation/slash-command/conversation.md####/conversation%20download)
> Learn more about how to create these templates [here](../reference/Conversation%20Export%20Templates)
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
	- **`JSON`**
	- **`Markdown`**
	- **`CSV`**
  - The format you want to set the template for. Right now only one format can be specified for each format
- **`template`**
  - *[Required, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The actual template you want to set, provided as `.txt` file

#### /profile templates show
> Shows the templates you specified, if any

#### /profile templates remove
> Remove a template
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
	- **`JSON`**
	- **`Markdown`**
	- **`CSV`**
  - The format you want to remove the template for



#### /profile raw-profile-data
- Shows all your profile data in JSON



#### /profile gpt-settings-global show
- Shows all GPT the settings you specified

#### /profile gpt-settings-global reset
- Reset a specific GPT setting
- __**`model`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the GPT model
- __**`temperature`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the temperature
- __**`top-p`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the TopP setting
- __**`max-tokens`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the max response tokens settings
- __**`presence-penalty`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the presence penalty settings
- __**`frequency-penalty`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset the frequency penalty settings
- __**`all`**__
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Reset all settings

#### /profile gpt-settings-global set
- Define your GPT settings
- __**`model`**__
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - *Default: gpt-3.5-turbo-16k-0613*
- __**`temperature`**__
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`top-p`**__
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`max-tokens`**__
  - *[Optional, Integer](../reference/Slash%20Commands####Integer)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- __**`presence-penalty`**__
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`frequency-penalty`**__
  - *[Optional, Number](../reference/Slash%20Commands####Number)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*