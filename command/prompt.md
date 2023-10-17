#### /prompt list-prompts
> List all your prompts latest versions
- **`simple`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Only shows the tier, prompt name & prompt post link (if posted)
- **`csv`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - Presents the list in a csv file

#### /prompt list-versions
> List all versions of a prompt
- **`prompt-id`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The ID of the prompt you want to list all versions for

#### /prompt inspect-version
> Get all details about a specific version
- **`version-uuid`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The UUID of the version you want to inspect

#### /prompt create
> Create a new prompt
- **`prompt-file`**
  - *[Required, Attachment](../reference/Slash%20Commands####Attachment)*
  - The file containing the prompt
- **`image`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - Add a image to the prompt
- **`price-in-cents`**
  - *[Optional, Integer](../reference/Slash%20Commands####Integer)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- **`redirect-url`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- **`is-public`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If false, this prompt will only available to it's Proompters
- **`class-rating`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Can be used to classify prompts in a S-D rating
- **`name`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The name of your prompt
- **`version`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The version of your prompt
- **`description`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The intro message of your prompt
- **`proompters`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - A list with all the Discord Users and/or names of **additional** proompters. Separated by semicolon, e.g: `@Proompter;Somebody else; @Another one`
- **`exclude-me`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, you will not be included as a proompter. Necessary if a prompt is uploaded on behalf of somebody else
- **`tags`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Semicolon separated list with tags which get applied to the prompt post

#### /prompt edit-prompt-version
> Edit a prompt version
- **`name`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - New name for the prompt
- **`image`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - Add a new image to the prompt
- **`price-in-cents`**
  - *[Optional, Integer](../reference/Slash%20Commands####Integer)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- **`remove-price`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, this prompt will be set to *Free*
- **`redirect-url`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- **`is-public`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If false, this prompt will only available to it's Proompters
- **`class-rating`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Can be used to classify prompts in a S-D rating
- **`new-prompt-intro`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Manually set a new prompt intro
- **`new-prompt-intro--file`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Manually set a new prompt intro from a textfile
- **`prompt-intro-gpt-3`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-3 generate a new prompt intro
- **`prompt-intro-gpt-4`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Let GPT-4 generate a new prompt intro
- **`version-uuid`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The uuid of the prompt version you want to edit. Takes the prompt version of the current post, if available
- **`proompters`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - A list with all the Discord Users and/or names of **all** proompters. Separated by semicolon, e.g: `@Haffel; @Proompter;Somebody else;`
- **`tags`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Semicolon separated list with tags which get applied to the prompt post

#### /prompt delete-prompt
> Delete a prompt and all it's versions
- **`prompt-id`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The ID of the prompt you want to delete

#### /prompt delete-prompt-version
- Delete a specific version of a prompt
- **`prompt-id`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The UUID of the prompt version you want to delete

#### /prompt update
> Update a prompt to a new version
- **`prompt-file`**
  - *[Required, Attachment](../reference/Slash%20Commands####Attachment)*
  - The .txt file containing the new version prompt
- **`prompt-id`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The ID of the prompt you want to update
- **`version`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - The new version of the prompt
- **`image`**
  - *[Optional, Attachment](../reference/Slash%20Commands####Attachment)*
  - Add/Change the image of this prompt. Will inherit from older versions
- **`changes`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - What changes have been made in this new version of the prompt?
- **`tags`**
  - *[Optional, String](../reference/Slash%20Commands####String)*
  - Semicolon separated list with additional tags which get applied to the prompt post
