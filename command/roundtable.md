#### /roundtable create
> Create a roundtable with different chatbots
- **`chatbot-roles`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - A list with all the chatbots to participate, in order, separated by semicolon. For the role dropdown list to show up, add a whitespace between the semicolon and "@" symbol
- **`iterations`**
  - *[Required, Integer](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Integer)*
  - *Max: 20*
  - How many turns should each chatbot get?
- **`task`**
  - *[Required, String](proompter-documentation/guides/Quickstart/Slash%20Commands.md####String)*
  - The task for the roundtable
- **`clear-context`**
  - *[Optional, Boolean](proompter-documentation/guides/Quickstart/Slash%20Commands.md####Boolean)*
  - If true, the context for all participating chatbots will be cleared before adding the task
