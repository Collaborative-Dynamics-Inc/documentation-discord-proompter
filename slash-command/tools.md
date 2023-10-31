</tools token-counter:1134802420359250053>
> Count how many tokens a prompt/file uses
- __**`model`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Which encoding should be used to calculate the tokens? Currently all models have the same encoding
- __**`prompt`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A simple text input to encode
- __**`prompt-file`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A file which gets encoded
- Either `prompt` or `prompt-file` needs to be passed

</tools tti-prompt:1134802420359250053>
> Create a text-to-image generator prompt based on a description
- __**`description`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Description to create the prompt based on

</tools discord-id:1134802420359250053>
> Get the [ID of a user, role or channel](<https://discord.com/channels/1100933695986208849/1149283993548759090>)
> Passing no argument will show your own user ID
- __**`user`**__
  - *[Optional, User](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The user you want to get the ID for
- __**`role`**__
  - *[Optional, Role](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The role you want to get the ID for
- __**`channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel you want to get the ID for