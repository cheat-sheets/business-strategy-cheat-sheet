# Business Strategy Cheat Sheet

Business Strategy involves analysis of how businesses and organizations behave in situations in which strategic 
decisions are interdependent, i.e. where my actions affect my competitors' profits and vice versa. Using the basic 
tools of [game theory](https://github.com/cheat-sheets/game-theory-cheat-sheet), it analyses how businesses choose 
strategies to attain competitive advantage.

## Table of Contents

- [The Basics](#the-basics)
- [Cooperation](#cooperation)
- [Complementary Products](#complementary-products)
  - [Strategic Partnerships](#strategic-partnerships)
- [Market Entry Strategy](#market-entry-strategy)
- [Research and Development](#research-and-development)
- [Product Differentiation](#product-differentiation)
- [Customer Switching Costs](#customer-switching-costs)
- [Price Discrimination](#price-discrimination)
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

## Complementary Products

Two products A and B are complementary if the demand for B increases when the price of A drops, and vice versa.
Examples: Computers & Software, Skis & Skiing Sticks, Smartphones & Apps. This phenomenon is referred to as 
**negative cross-price elasticity**.

**Cross-price elasticity of demand** measures the responsiveness of the quantity demanded for a good to a change in the 
price of another good, [ceteris paribus](https://en.wikipedia.org/wiki/Ceteris_paribus). It is measured as the 
percentage change in quantity demanded for the first good that occurs in response to a percentage change in price of 
the second good. For example, if, in response to a 10% increase in the price of fuel, the demand for new cars 
that are fuel inefficient decreased by 20%, the cross elasticity of demand would be: -2.

It may make sense to support the supplier of the complement - Better quality of complement and 
higher sales of complement is beneficial for own product. 

Examples:
- Apple gave laptops to students writing software for Mac OS. More compatible software titles made Apple's 
laptops more attractive.
- Game console manufacturer 3DO made publishers pay a fee of 3 dollars to 3DO for every game copy sold. 
  - 3DO could sell consoles much cheaper and attract more customers.
  - Publishers could sell more copies and increase net profits.
  
**Producing the complement yourself**:
- Pros:
  - Market for complement may be unattractive
  - Complement may require competencies the firm lacks (production, R&D, management,...)
  - Prospective customers might be put off by firm’s dominant position
- Cons:
  - Better tailoring of complement to own product
  - Quality control for complement
  - Internalisation of the positive effects of the complement on own product

**Strategies related to complements**
- **Cross subsidies** - charging higher prices to one type of consumers to artificially lower prices for another group.
	- Razors and blades, Mobile phones and operator contracts, Printers and cartridges.
- **Bundling** - sell main product and complement as a bundle.
- **Lock-in** - complement can only be used with main product of certain producer. Users have switching costs when 
switching from A to a substitute. The more complements (B, C, ...) to A they buy, the higher the switching cost.
Higher switching costs imply a higher value of the customer to the firm.

Sometimes two firms can be **both competitors and complementors**. 
For example, Sony and Apple. Both produce mp3 players. Sony uses iTunes store to sell music they produce.

### Strategic Partnerships

Sometimes firms don't want to merge, because they want to maintain control or only part of business is complementary.
In this case a strategic partnership can be used:

- Producers of complementary goods dependent on each other.
- Helping each other and coordinating each other's behaviour maximizes the positive effects of complementarity.
- In many cases, integration into one single company not feasible or not desired by involved firms.
- Forming a strategic partnership is a powerful way of institutionalizing coordination and formalising interests.

A strategic partnership is characterised by:

- Shared decision making
- Organizational integration 
  - Teams across firms
  - Established reporting and decision routines across firms
  - Heavy exchange of information
- Economic integration
  - Joint equity ownership 
  - A new legal entity (joint venture)

## Market Entry Strategy

### Attractiveness of New Market Entry

[**Porter's Five Forces**](https://en.wikipedia.org/wiki/Porter%27s_five_forces_analysis):

- **Threat of new entrants**
  - The existence of barriers to entry (patents, rights, etc.). The most attractive segment is one in which entry 
  barriers are high and exit barriers are low.
  - Government policy such as sanctioned monopolies or legal franchise requirements.
  - Capital requirements - clearly the Internet has influenced this factor dramatically. Web sites and apps can be launched cheaply and easily as opposed to the brick and mortar industries of the past.
  - Economies of scale
  - Product differentiation
  - Brand equity
  - Customer loyalty to established brands
  - Industry profitability (the more profitable the industry, the more attractive it will be to new competitors)
  - Network effect 
- **Threat of substitutes** (products that use a different technology to try to solve the same economic need)
  - Buyer propensity to substitute
  - Relative price performance of substitute
  - Buyer's switching costs
  - Number of substitute products available in the market
  - Availability of close substitute
- **Bargaining power of customers**
  - Buyer concentration to firm concentration ratio
  - Degree of dependency upon existing channels of distribution
  - Buyer switching costs
  - Buyer information availability
  - Buyer price sensitivity
- **Bargaining power of suppliers**
  - Supplier switching costs relative to firm switching costs
  - Degree of differentiation of inputs
  - Presence of substitute inputs
  - Employee solidarity
- **Competitive rivalry**
  - Sustainable competitive advantage through innovation
  - Level of advertising expense
  - Powerful competitive strategy which could potentially be realized by adhering to Porter's work on low cost 
  versus differentiation

### Structural Entry Barriers

- Control of essential resources
- Natural resources: DeBeers / diamonds
- Supplier capacity: Minnetonka / liquid soap
- Patents: Sony and Philips / CD
- Distribution channel: Coca Cola / fast food chains
- Location: Supermarkets / top locations
- Timing: Airlines / Arrival slots at airports
- Rationing by governments: Cabs, mobile phone networks
- Economies of scale and scope
  - Minimum efficient scale: Semiconductor production
  - Cost advantages of incumbents through experience or economies of scope: Airframe production
- Marketing advantages of incumbents
  - Brand loyalty: Frequent flyer programs
  - Switching costs: Network markets such as mobile telephony

### Strategic Entry Barriers

In business, strategic entry deterrence refers to any action taken by an existing business in a particular market 
that discourages potential entrants from entering into competition in that market. Such actions, or barriers to entry, 
can include hostile takeovers, product differentiation through heavy spending on new product development, 
capacity expansion to achieve lower unit costs, and predatory pricing. These actions are sometimes deemed 
anti-competitive and could be subject to various competition laws.

**Commitment**:

New entrant makes a commitment that makes him impossible to exit the market if incumbent retaliates.

Types of commitment
- High sunk cost investments
  - Production capacity
  - R&D
  - Advertising
- Exit from other strategic market segments and focus on entry.

**Judo Strategy**:

Entrant:
- Sets a price lower than the incumbent's price
- Limits its capacity to serve a small proportion of the market
- Signals the incumbent that it does not increase its capacity drastically in the future

Incumbent:
- Loses some profits by giving market share to the incumbent
- Can exclude the entrant and fight back the whole market by setting itsown price marginally lower than the entrant's 
one 
- Incurs (in the short run) losses through this price reduction 

Example: Amazon vs. Barnes & Noble
- Amazon enters into the online book retail in 1994
- Barnes & Noble (leading US book retailer) does not respond with an own online store even though 
potential to exclude Amazon
- Fear that online store would trigger an online price war and cannibalizing sales through classical bookstores
- Amazon gradually dragging customers away from classical bookstores

**Niche Market** - a subset of the market on which a specific product is focused. The market niche defines the product 
features aimed at satisfying specific market needs, as well as the price range, production quality and the demographics
 that it is intended to target. It is also a small market segment.

- The entrant focuses on a niche market
- Across the board retaliation may not be feasible for incumbent 

**Limit Pricing**:

A limit price is the price set by a monopolist to discourage economic entry into a market, and is illegal in many 
countries. The limit price is the price that the entrant would face upon entering as long as the incumbent 
firm did not decrease output. The limit price is often lower than the average cost of production or just 
low enough to make entering not profitable. The quantity produced by the incumbent firm to act as a deterrent to 
entry is usually larger than would be optimal for a monopolist, but might still produce higher economic profits 
than would be earned under perfect competition.

The problem with limit pricing as a strategy is that once the entrant has entered the market, 
the quantity used as a threat to deter entry is no longer the incumbent firm's best response. 
This means that for limit pricing to be an effective deterrent to entry, the threat must in some way be made credible. 
A way to achieve this is for the incumbent firm to constrain itself to produce a certain quantity whether 
entry occurs or not. An example of this would be if the firm signed a union contract to employ a 
certain (high) level of labor for a long period of time. In this strategy price of the product becomes the 
limit according to budget.

**Predatory pricing**:

Predatory pricing, also known as aggressive pricing (also known as "undercutting"), intended to drive out competitors 
from a market. It is illegal in some countries.

Companies or firms that tend to get involved with the strategy of predatory pricing often have the goal to place 
restrictions or a barrier for other new businesses from entering the applicable market. It is an unethical act 
which contradicts anti–trust law, attempting to establish within the market a monopoly by the imposing Company. 
Predatory pricing mainly occurs during price competitions in the market as it is an easy way to obfuscate the 
unethical and illegal act. Using this strategy, in the short term consumers will benefit and be satisfied with 
lower cost products. In the long run, firms often will not benefit as this strategy will continue to be used by 
other businesses to undercut competitors margins, causing an increase in competition within the field and 
facilitating major losses. This strategy is dangerous as it could be destructive to a firm in terms of losses 
and even lead to complete business failure.

Other pricing strategies: https://en.wikipedia.org/wiki/Pricing_strategies#Models_of_pricing.

**Preemption**:

The incumbent can preempt an entry by
- (Over-) investing to reduce variable costs of production below the level that would be optimal without threat of entry
- Pursuing horizontal product differentiation with greater product variety than would be optimal without threat of entry
- Choosing locations of outlets more densely than would be optimal without threat of entry

Other strategies to deter new entrants: https://en.wikipedia.org/wiki/Strategic_entry_deterrence

# Research and Development

- **Basic Research** - development of scientific knowledge that is applicable to wide range of potential uses.
- **Applied Research** - application of scientific knowledge to the solution of a specific problem, development of a 
new product or process.
- **Product Development** - identification of the relevant consumers, tailoring of the product / process to the needs 
of these consumers.

Results of Applied Research and Product development can be protected by patents or copyright.

### Incentive to innovate

- 100 consumers, 60 are willing to pay $500, 40 are willing to pay $400
- Production cost of 1 unit is $300
- Monopolist: **Value of innovation $8,000** . Monopolist sets the price $500 and makes 60 * ($500 - $300) = $12,000, 
with innovation $400 is more profitable: 60 * ($400 - $200) = $12,000. 
- Competitive market: **Value of innovation $10,000**. Everyone makes marginal profits, with innovation the innovator 
gets 100 * ~$100 = ~10,000.
- Monopolist with threat of entry: 
  - **Value of innovation for monopolist $15,000**. If new entrant innovates, the market will be split 50/50 and 
  previous monopolist will be making 50 * ($400 - $300) = $5,000. 
  - **Value of innovation for entrant $20,000**. If new entrant innovates, the market will be split 50/50 and entrant
  will be making 50 * ($400 - $200) = $10,000. 

From the above:
- **Replacement Effect** - for a given market structure, a monopolist has less incentive to innovate because of 
the higher level of pre-innovation profits.
- **Efficiency Effect** - under the threat of entry, a monopolist has higher incentives to innovate than a 
potential entrant into the market.

**Sleeping patents** - patents that prevent other firms to create similar products (example: Xerox).

## Product Differentiation

[**Bertrand paradox**](https://en.wikipedia.org/wiki/Bertrand_paradox_(economics)) describes a situation in which 
two firms reach a state of Nash equilibrium where both firms charge a price equal to marginal cost. The paradox
is that in real life it doesn't happen i.e. firms make money. The explanation is that the assumptions used in the 
Bertrand model are not true in real life: 

- Identical products: In reality, consumers have different taste and products are differentiated.
- Game played once: In reality, game has indefinite repetitions - cooperation is possible.
- Market transparency: In reality, imperfect market transparency.
- Infinite price elasticity: In reality, costs for consumers associated with switching seller (loyalty programs)
- No capacity constraints: In reality, companies have limited capacity (No incentive to induce a price war
over the complete demand)

**Vertical differentiation** - given equal prices, every consumer would choose product A over product B 
(e.g. iPhones with different storage size).

**Horizontal differentiation** - given equal prices, some consumers would choose product A whereas others 
would choose product B (e.g. iPhones of different color).

Differentiation fixes Bertrand paradox - firms take different segments of the market and don't compete in prices.

Strategies of taking share of the market:

- **Cost Leadership** - low-cost relative to competitors as strategic main theme:
  - Efficient-scale facilities
  - Rigorous cost reductions from experience
  - Avoidance of marginal customer accounts
  - Cost minimization in areas like R&D, service, sales force and advertising 
- **Differentiation** - differentiating the product or service, offering something that is perceived industry-wide 
as being unique. Dimensions:
  - Design or brand image
  - Technology
  - Customer service
  - Dealer networks
- **Focus** - focus on particular buyer group, segment of the product line or geographic market. 
Central rationale: Serving narrow strategic target group more effectively or efficiently than competitors.

## Customer Switching Costs 

Acquiring new customers is more expensive than keeping old customers. Firms can invest in loyalty programs to lock-in 
customers and make it less appealing for them to switch to a competitor.

New suppliers can give "goodies" (discounts, free flights) to their customers to give the incentive to switch. 
Switching costs for customers include:

- Risk that the new supplier is not a reliable replacement, E.g. uncertainty about qualification of new car repair center
- Costs of exchanging suppliers, e.g. cost of moving apartment, administrative costs if "supplier" is an employee
- Learning costs with new supplier 
- Loyalty programs and accumulated quantity discounts
- Psychological "costs" through change of contact person, e.g. missing the friendly welcome at your favorite restaurant
- Replacement of complementary goods for the product

- **When will a customer switch to a new supplier?**

C <= U + G, where C - customer switching costs, U - utility increase from switching, G - switching "goody" 
from new supplier.

- **How much should a new supplier invest to make a customer switch?**

S <= P - G, where S - supplier's switching costs, P - profit increase from new customer, G - switching "goody"
given to the new customer.

- **How can a supplier increase customer switching costs?**

	- Loyalty programs
	- Long-term contracts
	- Sale of complementary products 
	- Specific software / data formats
	- Specific interfaces
	- Close personal customer service

- **How can customers decrease their switching costs?**
	- Use anticipated switching costs to negotiate a price reduction before supplier lock-in
	- Use a second supplier / second sourcing (e.g. IBM purchases processors from Intel and AMD)
	
## Price Discrimination

**Price discrimination**: is the practice of transacting the same product at different prices to capture more market 
segments, e.g. set lower 
prices for students. Can be combined with product differentiation when different product versions have different price. 

- 1st degree discrimination - different price for each consumer.
- 2nd degree discrimination - firms construct prices so that consumers "self-select". Types:
  - Nonlinear pricing
  - Versioning
  - Bundling 
- 3rd degree discrimination - firms observe consumer characteristics that allow them to infer WTP (willingness to pay) 
and price accordingly. Consumer characteristics can include geography, timing, job.

**Product differentiation vs price discrimination**:

![Product differentiation vs price discrimination](./assets/product_differentiation_price_discrimination.png)


## Resources

- Competitive Strategy: course on Coursera https://www.coursera.org/learn/competitive-strategy
- Advanced Competitive Strategy: course on Coursera https://www.coursera.org/learn/advanced-competitive-strategy
