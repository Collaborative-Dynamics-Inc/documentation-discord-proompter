</context details:1118400398970073148>
> Get details about the saved context in the current channel
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot

</context download:1118400398970073148>
> Download the context of the current channel
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot to download the context from

</context download-detailed:1118400398970073148>
> Download the context of the current channel
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot to download the detailed context from

</context manipulate-message:1118400398970073148>
> Edit a chatbot message
- __**`message-id`**__
  - *[Required, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the chatbot message you want to edit

</context clear:1118400398970073148>
> Clear the current channels context
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot to clear the context for
  - `@everyone` as chatbot role will delete the context for all chatbots with permission in the current channel
- __**`reload`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, the context will be rebuilt after clearing it
_ _
</context system-prompt:1118400398970073148>
> Load a prompt into the system message
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot to change the system prompt for
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Load a specific prompt into the system message
- __**`prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Enter a prompt which gets loaded into the system message
- __**`prompt-file`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add a .txt attachment which will get loaded into the system message
- If no argument is passed, the default system message will be loaded

</context load-from-json:1118400398970073148>
> Load a saved conversation into the context. Needs to a detailed context
- __**`chatbot`**__
  - *[Required, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role of the chatbot to load the context for
- __**`context-file`**__
  - *[Required, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A `.json` file containing a detailed context


_ _
_ _
_ _
**Note:**
> Context management operations like clear, manipulating or anything related to the system prompt can only be executed by non-admin users if it's in a thread created by said user. Context of public channels can only be changed by admins. Additional users inside a thread can also not change anything in the context right now, only the original creator of the thread.
> For system-prompt operations it's necessary to also be the creator of the chatbot














</context load-messages:1118400398970073148>
- Load older Discord messages into the context of the current channel
- __**`chatbot`**__
  - *Required, Role*
  - The role of the chatbot to load messages
- __**`amount`**__
  - *Required, Number*
  - *Minimum: 1*
  - *Maximum: 300*
  - The amount of messages to load