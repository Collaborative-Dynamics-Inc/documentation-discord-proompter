# Tier Permissions

__**Permissions:**__
- `VIEW` - Allows to see and use the prompts in the tier
- `CREATE` - Allows to create prompts for that tier
- `USE_CHATBOTS` - Allows to use chatbots running on prompts in this tier
- `MANAGE_CHATBOTS` - Allows to create chatbots with prompts in this tier

> By default, public tiers have `VIEW` permissions enabled for everyone. But nobody has `CREATE` permissions (unless they are a [godmode](https://discord.com/channels/1100933695986208849/1141470321245954189) user or have such a role). Private tiers don't give anyone permissions by default
> To generate the permissions you need to use the tool you can find further down. It's a simple webpage. Download & open it

- [Get the ID of the role](<https://discord.com/channels/1100933695986208849/1149283993548759090>) you want to set permissions for. It will look something like this `1141202059882930219`
- Add that ID into the "Role ID" input of the Permissions Generator
- Select which permissions that role should have
- Repeat the same process for all roles you want to manage
- Click on "Generate Permissions" to get the text you need to add as `role-permissions` in the `register-tier` command




![[tier-permissions-generator-v0.1.html]]

![[Role setup.png]]
