# Get IDs of Roles, Users, Messages, Channels & Servers

> Behind the scenes, each role/user/message/channel/server has a unique ID. These IDs can be obtained either by having the [Developer Mode](https://discord.com/channels/1100933695986208849/1149283458905030696) enabled, or with a quick trick in the chat. Keep in mind, using chat only enables you to get roles, users and channels.

__**Using Developer Mode**__
- [Enable Developer Mode](https://discord.com/channels/1100933695986208849/1149283458905030696)
- Right click on the element you want to get the ID for. 
- Click on "Copy ID" at the bottom


_ _
*Developer Mode enabled*
![[Developer Mode.png]]





_ _
_ _
_ _
__**In the Chat**__
- Write the mention of a user/role or a channel reference like you would normally. For example, `@Haffel`, `@Chatbot 1` or `#documentation`
- Now, write a **backslash** `\` (NOT a slash `/`) before each mention. `\@Haffel`, `\@Chatbot 1` or `\#documentation`
- Send the message, and it should now show the ID of whatever you mentioned/referenced. Formats are like this:
  - `<@USER_ID>`
  - `<@&ROLE_ID>`
  - `<#CHANNEL_ID>`

<<<<<<< Updated upstream:guides/Good to Know/Get IDs of Roles-Users-Channels.md
#### Note:
=======
**Note:**
>>>>>>> Stashed changes:guides/Good to Know/Get IDs of Roles-Users-Chanels.md
- Write the backslash after you wrote the mention, else it won't show any recommendations to autocomplete the name
- Each mention needs it's own backslash. It's not a message wide toggle




_ _
*Write mention(s)*
![[Mentions.png]]
*Add backslash*
![[Add backslash.png]]

*Get IDs*
![[IDs.png]]




_ _
> You can now use those IDs to mention roles/users or link to channels. To do that, simply write it in the above formats into the chat, and Discord will convert it into the normal format. That also works in [slash command options](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)
> You can think of the backslashes as being a toggle to show the "raw" value instead of formatting it

> This can be especially useful when Discord has struggles to autocomplete the role of a chatbot you want to interact with. For those cases, the raw role ID shows in the <#1137217914802548796> post of each bot
> *Psst, want to talk to Discords AI powered Chatbot "Clyde"? Use Discords `/msg` command and paste 1081004946872352958 into the user option*





_ _
_ _
__**From URLs**__
> Discord URLs utilize IDs, therefore you can get some of the IDs out of them. A Discord link to a specific message looks like this:
`https://discord.com/channels/1100933695986208849/1153869392178855966/1153871369277276170`
> There are three IDs:
`https://discord.com/channels/<server_id>/<channel_id>/<message_id>`
> A link to a channel/thread would only contain the guild and the channel id.

> Theres a nice trick you can do with this. Ever wanted to go to the start of a channel? Grab a link to any message in that channel, and replace the message ID with `0`. You get something like this:
`https://discord.com/channels/1100933695986208849/1100933696481140738/0`
> Open that and voila, you're at the beginning of that channel






