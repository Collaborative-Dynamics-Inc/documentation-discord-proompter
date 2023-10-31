</prompt list-prompts:1125127413987295334>
> List all your prompts latest versions
- __**`simple`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Only shows the tier, prompt name & prompt post link (if posted)
- __**`csv`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Presents the list in a csv file

</prompt list-versions:1125127413987295334>
> List all versions of a prompt
> If no ID is provided, the prompt in the current channel is used, if available
- __**`prompt-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the prompt you want to list all versions for

</prompt inspect-version:1125127413987295334>
> Get all details about a specific version
> If no UUID is provided, the prompt in the current channel is used, if available
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the version you want to inspect

</prompt list-changes:1125127413987295334>
> List all changelogs of a prompt
> If no ID is provided, the prompt in the current channel is used, if available
- **`prompt-id`**
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the propt you want to get the changelogs for


_ _
</prompt create:1125127413987295334>
> Create a new prompt
- __**`prompt-file`**__
  - *[Required, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The file containing the prompt
- __**`image`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add a image to the prompt
- __**`price-in-cents`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- __**`redirect-url`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this prompt will only available to it's Proompters
- __**`class-rating`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Can be used to classify prompts in a S-D rating
- __**`name`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The name of your prompt


- __**`version`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The version of your prompt
- __**`description`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The intro message of your prompt
- __**`proompters`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list with all the Discord Users and/or names of **additional** proompters. Separated by semicolon, e.g: `@Proompter;Somebody else; @Another one`
- __**`exclude-me`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, you will not be included as a proompter. Necessary if a prompt is uploaded on behalf of somebody else
- __**`tags`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Semicolon separated list with tags which get applied to the prompt post


_ _
</prompt edit-prompt-version:1125127413987295334>
> Edit a prompt version
- __**`name`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New name for the prompt
- __**`image`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add a new image to the prompt
- __**`price-in-cents`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- __**`remove-price`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If true, this prompt will be set to *Free*
- __**`redirect-url`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this prompt will only available to it's Proompters
- __**`class-rating`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Can be used to classify prompts in a S-D rating


- __**`new-prompt-intro`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Manually set a new prompt intro
- __**`new-prompt-intro--file`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Manually set a new prompt intro from a textfile
- __**`prompt-intro-gpt-3`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-3 generate a new prompt intro
- __**`prompt-intro-gpt-4`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Let GPT-4 generate a new prompt intro
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The uuid of the prompt version you want to edit. Takes the prompt version of the current post, if available
- __**`proompters`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A list with all the Discord Users and/or names of **all** proompters. Separated by semicolon, e.g: `@Haffel; @Proompter;Somebody else;`
- __**`tags`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Semicolon separated list with tags which get applied to the prompt post


_ _
</prompt delete-prompt:1125127413987295334>
> Delete a prompt and all it's versions
> If no ID is provided, the prompt in the current channel is used, if available
- __**`prompt-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the prompt you want to delete

</prompt delete-prompt-version:1125127413987295334>
- Delete a specific version of a prompt
> If no UUID is provided, the prompt in the current channel is used, if available
- __**`version-uuid`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The UUID of the prompt version you want to delete

</prompt update:1125127413987295334>
> Update a prompt to a new version
- __**`prompt-file`**__
  - *[Required, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The .txt file containing the new version prompt
- __**`prompt-id`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The ID of the prompt you want to update
- __**`version`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The new version of the prompt
- __**`image`**__
  - *[Optional, Attachment](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Add/Change the image of this prompt. Will inherit from older versions
- __**`changes`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - What changes have been made in this new version of the prompt?
- __**`tags`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Semicolon separated list with additional tags which get applied to the prompt post