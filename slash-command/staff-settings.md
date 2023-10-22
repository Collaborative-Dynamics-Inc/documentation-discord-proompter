</staff-settings modules:1140394502863986710>
> Manage different modules of the bot
> Passing no option will display the current settings
- __**`module`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
    - __**`SocialMediaPost`**__
	- __**`Instagram`**__
- __**`enabled`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Change the status of a module

</staff-settings chatbot ignored-channels:1140394502863986710>
> Manage the channels which will be ignored by all chatbots
> Passing no option will display the current settings
- __**`set-channels`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set the list of ignored channels, separated by a semicolon
- __**`add-channels`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add a list of ignored channels, separated by a semicolon
- __**`clear-channels`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Clear the list of ignored channels

</staff-settings chatbot chatbot-library:1140394502863986710>
> Manage the chatbot library
> Passing no option will display the current settings
- __**`forum-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The forum where chatbots will show up

</staff-settings prompt portal:1140394502863986710>
- Manage the prompt portal
> Passing no option will display the current settings
- __**`ping-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - This role will be mentioned for prompt portal alerts


_ _
</staff-settings prompt intro-prompt:1140394502863986710>
> Change the prompt that is used to create the initial prompt post intros
> Passing no option will display the current settings
- __**`set-prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: `Introduce yourself and tell me what your capable of`*
  - The new prompt to use
- __**`clear-prompt`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Clear the current prompt (will use the default again)

</staff-settings prompt portal-prompt:1140394502863986710>
> Change the prompt that is used to create the prompt portal summaries
> Passing no option will display the current settings
> **Important:** You need to use the `{{prompt}}` placeholder somewhere in your prompt, else it will not know which prompt to create the summary for
- __**`set-prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Default: `Summarize the capabilities of the following persona:\n{{prompt}}`*
  - The new prompt to use
- __**`clear-prompt`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Clear the current prompt (will use the default again)



_ _
</staff-settings social-media instagram:1140394502863986710>
> Manage Instagram settings
> Passing no option will display the current settings
- __**`post-alert-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel where new posts will be alerted
- __**`post-management-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel where prepared posts will show up
- __**`ping-role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role which will be mentioned for new posts
- __**`caption-suffix`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - This will be appended to the generated caption of a post

</staff-settings godmode:1140394502863986710>
> Users/Roles with godmode have permissions to do almost everything
> Passing no option will display the current settings
- __**`set-roles`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of roles, separated by semicolon
- __**`set-users`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of users, separated by semicolon


_ _  
</staff-settings gpt openai-api:1140394502863986710>
> This OpenAI API key will be used for the whole guild
> Passing no option will display the current settings (shortens the API key)
- __**`set-key`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set the OpenAI API key
- __**`remove-key`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Remove the OpenAI API key

</staff-settings moderation keywords:1140394502863986710>
> Manage keyword based moderation filters
> Passing no option will display the current settings
- __**`add-keywords`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add a list of keywords (or sentences) to filter to the existing keywords, semicolon separated
- __**`set-keywords`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set the list of keywords (or sentences) to filter, semicolon separated
- __**`clear-keywords`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Clear the keyword list
</staff-settings moderation openai:1140394502863986710>
> Set the alert channel for moderation alerts
> Passing no option will display the current settings
- __**`alert-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Text channel where alerts are posted

_ _
</staff-settings keep-threads-open:1140394502863986710>
> Threads usually auto-archive after a certain duration. But archived threads have limitations, for example they aren't visible for non-admins under certain circumstances, or cannot be edited by bots. Threads which are inside of a channel specified with this command, will automatically be unarchived as soon as they get archived
> Passing no option will display the current settings
- __**`set-channels`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of channels to override the current settings, semicolon separated
- __**`add-channels`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list of channels that will be added to the current list, semicolon separated
- __**`clear-channels`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Remove all channels

</staff-settings leaderboard set:1140394502863986710>
> Change the settings of a specific leaderboard
- __**`type`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
    - [Check the leaderboard type list](<LINK>)
  - The leaderboard type you want to change the settings for
- __**`set-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel where this leaderboard will be posted
- __**`show-top-x`**__
  - *[Required, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The amount of entries that will be shown in this leaderboard

_ _
</staff-settings leaderboard update-all:1140394502863986710>
> Update all leaderboards

</staff-settings leaderboard delete:1140394502863986710>
> Delete a leaderboard
- __**`type`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
    - [Check the leaderboard type list](<https://discord.com/channels/1100933695986208849/1160727372518137918>)

</staff-settings leaderboard get:1140394502863986710>
> Get the settings of a leaderboard
- __**`type`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Available Options:*
    - [Check the leaderboard type list](<https://discord.com/channels/1100933695986208849/1160727372518137918>)




