# Conversation Export Templates

> The [/conversation download](<https://discord.com/channels/1100933695986208849/1164286329165717575>) allows to export conversations into nicely formatted files. Currently JSON and Markdown are supported

__**Default Templates**__
`JSON`
```
{
  "authorName": %authorName%,
  "content": %content%,
  "tokenCount": %tokenCount%,
  "messageTimestamp": %messageTimestamp(0)%
}
```

`Markdown`
```
**%authorName%** | %messageTimestamp(0)%
\`\`\`
Chatbot: %isChatbot%
Tokens: %tokenCount%
Characters: %characterCount%
\`\`\`


%content%


---


```



__**Available Placeholders**__
```
%conversationUUID%
%guildId%
%channelId%
%messageId%
%parentId%
%authorId%
%authorName%
%isChatbot%
%chatbotRoleId%
%content%
%tokenCount%
%messageTimestamp(0)%
%characterCount%
```
> Some of the values might have no value, in that case they show up as `--`


__**Specfiy Timezone**__
> The `%messageTimestamp(0)%` allows to set the timezone. It's calculated based on the UTC timezone.
- `%messageTimestamp(0)%` (Default) = UTC+0
- `%messageTimestamp(4)%` = UTC+4
- `%messageTimestamp(-7)%` = UTC-7


__**Use custom Templates**__
> You can create and safe your own templates. If it's a one-time use of a specific template, you can provide it as `template` option in the [/conversation download](<https://discord.com/channels/1100933695986208849/1164286329165717575>) command
> If you want to make it your new default template, you can safe it in your profile, by using the [/profile templates set](<https://discord.com/channels/1100933695986208849/1153688751260840108>) command

