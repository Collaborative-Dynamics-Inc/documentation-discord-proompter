</staff-tools send-json:1134802420359250054>
> Sends a JSON payload to the chat. Currently only works in the name of Haffeltron
- __**`json`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The JSON payload to send, for example a embed
- __**`name`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Name of the "User" which sends the content
- __**`avatar-url`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The link to the image of the "User" avatar

</staff-tools delete-webhooks:1134802420359250054>
> Delete all webhooks in the current channel

</staff-tools bulk-delete:1134802420359250054>
> Delete multiple messages in this channel, going from the latest to the oldest
- __**`amount`**__
  - *[Required, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The amount of messages to delete

</staff-tools update-all-prompts:1134802420359250054>
> Update all prompt posts
- __**`tier-forum`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The forum channel of the tier you want to update
- __**`cancel`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Cancel an ongoing update process

</staff-tools unarchive-forum:1134802420359250054>
> Open all threads in a forum
- __**`forum`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The forum of which all threads are opened

_ _
</staff-tools update-all-chatbot-libraries:1134802420359250054>
> Update all chatbot library posts
- __**`cancel`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Cancel an ongoing update process

</staff-tools clear-all-context:1134802420359250054>
> Clears the context for all chatbots in all conversations on the server