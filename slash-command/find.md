#### /find prompt by-name
> Keyword search based on prompt names
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name you want to search for
- **`tier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifier. Limit the search to only a specific tier
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 50*
  - The maximum amount of results which get provided
- **`include-ids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: true*
  - If true, prompt IDs get included in the results. Useful for Proompters
- **`include-uuids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: false*
  - If true, version UUIDs get included in the results. Useful for Proompters

#### /find prompt by-description
> Keyword search based on portal description
- **`description`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The description you want to search for
- **`tier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifier. Limit the search to only a specific tier
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 50*
  - The maximum amount of results which get provided
- **`include-ids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: true*
  - If true, prompt IDs get included in the results. Useful for Proompters
- **`include-uuids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: false*
  - If true, version UUIDs get included in the results. Useful for Proompters

#### /find prompt by-tag
> Keyword search based on prompt tags
- **`tag`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The tag you want to search for
- **`tier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifier. Limit the search to only a specific tier
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 50*
  - The maximum amount of results which get provided
- **`include-ids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: true*
  - If true, prompt IDs get included in the results. Useful for Proompters
- **`include-uuids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: false*
  - If true, version UUIDs get included in the results. Useful for Proompters

#### /find chatbot
> Lists all chatbots you have permission for
