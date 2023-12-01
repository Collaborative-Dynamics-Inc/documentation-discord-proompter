Thread is called *Reference - Balance* (alle links ändern falls neuer thread erstellt wird)


# Balance
## Table of Contents
- **[How to check your Balance](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620831381893160>)**
- **[How to buy Balance](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620854530248775>)**
- **[How to cancel an Order](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620877691211887>)**
- **[Free monthly balance](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620915528020000>)**
- **[Token Pricing](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620941444616192>)**
- **[Token Price Multiplicator](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173620998696865973>)**
- **[Available Countries](<https://discord.com/channels/1100933695986208849/1173620749827842078/1173623081399492608>)**







_ _
_ _
_ _
_ _
_ _
# How to check your Balance
- Use the [/balance info](<https://discord.com/channels/1100933695986208849/1136860811189551195>) command to get all the details about the balance you have

## Check how you spent your balance
> Pass the `show-transactions: True` [option](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278821565079614>) to get a list with all the transactions
> You can also download them by passing the `download-csv: True` [option](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278821565079614>)








_ _
_ _
_ _
_ _
_ _
# How to buy Balance
- Use the [/balance buy](<https://discord.com/channels/1100933695986208849/1136860811189551195>) command
	- Use the [optional options](<https://discord.com/channels/1100933695986208849/1139918131737923614/1149278821565079614>) to define how many [packages](<https://discord.com/channels/1100933695986208849/1173580792660775023>) you want to buy of each type
- Click on `Checkout`, you're browser should open the Stripe checkout page
- Add your payment details and confirm
- Usually it only takes a few seconds up to a few minutes until your balance arrives. If it takes longer (more than 10 minutes), check if your payment was successful. If yes, feel free to contact us so we can help you fix the issue









_ _
_ _
_ _
_ _
_ _
# How to cancel an Order
### Method 1
> Click on `Cancel Order` after you executed the [/balance buy](<https://discord.com/channels/1100933695986208849/1136860811189551195>) command



### Method 2
- Execute the [/balance orders list](<https://discord.com/channels/1100933695986208849/1136860811189551195>) command
- Grab the `UUID` of the order you want to cancel
- Use [/balance orders inspect](<https://discord.com/channels/1100933695986208849/1136860811189551195>) command and pass the `UUID`
- Click on `Cancel Order`

> **Note:** If the cancel order button isn't showing up, or the cancel fails, it usually means that the order is in a state where it cannot be cancelled
> Contact us if you wish to get a refund








_ _
_ _
_ _
_ _
_ _
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









_ _
_ _
_ _
_ _
_ _
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











_ _
_ _
_ _
_ _
_ _
# Token Price Multiplicator
The token price multiplicator is visible in the [/balance info](<https://discord.com/channels/1100933695986208849/1136860811189551195>) overview. It defines the fee you pay ontop of every used token.


**Base price:** `x1`
> A token price multiplicator of `x1` reflects the exact price of a token. That means, if a token has a base price of `$0.00003`, you will pay that exact price for a token


**Current multiplicator:** `x1.33`
> On top of the token price, you automatically pay a 30% fee. For a token with a base price of `$0.00003`, you get charged `$0.00004`





_ _
_ _
_ _
_ _
_ _
# Available Countries
> Buying balance is currently only supported in the US





_ _
_ _
*Last edit: 13.11.2023*