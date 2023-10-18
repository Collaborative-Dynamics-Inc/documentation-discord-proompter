# Slash Commands
> Slash Commands are a very convenient way to interact with Discord bots. They allow to have a clear syntax which makes it very easy to use them


## Table of contents
- **[Parts](##Parts)**
  - **[Command Option Types](##Command%20Option%20Types)**
- **[Usage](##Usage)**


---


## Parts
> A slash command can contain several different parts:
- 🟩 A subcommand
- 🟦 Required option
- 🟨 Optional option
- 🟪 All the different parts have a description to give a quick explanation about what the specific command/option is there for
> Each option can be of a different type, for example an user/role, an integer/number, an attachment or a string/text.

![[command-parts.png]]


---


## Command Option Types
#### User
> It's the same as mentioning a user a chat by writing `@Haffel`
#### Role
> It's the same as mentioning a role in a chat by writing `@Admin`
### Channel
> Similar to the users or roles, a channel can be selected like this: `#documentation`

### Boolean
> Either "true" or "false" is valid

### String
> A string is just any plain text. It can be a single character, or a whole paragraph

### Integer
> Integers are whole numbers without any decimals like `1`, `-3` or `4723`

### Number
> Numbers can have decimal places too. Unlike for many other applications, Discord wants numbers with commas, not with dots. That means to pass 1 and a half as a number, you need to write `1,5` NOT `1.5` as `1.5` would be turned into `15` behind the scenes

### Attachment
> An attachment is any file that gets uploaded to Discord. Proompter commands usually have a note about which files are supported. `Textfile` would be `.txt` or `CSV` would be a `.csv`
> Keep in mind that even if an option only allows certain filetypes, you can still add any other file when entering the command. It just throws an error after executing it


### Required vs Optional vs Conditional Option
> - **Required** options need to be passed to execute the command at all
> - **Optional** options can be passed if necessary. Check the commands documentation to decide if it's necessary or not
> - **Conditional** options aren't a specific type provided by Discord, so they aren't displayed any different. They are just two or more optional options and if none is provided, the command will fail

![[option-types.png]]


---


## Usage
> Simply write a slash (`/`) in the empty chat and a list with commands will pop-up.
> From there, you can either select them with your mouse/arrow keys or write the command into the chat. Follow the descriptions/documentation of the specific command/subcommand to enter all the parameters you need

![[command-list.png]]
