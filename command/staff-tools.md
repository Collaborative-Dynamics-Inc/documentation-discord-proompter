#### /staff-tools send-json
> Sends a JSON payload to the chat. Currently only works in the name of Haffeltron
- **`json`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The JSON payload to send, for example a embed
- **`name`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - Name of the "User" which sends the content
- **`avatar-url`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The link to the image of the "User" avatar

#### /staff-tools delete-webhooks
> Delete all webhooks in the current channel

#### /staff-tools bulk-delete
> Delete multiple messages in this channel, going from the latest to the oldest
- **`amount`**
  - *[Required, Integer](../reference/Slash%20Commands####Integer)*
  - The amount of messages to delete

#### /staff-tools update-all-prompts
> Update all prompt posts
- **`tier-forum`**
  - *[Required, Channel](../reference/Slash%20Commands####Channel)*
  - The forum channel of the tier you want to update
- **`cancel`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Cancel an ongoing update process

#### /staff-tools unarchive-forum
> Open all threads in a forum
- **`forum`**
  - *[Required, Channel](../reference/Slash%20Commands####Channel)*
  - The forum of which all threads are opened

#### /staff-tools update-all-chatbot-libraries
> Update all chatbot library posts
- **`cancel`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Cancel an ongoing update process