#### /tools token-counter
> Count how many tokens a prompt/file uses
- **`model`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - Which encoding should be used to calculate the tokens? Currently all models have the same encoding
- **`prompt`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - A simple text input to encode
- **`prompt-file`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - A file which gets encoded
- Either `prompt` or `prompt-file` needs to be passed

#### /tools tti-prompt
> Create a text-to-image generator prompt based on a description
- **`description`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - Description to create the prompt based on

#### /tools discord-id
> Get the [ID of a user, role or channel](../guides/Good%20to%20Know/Get%20IDs%20of%20Roles-Users-Channels)
> Passing no argument will show your own user ID
- **`user`**
  - *[Optional, User](../reference/Slash%20Commands####User)*
  - The user you want to get the ID for
- **`role`**
  - *[Optional, Role](../reference/Slash%20Commands####Role)*
  - The role you want to get the ID for
- **`channel`**
  - *[Optional, Channel](../reference/Slash%20Commands####Channel)*
  - The channel you want to get the ID for
  