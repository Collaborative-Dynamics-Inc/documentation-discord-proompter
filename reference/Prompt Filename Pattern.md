# Prompt Filename Pattern

> By following a specific filename pattern the usage of most commands is very easy as most informations just get extracted from it. It looks like this: `Idea Generator - BRAINSTORMER T0 v2.0.txt`

The pattern consist of three parts:
1. **Name**
  - The name can be whatever you want, it doesn't matter
2. **Tier Identifier**
  - `T0` is the [tier identifier](./Tier%20Identifiers%20in%20CD) for the Free Tier
3. **Version**
  - `v2.0` is the version of this prompt. It's the last part before the filetype `.txt`
  - It can be written as `v2.0`, `V2`, `2.0`, `v2` etc.

> To make sure the filename pattern is recognized, make sure that the version is the last part of the filename. Nothing may be between the version and the filetype `.txt`
> The tier identifier needs to be separated by a whitespace or underline* from the version, and has to be the second last part. Everything else doesn't matter, as the Bot will just take all thats left as the name

> **Discord replaces all whitespace with a underline as soon as the attachment gets uploaded. So no worries about them*
> `Idea Generator - BRAINSTORMER T0 v2.0.txt` gets converted to `Idea_Generator_-_BRAINSTORMER_T0_v2.0.txt`


### Note:
> The mentioned Tier identifiers are specific for the "Stunspot Prompting" Discord. On other servers the setup might be different, therefore other identifiers are valid.