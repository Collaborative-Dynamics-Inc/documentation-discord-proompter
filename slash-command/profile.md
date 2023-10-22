#### /profile favorite-prompts
> Shows a list of prompts you have reacted to

#### /profile templates set
> Set templates which are used to [download a conversation](proompter-documentation/slash-command/conversation.md####/conversation%20download)
> Learn more about how to create these templates [here](../reference/Conversation%20Export%20Templates)
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
	- **`JSON`**
	- **`Markdown`**
	- **`CSV`**
  - The format you want to set the template for. Right now only one format can be specified for each format
- **`template`**
  - *[Required, Attachment](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Attachment)*
  - The actual template you want to set, provided as `.txt` file

#### /profile templates show
> Shows the templates you specified, if any

#### /profile templates remove
> Remove a template
- **`format`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - *Available Options:*
	- **`JSON`**
	- **`Markdown`**
	- **`CSV`**
  - The format you want to remove the template for
