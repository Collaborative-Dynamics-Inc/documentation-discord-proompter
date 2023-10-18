#### /conversation download
> Download a conversation into JSON/Markdown format based on [custom templates](<LINK_TO_EXPORT_TEMPLATE>)
> More details about how to use the different options are available [here](<LINK_TO_EXPORT_OPTIONS>)
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
