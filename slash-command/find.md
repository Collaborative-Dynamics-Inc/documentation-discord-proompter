#### /find prompt by-name
> Keyword search based on prompt names

#### /find prompt by-description
> Keyword search based on portal description

#### /find prompt by-tag
> Keyword search based on prompt tags



##### Prompt Search Options
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name you want to search for
- **`tier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifiers, separated by semicolons. For example: `T1;T2` searches only in Tier 1 & 2
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 100*
  - The maximum amount of results per page
- **`include-ids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: true*
  - If true, prompt IDs get included in the results. Useful for Proompters
- **`include-uuids`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: false*
  - If true, version UUIDs get included in the results. Useful for Proompters
- **`min-tokens`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - Search for prompts with a minimum amount of tokens
- **`max-tokens`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - Search for prompts with a maximum amount of tokens
- **`min-characters`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - Search for prompts with a minimum amount of characters
- **`max-characters`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - Search for prompts with a maximum amount of characters
- **`export-csv`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - *Default: false*
  - If true, the search results are exported to a .csv file

---

#### /find chatbot by-name
> Keyword search based on chatbot names
- **`name`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The name you want to search for
- **`tier`**
  - *[Optional, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifiers, separated by semicolons. For example: `T1;T2` searches only in Tier 1 & 2
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 100*
  - The maximum amount of results per page

#### /find chatbot by-tier
> List all chatbots in a specific tier
- **`tier`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - Tier identifier to search for
- **`max-results`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Default: 10*
  - *Max value: 100*
  - The maximum amount of results per page