#### /conversation download
> Download a conversation into JSON/Markdown format based on [custom templates](<LINK_TO_EXPORT_TEMPLATE>)
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
	- __**``JSON`**__
	- __**``Markdown`**__
- **`template`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - Allows to set a specific [template](<LINK_TO_EXPORT_TEMPLATE>) for the output formatting. Provided as a `.txt` file
- **`after-message-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Export messages up to and including the provided one. Check [this](https://discord.com/channels/1100933695986208849/1149283993548759090) to learn how to get message IDs
- **`before-message-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Export messages older than and including the provided one. Check [this](https://discord.com/channels/1100933695986208849/1149283993548759090) to learn how to get message IDs
- **`max-messages`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Min: 1*
  - *Max: 10000*
  - *Default: 50*
  - The maximum amount of messages to export
- **`filename`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Default: `conversation_<ChannelName>.<format>`*
  - Provide a specific filename to identify conversation more easily. The `.<format>` part will be automatically applied. Placeholders are not supported


---


### Note
- The `before` and `after` messages are included in the export
- The `max-messages` option counts backwards. If provided, `before-message-id` is the first message, else the most recent message will be
- It then gathers as many messages until either `after-message-id` or `max-messages` is reached. For example, by default `max-messages` is `50`
  - When only `before-message-id` is provided, it will start there, and grab an additional 49 messages older than that one
  - When only `after-message-id` is provided, the most recent message is the first. Additional 49 messages before that will be gathered, unless `after-message-id` is reached. In that case it will stop there
  - When both `before-message-id` & `after-message-id` are provided, it will start at the `before` message, and then gather either 49 more messages, or as many until `after` is hit
