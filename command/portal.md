#### /portal inspect-post
> Shows all details about a post
- **`post-channel`**
  - *[Optional, Channel](../reference/Slash%20Commands####Channel)*
  - If not passed, it will use the current channel

#### /portal manage-post
> Manage details for an existing prompt post
> Has to be used inside the post channel of the post one wants to change
- **`new-portal-description`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Set a custom portal description
- **`new-portal-description-gpt-3`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-3.5 create a new portal description based on the prompt
- **`new-portal-description-gpt-4`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-4 create a new portal description based on the prompt
- **`new-emoji`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Set the emoji
- **`new-portal-emoji-gpt-3`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-3.5 create a new portal emoji based on the portal description
- **`new-portal-emoji-gpt-4`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-4 create a new portal emoji based on the portal description

#### /portal create-post
> Create a new post for a prompt
- **`version-uuid`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The UUID of the version you want to create a post for

#### /portal delete-post
> Delete a prompt post. This will NOT delete the actual prompt
- **`post-channel-id`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The channel ID where the post is located. If not provided, the current channel is taken
- **`delete-version`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, the prompt version in the post also gets deleted
- **`delete-prompt`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, all versons of the prompt in the post also gets deleted

#### /portal move-to-tier
> Move a prompt post to a different tier
- **`tier-identifier`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The identifier of the tier to move the post to
- **`reason`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Reason why the prompt gets moved to another tier

#### /portal register-post
> Register a existing thread as prompt post
- **`version-uuid`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The UUID of the prompt version this post will be applied to
- **`stats-message-id`**
  - *[Required, Integer](../reference/Slash%20Commands####Integer)*
  - The ID of the statistics message of this post. `-1` if there is no message, a new one will be sent
- **`portal-emoji`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Manually set a portal emoji
- **`portal-description`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Manually set a portal description

#### /portal update-post
> Update a existing post to the latest prompt version. If not later version is available, it will be refreshed with possible changes made to the prompt

#### /portal list-post-channels
> List all post thread channels
