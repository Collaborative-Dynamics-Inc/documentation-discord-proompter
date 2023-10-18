#### /staff-conversation list
> List all saved conversations

#### /staff-conversation inspect
> Show details about a conversation
- **`conversation-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - If no UUID is provided, the conversation in the current channel is used

#### /staff-conversation message list
> List all messages in a conversation
- **`conversation-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - If no UUID is provided, the conversation in the current channel is used

#### /staff-conversation message inspect
> Get details about a specific message in a conversation
- **`message-uuid`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the message you want to get details for
