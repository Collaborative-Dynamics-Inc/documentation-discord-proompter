#### /tools token-counter
> Count how many tokens a prompt/file uses
- Either `input` or `input-file` needs to be passed
- **`input`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A simple text input to encode
- **`input-file`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - A text file which gets encoded
- __**`show-tokens`**__
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the output will be splitted into individual tokens
- __**`output-token-file`**__
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the output will be splitted into individual tokens and provided as file
- **`model`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Which encoding should be used to calculate the tokens? Currently all models have the same encoding



#### /tools tti-prompt
> Create a text-to-image generator prompt based on a description
- **`description`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Description to create the prompt based on



#### /tools discord-id
> Get the [ID of a user, role or channel](../guides/Good%20to%20Know/Get%20IDs%20of%20Roles-Users-Channels)
> Passing no argument will show your own user ID
- **`user`**
  - *[Optional, User](proompter-documentation/guides/Quickstart/Slash%20Commands.md####User)*
  - The user you want to get the ID for
- **`role`**
  - *[Optional, Role](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Role)*
  - The role you want to get the ID for
- **`channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel you want to get the ID for
  