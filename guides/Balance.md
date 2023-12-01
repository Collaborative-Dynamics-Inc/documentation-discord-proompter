# Balance
## Table of Contents
- **[How to check your Balance](#How%20to%20check%20your%20Balance)**
- **[How to buy Balance](#How%20to%20buy%20Balance)**
- **[How to cancel an Order](#How%20to%20cancel%20an%20Order)**
- **[Free monthly balance](#Free%20monthly%20balance)**
- **[Token Pricing](#Token%20Pricing)**
- **[Token Price Multiplicator](#Token%20Price%20Multiplicator)**
- **[Available Countries](#Available%20Countries)**


---


# How to check your Balance
- Use the [/balance info](../slash-command/balance####/balance%20info) command to get all the details about the balance you have

## Check how you spent your balance
> Pass the `show-transactions: True` [option](../guides/Quickstart/Slash%20Commands##Command%20Option%20Types) to get a list with all the transactions
> You can also download them by passing the `download-csv: True`  [option](../guides/Quickstart/Slash%20Commands##Command%20Option%20Types)


---


# How to buy Balance
- Use the [/balance buy](../slash-command/balance####/balance%20buy) command
	- Use the  [option](../guides/Quickstart/Slash%20Commands##Command%20Option%20Types) to define how many [packages](../reference/Balance%20Packages) you want to buy of each type
- Click on `Checkout`, you're browser should open the Stripe checkout page
- Add your payment details and confirm
- Usually it only takes a few seconds up to a few minutes until your balance arrives. If it takes longer (more than 10 minutes), check if your payment was successful. If yes, feel free to contact us so we can help you fix the issue


---


# How to cancel an Order
### Method 1
> Click on `Cancel Order` after you executed the [/balance buy](../slash-command/balance####/balance%20buy) command



### Method 2
- Execute the [/balance orders list](../slash-command/balance####/balance%20orders%20list)  command
- Grab the `UUID` of the order you want to cancel
- Use [/balance orders inspect](../slash-command/balance####/balance%20orders%20list) command and pass the `UUID`
- Click on `Cancel Order`

> **Note:** If the cancel order button isn't showing up, or the cancel fails, it usually means that the order is in a state where it cannot be cancelled
> Contact us if you wish to get a refund


---


# Free monthly balance
> [Patreon](<https://www.patreon.com/StunspotPrompting>) subscribers get free balance every month

**Tier 1**
> `$0.50`
**Tier 2**
> `$1.50`
**Tier 3**
> `$5.00`
**Tier 4**
> `$10.00`



**Note:**
> Every month your free balance gets loaded up again to the amount your highest tier is credible for
> For example, if you are on Tier 3, you get up to `$5` every month. Assuming you `$2` free credits left, you will get `$3` at the end of the month


---


# Token Pricing
We charge based on the tokens you use, and add an additional fee on top of that. The fee is percentage based, and the same across all models. It's defined by the token multiplicator

**Price per token (base price):**
- `gpt-3.5-turbo`
  - Input: `$0.0000015`
  - Output: `$0.000002`
- `gpt-3.5-turbo-16`
  - Input: `$0.000003`
  - Output: `$0.000004`
- `gpt-4-8k`
  - Input: `$0.00003`
  - Output: `$0.00006`


---


# Token Price Multiplicator
The token price multiplicator is visible in the [/balance info](../slash-command/balance####/balance%20info) overview. It defines the fee you pay ontop of every used token.


**Base price:** `x1`
> A token price multiplicator of `x1` reflects the exact price of a token. That means, if a token has a base price of `$0.00003`, you will pay that exact price for a token


**Current multiplicator:** `x1.33`
> On top of the token price, you automatically pay a 30% fee. For a token with a base price of `$0.00003`, you get charged `$0.00004`


---


# Available Countries
> Buying balance is currently only supported in the US






*Last edit: 13.11.2023*