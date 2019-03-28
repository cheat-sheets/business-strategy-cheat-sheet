# Business Strategy Cheat Sheet

Business Strategy involves analysis of how businesses and organizations behave in situations in which strategic 
decisions are interdependent, i.e. where my actions affect my competitors' profits and vice versa. Using the basic 
tools of [game theory](https://github.com/cheat-sheets/game-theory-cheat-sheet), it analyses how businesses choose 
strategies to attain competitive advantage.

## Table of Contents

- [The Basics](#the-basics)
- [Cooperation](#cooperation)
- [Resources](#resources)

## The Basics

[Game Representations](https://github.com/cheat-sheets/game-theory-cheat-sheet#game-representations)

**Simultaneous Game** - is a game where each player chooses his action without knowledge of the actions chosen by other 
players.

**Sequential Game** - a game where one player chooses their action before the others choose theirs. 
Importantly, the later players must have some information of the first's choice, otherwise the difference in time 
would have no strategic effect.

**Dominant Strategy** - a strategy that is always better than any other strategy, 
regardless of what the other player is doing.

**Nash Equilibrium** - a set of strategies, one for each player, such that no player has incentive to change 
his strategy given what the other players are doing.

[**Prisoner's Dilemma**](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma) - a standard example of a game analyzed 
in game theory that shows why two completely rational 
agents might not cooperate, even if it appears that it is in their best interests to do so. It's a simultaneous game.

|                      | **Betray**          | **Stay silent**     |
| ---                  | ---                 | ---                 |
| **Betray**           | **-2,-2**           | 0,-3                |
| **Stay silent**      | -3,0                | -1,-1               |

- If A and B each betray the other, each of them serves 2 years in prison
- If A betrays B but B remains silent, A will be set free and B will serve 3 years in prison (and vice versa)
- If A and B both remain silent, both of them will only serve 1 year in prison (on the lesser charge).

### Toothpaste Wars

An example of a Prisoner's Dilemma is when Colgate and Sensodyne both advertise because it's a dominant strategy, 
share the market equally (the assumption here is that the size of the market stays the same regardless of whether
any company advertises):

|                          | **Advertise**           | **Don't advertise**          |
| ---                      | ---                     | ---                          |
| **Advertise**            | **$3M,$3M**             | $6M,$2M                      |
| **Don't advertise**      | $2M,$6M                 | $5M,$5M                      |

- Total market size: $10M
- Advertisement cost: $2M
- Market split when both advertise or no one advertises: 50%/50%
- Market split when one advertises and another doesn't: 80%/20%

### Chocolate Wars

- Universal Studio charges $1.0mn for a product placement in the movie 
[E.T. the Extra-Terrestrial](https://en.wikipedia.org/wiki/E.T._the_Extra-Terrestrial)
- Product placement by Mars
  - Mars' gross profits increase by $0.8M
  - Hershey's decrease by $0.1M
- Product placement by Hershey
  - Hershey's gross profits increase by $1.2M
  - Mars' decrease by $0.5M
- No product placement: "business as usual"

![Chocolate Wars](./assets/chocolate_wars.png)

Mars decided to reject the deal and lost $0.5M. If the accepted the deal they would lose only $0.2M.

### Price Wars

[Price war](https://en.wikipedia.org/wiki/Price_war) is "commercial competition characterized by the repeated cutting 
of prices below those of competitors". One competitor will lower its price, then others will lower their prices to 
match. If one of them reduces their price again, a new round of reductions starts. 
In the short term, price wars are good for buyers, who can take advantage of lower prices. Often they are not 
good for the companies involved because the lower prices reduce profit margins and can threaten their survival.

In the medium to long term, price wars can be good for the dominant firms in the industry. Typically, the smaller, 
more marginal firms cannot compete and must close. The remaining firms absorb the market share of those that 
have closed. The real losers, then, are the marginal firms and their investors. In the long term, the consumer 
may lose too. With fewer firms in the industry, prices tend to increase, sometimes higher than before the price 
war started.

## Cooperation

As can be seen from the [Prisoner's Dilemma](#toothpaste-wars) the outcome of the game can improve for both parties 
if they can cooperate. 

[**Cooperation**](https://en.wikipedia.org/wiki/Cooperation) is the process of groups of organisms working or acting 
together for common, mutual, or some underlying benefit, as opposed to working in competition for selfish benefit.

[Grim Trigger](https://en.wikipedia.org/wiki/Grim_trigger) - a trigger strategy for a repeated game. Initially, 
a player using grim trigger will cooperate, but as soon as the opponent defects (thus satisfying the trigger condition), 
the player using grim trigger will defect for the remainder of the iterated game. Grim Trigger played by all players is
a [Subgame Perfect Equilibrium](https://en.wikipedia.org/wiki/Subgame_perfect_equilibrium).

Discount Factor - a number between 0 and 1 that represents the time value of consumption and probability of continuation. 
A higher discount factor means more patience and higher chance of surviving into the next period.

**What induces cooperation**:

- Repeated games - if the game is played multiple times the payoffs are different. Assuming the Grim Trigger strategy
for both players and that 

|                      | 1st round | 2nd round | 3rd round | 4th round |
| ---                  | ---       |           | ---       | ---       |
| **Betray**           | 0         | -2        | -2        | -2        |
| **Cooperate**        | -1        | -1        | -1        | -1        |

Cooperation will be chosen if the discount factor is sufficiently high.

A [Most-Favoured-Customer Clause (MFC)](https://en.wikipedia.org/wiki/Most-Favoured-Customer_Clause) is a contractual 
arrangement between vendor and customer that guarantees the customer the best price the vendor gives to anyone. 
The MFC prevents a company from treating different customers differently in negotiations. While it may appear that 
MFCs benefit consumers because prices are lowered, views have changed in recent years (since approximately 2012). 
Authorities increasingly argue that such clauses prevent the offer of lower prices elsewhere and make the market 
entry of competitive offers considerably more difficult because they prevent new entrants from offering products at 
lower prices. It thus violates competition.

**Aggressive commitment**: eliminate those moves which lead to unattractive equilibria:

- Boeing and Airbus both think about launching a new large scale passenger airplane (Airbus: A380, Boeing: 747X).
- There is not enough market for two different models
- Airbus moves first - builds production facilities in Hamburg and Toulouse, 
these can be used for the production of the A380 only.


## Resources

- Competitive Strategy: course on Coursera https://www.coursera.org/learn/competitive-strategy
- Advanced Competitive Strategy: course on Coursera https://www.coursera.org/learn/advanced-competitive-strategy
