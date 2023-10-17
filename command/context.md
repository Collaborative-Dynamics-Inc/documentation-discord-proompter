#### /context details
> Get details about the saved context in the current channel
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot

#### /context download
> Download the context of the current channel
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot to download the context from

#### /context download-detailed
> Download the context of the current channel
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot to download the detailed context from

#### /context manipulate-message
> Edit a chatbot message
- **`message-id`**
  - *[Required, Integer](../reference/Slash%20Commands####Integer)*
  - The ID of the chatbot message you want to edit

#### /context clear
> Clear the current channels context
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot to clear the context for
  - `@everyone` as chatbot role will delete the context for all chatbots with permission in the current channel
- **`reload`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, the context will be rebuilt after clearing it
_ _
#### /context system-prompt
> Load a prompt into the system message
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot to change the system prompt for
- **`version-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Load a specific prompt into the system message
- **`prompt`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Enter a prompt which gets loaded into the system message
- **`prompt-file`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - Add a .txt attachment which will get loaded into the system message
- If no argument is passed, the default system message will be loaded

#### /context load-from-json
> Load a saved conversation into the context. Needs to a detailed context
- **`chatbot`**
  - *[Required, Role](../reference/Slash%20Commands####Role)*
  - The role of the chatbot to load the context for
- **`context-file`**
  - *[Required, Attachment](../reference/Slash%20Commands####Attachment)*
  - A `.json` file containing a detailed context



#### /Note
> Context management operations like clear, manipulating or anything related to the system prompt can only be executed by non-admin users if it's in a thread created by said user. Context of public channels can only be changed by admins. Additional users inside a thread can also not change anything in the context right now, only the original creator of the thread.
> For system-prompt operations it's necessary to also be the creator of the chatbot
