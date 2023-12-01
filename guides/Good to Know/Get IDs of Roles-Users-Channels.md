# Get IDs of Roles, Users, Messages, Channels & Servers

> Behind the scenes, each role/user/message/channel/server has a unique ID. These IDs can be obtained either by having the [Developer Mode](./Developer%20Mode) enabled, or with a quick trick in the chat. Keep in mind, using chat only enables you to get roles, users and channels.

### Using Developer Mode
- [Enable Developer Mode](./Developer%20Mode)
- Right click on the element you want to get the ID for. 
- Click on "Copy ID" at the bottom

*With Developer Mode enabled*
![[../../Attachments/Developer Mode.png]]


---


### In the Chat
- Write the mention of a user/role or a channel reference like you would normally. For example, `@Haffel`, `@Chatbot 1` or `#documentation`
- Now, write a **backslash** `\` (NOT a slash `/`) before each mention. `\@Haffel`, `\@Chatbot 1` or `\#documentation`
- Send the message, and it should now show the ID of whatever you mentioned/referenced. Formats are like this:
  - `<@USER_ID>`
  - `<@&ROLE_ID>`
  - `<#CHANNEL_ID>`

#### Note
- Write the backslash after you wrote the mention, else it won't show any recommendations to autocomplete the name
- Each mention needs it's own backslash. It's not a message wide toggle

*Write mention(s)*
![[../../Attachments/Mentions.png]]

*Add backslash*
![[../../Attachments/Add Backslash.png]]

*Get IDs*
![[../../Attachments/IDs.png]]

> You can now use those IDs to mention roles/users or link to channels. To do that, simply write it in the above formats into the chat, and Discord will convert it into the normal format. That also works in [slash command options](../Quickstart/Slash%20Commands##Command%20Option%20Types)
> You can think of the backslashes as being a toggle to show the "raw" value instead of formatting it

> This can be especially useful when Discord has struggles to autocomplete the role of a chatbot you want to interact with. For those cases, the raw role ID shows in the [chatbot library](https://discord.com/channels/1100933695986208849/1137217914802548796) post of each bot


---


### From URLs
> Discord URLs utilize IDs, therefore you can get some of the IDs out of them. A Discord link to a specific message looks like this:
`https://discord.com/channels/1100933695986208849/1153869392178855966/1153871369277276170`
> There are three IDs:
`https://discord.com/channels/<server_id>/<channel_id>/<message_id>`
> A link to a channel/thread would only contain the guild and the channel id.

> Theres a nice trick you can do with this. Ever wanted to go to the start of a channel? Grab a link to any message in that channel, and replace the message ID with `0`. You get something like this:
`https://discord.com/channels/1100933695986208849/1100933696481140738/0`
> Open that and voila, you're at the beginning of that channel