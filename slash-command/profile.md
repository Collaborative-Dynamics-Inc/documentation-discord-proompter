</profile bookmarked-messages list:1153117013506543626>
- List all bookmarked messages

</profile bookmarked-messages add:1153117013506543626>
- Bookmark a message
- __**`message-url`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The Discord link to the message
- __**`note`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A note to quickly identify the message when listing them

</profile bookmarked-messages remove:1153117013506543626>
- Remove a bookmarked message
- __**`message-url`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The Discord link to the message

</profile bookmarked-messages clear:1153117013506543626>
- Remove all bookmarked messages



_ _
_ _
</profile favorite-prompts:1153117013506543626>
> Shows a list of prompts you have reacted to



_ _
_ _
</profile templates set:1153117013506543626>
> Set templates which are used to [download a conversation](<https://discord.com/channels/1100933695986208849/1164286329165717575>)
> Learn more about how to create these templates [here](<https://discord.com/channels/1100933695986208849/1164336383679275088>)
- __**`format`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
	- __**`JSON`**__
	- __**`Markdown`**__
	- __**`CSV`**__
  - The format you want to set the template for. Right now only one format can be specified for each format
- __**`template`**__
  - *[Required, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The actual template you want to set, provided as `.txt` file

</profile templates show:1153117013506543626>
> Shows the templates you specified, if any

</profile templates remove:1153117013506543626>
> Remove a template
- __**`format`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
	- __**`JSON`**__
	- __**`Markdown`**__
	- __**`CSV`**__
  - The format you want to remove the template for



_ _
_ _
</profile raw-profile-data:1153117013506543626>
- Shows all your profile data in JSON









_ _
_ _
</profile gpt-settings-global show:1153117013506543626>
- Shows all GPT the settings you specified

</profile gpt-settings-global reset:1153117013506543626>
- Reset a specific GPT setting
- __**`model`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the GPT model
- __**`temperature`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the temperature
- __**`top-p`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the TopP setting
- __**`max-tokens`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the max response tokens settings
- __**`presence-penalty`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the presence penalty settings
- __**`frequency-penalty`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset the frequency penalty settings
- __**`all`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reset all settings

</profile gpt-settings-global set:1153117013506543626>
- Define your GPT settings
- __**`model`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: gpt-3.5-turbo-16k-0613*
- __**`temperature`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`top-p`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 0*
  - *Max: 2*
  - *Default: 1*
- __**`max-tokens`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Max: Model limit*
  - *Default: 1500*
  - Maximum amount of tokens reserved for Chatbot responses
- __**`presence-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*
- __**`frequency-penalty`**__
  - *[Optional, Number](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: -2*
  - *Max: 2*
  - *Default: 0*