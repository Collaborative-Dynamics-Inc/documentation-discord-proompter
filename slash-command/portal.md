</portal inspect-post:1125127413987295333>
> Shows all details about a post
- __**`post-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If not passed, it will use the current channel

</portal manage-post:1125127413987295333>
> Manage details for an existing prompt post
> Has to be used inside the post channel of the post one wants to change
- __**`new-portal-description`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set a custom portal description
- __**`new-portal-description-gpt-3`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-3.5 create a new portal description based on the prompt
- __**`new-portal-description-gpt-4`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-4 create a new portal description based on the prompt
- __**`new-emoji`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Set the emoji
- __**`new-portal-emoji-gpt-3`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-3.5 create a new portal emoji based on the portal description
- __**`new-portal-emoji-gpt-4`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-4 create a new portal emoji based on the portal description

</portal create-post:1125127413987295333>
> Create a new post for a prompt
- __**`version-uuid`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the version you want to create a post for


_ _
</portal delete-post:1125127413987295333>
> Delete a prompt post. This will NOT delete the actual prompt
- __**`post-channel-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel ID where the post is located. If not provided, the current channel is taken
- __**`delete-version`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, the prompt version in the post also gets deleted
- __**`delete-prompt`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, all versons of the prompt in the post also gets deleted

</portal move-to-tier:1125127413987295333>
> Move a prompt post to a different tier
- __**`tier-identifier`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The identifier of the tier to move the post to
- __**`reason`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Reason why the prompt gets moved to another tier


_ _
</portal register-post:1125127413987295333>
> Register a existing thread as prompt post
- __**`version-uuid`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the prompt version this post will be applied to
- __**`stats-message-id`**__
  - *[Required, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the statistics message of this post. `-1` if there is no message, a new one will be sent
- __**`portal-emoji`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Manually set a portal emoji
- __**`portal-description`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Manually set a portal description

</portal update-post:1125127413987295333>
> Update a existing post to the latest prompt version. If not later version is available, it will be refreshed with possible changes made to the prompt

</portal list-post-channels:1125127413987295333>
> List all post thread channels
