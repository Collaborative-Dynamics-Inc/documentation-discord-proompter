#### /tier register-tier
> Register a new tier
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Name of this tier
- **`identifier`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Identifier shortcut for this tier
- **`forum-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The forum channel in which the prompts of this tier are
- **`portal-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel in which the portal will be
- **`update-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - Update channel for prompt alerts
- **`embed-color`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A hexadecimal color code, e.g: `#ffffff`**
- **`display-priority`**
  - *[Required, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - 1 is the highest priority
- **`description`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Description of the tier which will show between the title and the first embed
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this tier is only visible for roles with `VIEW` permissions
- **`role-permissions`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Permission overrides for roles

#### /tier list-tiers
> Lists all forum-channels which have a tier associated

#### /tier inspect-tier
> Shows all details about a tier
- **`forum-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The forum-channel the requested tier is associated with

#### /tier manage-tier
> Edit a existing tier
- **`current-identifier`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The identifier of the tier you want to edit
- **`name`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - New name
- **`identifier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - New identifier
- **`forum-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - New forum channel in which the prompts of this tier are
- **`portal-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - New channel in which the portal will be
- **`update-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - New update channel for prompt alerts
- **`embed-color`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - New hexadecimal color code, e.g: `#ffffff`**
- **`display-priority`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - 1 will be the highest tier in the list, 2 will be below 1 etc. Has to be unique
- **`description`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - New description of the tier which will show between the title and the first embed
- **`is-public`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If false, this tier is only visible for roles with `VIEW` permissions
- **`role-permissions`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Permission overrides for roles. Public channels have `VIEW` for everyone by default

#### /tier delete-tier
> Delete a tier entry
- **`forum-channel`**
  - *[Required, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - The channel which the tier corresponds to. Only delets the tier in the Database, nothing else. Portal embeds need to be deleted manually

#### /tier generate-portal
> Generates the portal embeds, old portal embed messages will be deleted
- **`portal-channel`**
  - *[Optional, Channel](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Channel)*
  - If not passed, the current channel will be used as portal-channel

#### /tier generate-portal-hub
> Sends a portal hub embed in the current channel
