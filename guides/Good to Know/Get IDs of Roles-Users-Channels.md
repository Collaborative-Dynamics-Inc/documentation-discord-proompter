# Get IDs of Roles/Users/Channels

> Behind the scenes, every channel/role/user/server has a unique ID. These IDs can be obtained either by having the [Developer Mode](./Developer%20Mode) enabled, or with a quick trick in the chat.

### Developer Mode
- [Enable Developer Mode](./Developer%20Mode)
- Right click on a channel/user/role/server
- Click on "Copy ID" at the bottom

### Chat
- Write the mention of a user/role or a channel reference like you would normally. For example, `@Haffel`, `@Chatbot 1` or `#documentation`
- Now, write a backslash `\` before that mention. `\@Haffel`, `\@Chatbot 1` or `\#documentation`. Don't write the backslash before writing the mention, as it won't show any recommendations for users/roles/channels
- Send the message, and it should now show the ID of whatever you mentioned/referenced. Formats are like this:
  - `<@USER_ID>`
  - `<@&ROLE_ID>`
  - `<#CHANNEL_ID>`
- In the way as the IDs get presented, you can also use them to mention users, roles or channels with the same format. That format can also be used inside of [slash command options](../../reference/Slash%20Commands##Command%20Option%20Types)


---


*With Developer Mode enabled*
![[../../Attachments/Developer Mode.png]]


---


*Write mention(s)*
![[../../Attachments/Mentions.png]]

*Add backslash*
![[../../Attachments/Add Backslash.png]]

*Get IDs*
![[../../Attachments/IDs.png]]


