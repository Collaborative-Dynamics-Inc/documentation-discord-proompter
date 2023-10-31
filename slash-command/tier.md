</tier register-tier:1128274313259257856>
> Register a new tier
- __**`name`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Name of this tier
- __**`identifier`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Identifier shortcut for this tier
- __**`forum-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The forum channel in which the prompts of this tier are
- __**`portal-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel in which the portal will be
- __**`update-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Update channel for prompt alerts
- __**`embed-color`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - A hexadecimal color code, e.g: `#ffffff`**__
- __**`display-priority`**__
  - *[Required, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - 1 is the highest priority
- __**`description`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Description of the tier which will show between the title and the first embed
- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this tier is only visible for roles with `VIEW` permissions
- __**`role-permissions`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Permission overrides for roles


_ _
</tier list-tiers:1128274313259257856>
> Lists all forum-channels which have a tier associated

</tier inspect-tier:1128274313259257856>
> Shows all details about a tier
- __**`forum-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The forum-channel the requested tier is associated with


_ _
</tier manage-tier:1128274313259257856>
> Edit a existing tier
- __**`current-identifier`**__
  - *[Required, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The identifier of the tier you want to edit
- __**`name`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New name
- __**`identifier`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New identifier
- __**`forum-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New forum channel in which the prompts of this tier are
- __**`portal-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New channel in which the portal will be
- __**`update-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New update channel for prompt alerts
- __**`embed-color`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New hexadecimal color code, e.g: `#ffffff`**__
- __**`display-priority`**__
  - *[Optional, Integer](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - 1 will be the highest tier in the list, 2 will be below 1 etc. Has to be unique
- __**`description`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - New description of the tier which will show between the title and the first embed
- __**`is-public`**__
  - *[Optional, Boolean](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If false, this tier is only visible for roles with `VIEW` permissions
- __**`role-permissions`**__
  - *[Optional, String](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - Permission overrides for roles. Public channels have `VIEW` for everyone by default


_ _
</tier delete-tier:1128274313259257856>
> Delete a tier entry
- __**`forum-channel`**__
  - *[Required, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - The channel which the tier corresponds to. Only delets the tier in the Database, nothing else. Portal embeds need to be deleted manually

</tier generate-portal:1128274313259257856>
> Generates the portal embeds, old portal embed messages will be deleted
- __**`portal-channel`**__
  - *[Optional, Channel](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278889156296724>)*
  - If not passed, the current channel will be used as portal-channel

</tier generate-portal-hub:1128274313259257856>
> Sends a portal hub embed in the current channel
