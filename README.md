# forward_start_option

A Forward Start Option is a type of exotic option where the strike price is not determined at the inception of the option but is instead set at a future date, known as the forward start date. This type of option is useful in situations where the underlying asset's price is uncertain at the time of the option's creation, such as in employee stock options or certain hedging strategies.


Underlying Asset (S): The asset on which the option is based (e.g., a stock, index).
Initial Price (S_0): The price of the underlying asset at the inception of the option.
Forward Start Date (t_start): The future date at which the strike price is set based on the underlying asset's price at that time.
Strike Price (K): The price at which the option can be exercised, determined on the forward start date.
Maturity Date (T): The date when the option expires, typically set some time after the forward start date.
Call Option: Gives the holder the right to buy the underlying asset at the strike price.
Put Option: Gives the holder the right to sell the underlying asset at the strike price.

Once the strike price is set at the forward start date t_start, the option functions like a standard European option, with the payoff determined at maturity T.

Call Option Payoff:
The payoff at maturity T is:
Payoff_call = max(S_T - K, 0)
Where:
S_T is the price of the underlying asset at maturity.
K is the strike price set at the forward start date t_start.

Put Option Payoff:
The payoff at maturity T is:
Payoff_put = max(K - S_T, 0)
