# Conversation Export Templates

> The [/conversation download](proompter-documentation/slash-command/conversation.md####/conversation%20download) allows to export conversations into nicely formatted files. Currently JSON and Markdown are supported

## Default Templates
`JSON`
```
{
  "authorName": {{author_name}},
  "isChatbot": {{is_chatbot}},
  "content": {{content}},
  "tokenCount": {{token_count}},
  "characterCount": {{character_count}},
  "messageTimestamp": {{message_timestamp(0)}}
}
```

`Markdown`
```
**{{author_name}}** | {{message_timestamp(0)}}
\`\`\`
Chatbot: {{is_chatbot}}
Tokens: {{token_count}}
Characters: {{character_count}}
\`\`\`


{{content}}


---

```

`CSV`
```
author_name,content,token_count,message_timestamp
```



## Available Placeholders
```
{{conversation_uuid}}
{{guild_id}}
{{channel_id}}
{{message_id}}
{{parent_id}}
{{author_id}}
{{author_name}}
{{is_chatbot}}
{{chatbot_role_id}}
{{content}}
{{token_count}}
{{message_timestamp(0)}}
{{character_count}}
```
> Some of the values might have no value, in that case they show up as `--`
> **Note:** For CSV:
- `message_timestamp` cannot be formatted into a human readable timestamp
- `character_count` is not available



### Specfiy Timezone
> The `{{messageTimestamp(0)}}` allows to set the timezone. It's calculated based on the UTC timezone.
- `{{messageTimestamp(0)}}` (Default) = UTC+0
- `{{messageTimestamp(4)}}` = UTC+4
- `{{messageTimestamp(-7)}}` = UTC-7


### Use custom Templates
> You can create and safe your own templates. If it's a one-time use of a specific template, you can provide it as `template` option in the  [/conversation download](proompter-documentation/slash-command/conversation.md####/conversation%20download) command
> If you want to make it your new default template, you can safe it in your profile, by using the [/profile templates set](proompter-documentation/slash-command/profile.md####/profile%20templates%20set) command

