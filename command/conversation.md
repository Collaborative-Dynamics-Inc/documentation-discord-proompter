<<<<<<< Updated upstream
#### /conversation download
> Download a conversation into JSON/Markdown format based on [custom templates](<LINK_TO_EXPORT_TEMPLATE>)
> More details about how to use the different options are available [here](<LINK_TO_EXPORT_OPTIONS>)
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
=======
</conversation download:1163814409974591498>
> Download a conversation into JSON/Markdown format based on [custom templates](<https://discord.com/channels/1100933695986208849/1164336383679275088>)
- __**`format`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
>>>>>>> Stashed changes
  - *Available Options:*
	- __**``JSON`**__
	- __**``Markdown`**__
- __**`template`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Allows to set a specific [template](<https://discord.com/channels/1100933695986208849/1164336383679275088>) for the output formatting. Provided as a `.txt` file
- __**`after-message-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Export messages up to and including the provided one. Check [this](https://discord.com/channels/1100933695986208849/1149283993548759090) to learn how to get message IDs
- __**`before-message-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Export messages older than and including the provided one. Check [this](https://discord.com/channels/1100933695986208849/1149283993548759090) to learn how to get message IDs
- __**`max-messages`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 1*
  - *Max: 10000*
  - *Default: 50*
  - The maximum amount of messages to export
- __**`filename`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: `conversation_<ChannelName>.<format>`
  - Provide a specific filename to identify conversation more easily. The `.<format>` part will be automatically applied. Placeholders are not supported
<<<<<<< Updated upstream
=======


_ _
**Note:**
- The `before` and `after` messages are included in the export
- The `max-messages` option counts backwards. If provided, `before-message-id` is the first message, else the most recent message will be
- It then gathers as many messages until either `after-message-id` or `max-messages` is reached. For example, by default `max-messages` is `50`
  - When only `before-message-id` is provided, it will start there, and grab an additional 49 messages older than that one
  - When only `after-message-id` is provided, the most recent message is the first. Additional 49 messages before that will be gathered, unless `after-message-id` is reached. In that case it will stop there
  - When both `before-message-id` & `after-message-id` are provided, it will start at the `before` message, and then gather either 49 more messages, or as many until `after` is hit
>>>>>>> Stashed changes
