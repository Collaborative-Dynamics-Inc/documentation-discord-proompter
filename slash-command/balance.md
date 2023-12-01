#### /balance info
> Shows details about your balance and LLM usage
- **`show-transactions`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, all transactions are shown
- **`download-csv`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, a CSV file with all the transactions will be created

#### /balance buy
> Buy balance to interact with chatbots and use all Proompter tools. Check [this](../reference/Balance%20Packages) for more details about balance packages & bonuses
> At least one option needs to be provided
- **`5-dollar`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - The amount of `$5` packages you want to buy
- **`10-dollar`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - The amount of `$10` packages you want to buy
- **`20-dollar`**
  - *[Optional, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - The amount of `$20` packages you want to buy

#### /balance orders inspect
> Get all the details about a specific order
- **`order-uuid`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*

#### /balance orders list
> List all your orders
