# Tier Permissions

__**Permissions:**__
- `VIEW` - Allows to see and use the prompts in the tier
- `CREATE` - Allows to create prompts for that tier
- `USE_CHATBOTS` - Allows to use chatbots running on prompts in this tier
- `MANAGE_CHATBOTS` - Allows to create chatbots with prompts in this tier

> By default, public tiers have `VIEW` permissions enabled for everyone. But nobody has `CREATE` permissions (unless they are a [godmode](../../reference/Godmode) user or have such a role). Private tiers don't give anyone permissions by default
> To generate the permissions you need to use the tool you can find further down. It's a simple webpage. Download & open it

#### Tier Permissions Generator Tool:
![[../../attachments/tier-permissions-generator-v0.2.html]]



- [Get the ID of the role](../Good%20to%20Know/Get%20IDs%20of%20Roles-Users-Channels) you want to set permissions for. It will look something like this `1141202059882930219`
- Add that ID into the "Role ID" input of the Permissions Generator
- Select which permissions that role should have
- Repeat the same process for all roles you want to manage
- Click on "Generate Permissions" to get the text you need to add as `role-permissions` in the `register-tier` command


![[../../attachments/role setup.png]]

