#### /staff-settings modules
> Manage different modules of the bot
> Passing no option will display the current settings
- **`module`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
    - **`SocialMediaPost`**
	- **`Instagram`**
- **`enabled`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Change the status of a module

#### /staff-settings chatbot ignored-channels
> Manage the channels which will be ignored by all chatbots
> Passing no option will display the current settings
- **`set-channels`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Set the list of ignored channels, separated by a semicolon
- **`add-channels`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Add a list of ignored channels, separated by a semicolon
- **`clear-channels`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Clear the list of ignored channels

#### /staff-settings chatbot chatbot-library
> Manage the chatbot library
> Passing no option will display the current settings
- **`forum-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The forum where chatbots will show up

#### /staff-settings prompt-portal
- Manage the prompt portal
> Passing no option will display the current settings
- **`ping-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - This role will be mentioned for prompt portal alerts

#### /staff-settings social-media instagram
> Manage Instagram settings
> Passing no option will display the current settings
- **`post-alert-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel where new posts will be alerted
- **`post-management-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel where prepared posts will show up
- **`ping-role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role which will be mentioned for new posts
- **`caption-suffix`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - This will be appended to the generated caption of a post

#### /staff-settings godmode
> Users/Roles with godmode have permissions to do almost everything
> Passing no option will display the current settings
- **`set-roles`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of roles, separated by semicolon
- **`set-users`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of users, separated by semicolon
  
#### /staff-settings gpt openai-api
> This OpenAI API key will be used for the whole guild
> Passing no option will display the current settings (shortens the API key)
- **`set-key`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Set the OpenAI API key
- **`remove-key`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Remove the OpenAI API key

#### /staff-settings moderation keywords
> Manage keyword based moderation filters
> Passing no option will display the current settings
- **`add-keywords`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Add a list of keywords (or sentences) to filter to the existing keywords, semicolon separated
- **`set-keywords`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Set the list of keywords (or sentences) to filter, semicolon separated
- **`clear-keywords`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Clear the keyword list

#### /staff-settings moderation openai
> Set the alert channel for moderation alerts
> Passing no option will display the current settings
- **`alert-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - Text channel where alerts are posted

#### /staff-settings keep-threads-open
> Threads usually auto-archive after a certain duration. But archived threads have limitations, for example they aren't visible for non-admins under certain circumstances, or cannot be edited by bots. Threads which are inside of a channel specified with this command, will automatically be unarchived as soon as they get archived
> Passing no option will display the current settings
- **`set-channels`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of channels to override the current settings, semicolon separated
- **`add-channels`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list of channels that will be added to the current list, semicolon separated
- **`clear-channels`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Remove all channels

#### /staff-settings leaderboard set
> Change the settings of a specific leaderboard
- **`type`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
    - [Check the leaderboard type list](../reference/Leaderboards##Types)
  - The leaderboard type you want to change the settings for
- **`set-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel where this leaderboard will be posted
- **`show-top-x`**
  - *[Required, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - The amount of entries that will be shown in this leaderboard

#### /staff-settings leaderboard update-all
> Update all leaderboards

#### /staff-settings leaderboard delete
> Delete a leaderboard
- **`type`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
    - [Check the leaderboard type list](../reference/Leaderboards##Types)

#### /staff-settings leaderboard get
> Get the settings of a leaderboard
- **`type`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
    - [Check the leaderboard type list](../reference/Leaderboards##Types)
