#### /index
> Get a full list of prompts, based on some filters
- `filter`
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A selection of one or more filters
  - Options:
    - *name*
	- *title* - Title of the prompt. As title the first part before a " - " in the prompt name is considered. Will not list any prompts without that pattern
	- *tier_identifier*
	- *character_count*
	- *token_count*
	- Each option can be either `ASC` (ascending) or `DESC` (descending)

## IMPORTANT
- This command is currently broken and theres no ETA when it's gonna be fixed as the issue is still unknown
