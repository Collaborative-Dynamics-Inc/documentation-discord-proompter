#### /prompt list-prompts
> List all your prompts latest versions
- **`simple`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Only shows the tier, prompt name & prompt post link (if posted)
- **`csv`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - Presents the list in a csv file

#### /prompt list-versions
> List all versions of a prompt
> If no ID is provided, the prompt in the current channel is used, if available
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the prompt you want to list all versions for

#### /prompt inspect-version
> Get all details about a specific version
> If no UUID is provided, the prompt in the current channel is used, if available
- **`version-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the version you want to inspect

#### /prompt list-changes
> List all changelogs of a prompt
> If no ID is provided, the prompt in the current channel is used, if available
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the propt you want to get the changelogs for

#### /prompt create
> Create a new prompt
- **`prompt-file`**
  - *[Required, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The file containing the prompt
- **`image`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - Add a image to the prompt
- **`price-in-cents`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- **`redirect-url`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- **`redirect-label`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The label shown on the `redirect-url` button. Default: `Go to marketplace`
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this prompt will only available to it's Proompters
- **`class-rating`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Can be used to classify prompts in a S-D rating
- **`name`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name of your prompt
- **`version`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The version of your prompt
- **`description`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The intro message of your prompt
- **`proompters`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list with all the Discord Users and/or names of **additional** proompters. Separated by semicolon, e.g: `@Proompter;Somebody else; @Another one`
- **`exclude-me`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, you will not be included as a proompter. Necessary if a prompt is uploaded on behalf of somebody else
- **`tags`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Semicolon separated list with tags which get applied to the prompt post

#### /prompt edit-prompt-version
> Edit a prompt version
- **`name`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - New name for the prompt
- **`image`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - Add a new image to the prompt
- **`price-in-cents`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Min: 50*
  - The price of this prompt in cents. 1000 = 10.00$
- **`remove-price`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, this prompt will be set to *Free*
- **`redirect-url`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - For prompts that are available outside of the Discord, for example a 3rd party marketplace. If this value is provided, an additional button will be added to the prompt post
- **`remove-redirect-url`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the redirect URL will be removed
- **`redirect-label`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The label shown on the `redirect-url` button. Default: `Go to marketplace`
- **`remove-redirect-label`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the redirect label will be removed
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this prompt will only available to it's Proompters
- **`class-rating`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Can be used to classify prompts in a S-D rating
- **`new-prompt-intro`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Manually set a new prompt intro
- **`new-prompt-intro--file`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Manually set a new prompt intro from a textfile
- **`prompt-intro-gpt-3`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Let GPT-3 generate a new prompt intro
- **`prompt-intro-gpt-4`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Let GPT-4 generate a new prompt intro
- **`version-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The uuid of the prompt version you want to edit. Takes the prompt version of the current post, if available
- **`proompters`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list with all the Discord Users and/or names of **all** proompters. Separated by semicolon, e.g: `@Haffel; @Proompter;Somebody else;`
- **`tags`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Semicolon separated list with tags which get applied to the prompt post

#### /prompt delete-prompt
> Delete a prompt and all it's versions
> If no ID is provided, the prompt in the current channel is used, if available
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the prompt you want to delete

#### /prompt delete-prompt-version
- Delete a specific version of a prompt
> If no UUID is provided, the prompt in the current channel is used, if available
- **`version-uuid`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The UUID of the prompt version you want to delete

#### /prompt update
> Update a prompt to a new version
- **`prompt-file`**
  - *[Required, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The .txt file containing the new version prompt
- **`prompt-id`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The ID of the prompt you want to update
- **`version`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The new version of the prompt
- **`image`**
  - *[Optional, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - Add/Change the image of this prompt. Will inherit from older versions
- **`changes`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - What changes have been made in this new version of the prompt?
- **`tags`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Semicolon separated list with additional tags which get applied to the prompt post
