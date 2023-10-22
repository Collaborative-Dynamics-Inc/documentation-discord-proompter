#### /staff-tools send-json
> Sends a JSON payload to the chat. Currently only works in the name of Haffeltron
- **`json`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The JSON payload to send, for example a embed
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Name of the "User" which sends the content
- **`avatar-url`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The link to the image of the "User" avatar

#### /staff-tools delete-webhooks
> Delete all webhooks in the current channel

#### /staff-tools bulk-delete
> Delete multiple messages in this channel, going from the latest to the oldest
- **`amount`**
  - *[Required, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - The amount of messages to delete

#### /staff-tools update-all-prompts
> Update all prompt posts
- **`tier-forum`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The forum channel of the tier you want to update
- **`cancel`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Cancel an ongoing update process

#### /staff-tools unarchive-forum
> Open all threads in a forum
- **`forum`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The forum of which all threads are opened

#### /staff-tools update-all-chatbot-libraries
> Update all chatbot library posts
- **`cancel`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Cancel an ongoing update process

#### /staff-tools clear-all-context
> Clears the context for all chatbots in all conversations on the server