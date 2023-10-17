#### /roundtable create
> Create a roundtable with different chatbots
- **`chatbot-roles`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - A list with all the chatbots to participate, in order, separated by semicolon. For the role dropdown list to show up, add a whitespace between the semicolon and "@" symbol
- **`iterations`**
  - *[Required, Integer](../reference/Slash%20Commands####Integer)*
  - *Max: 20*
  - How many turns should each chatbot get?
- **`task`**
  - *[Required, String](../reference/Slash%20Commands####String)*
  - The task for the roundtable
- **`clear-context`**
  - *[Optional, Boolean](../reference/Slash%20Commands####Boolean)*
  - If true, the context for all participating chatbots will be cleared before adding the task
