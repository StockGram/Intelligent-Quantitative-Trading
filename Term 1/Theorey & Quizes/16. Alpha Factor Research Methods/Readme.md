# Alpha Factor Research Methods

## Research Paper 1 : [Overnight Returns and Firm-Specific Investor Sentiment](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2554010)

### Abtract
We explore the possibility that overnight returns can serve as a measure of firm-specific investor sentiment by analyzing whether they exhibit characteristics expected of a sentiment measure. First, we document short-term persistence in overnight returns, consistent with existing evidence of short-term persistence in share demand of sentiment-influenced retail investors. Second, we find that short-term persistence is stronger for harder-to-value firms, consistent with evidence that sentiment plays a larger role when there is less objective data available for valuation. Third, we show that stocks with high (low) overnight returns underperform (outperform) over the longer-term, consistent with evidence of temporary sentiment-driven mispricing.  

### p 1
The recent work of Berkman, Koch, Tuttle, and Zhang (2012) suggests that a stock’s
overnight (close-to-open) return can serve as a measure of firm-level sentiment.

### p 2
Specifically, Berkman et al. (2012) find that attention-generating events (high absolute returns or
strong net buying by retail investors) on one day lead to higher demand by individual investors,
concentrated near the open of the next trading day...This creates temporary price pressure at the
open, resulting in elevated overnight returns that are reversed during the trading day.

### p 3
We conduct three sets of analyses. **In the first
we test for short-run persistence in overnight returns.** The basis for expecting this from a
measure of sentiment is the evidence in Barber et al. (2009) that the order imbalances of retail
investors, who are the investors most likely to exhibit sentiment, persist for periods extending
over several weeks...In the third analysis we
examine whether stocks with high overnight returns underperform those with low overnight
returns over the long term.

Exercise on overnight returns can be found [here](https://github.com/purvasingh96/AI-for-Trading/blob/master/Term%201/Theorey%20%26%20Quizes/16.%20Alpha%20Factor%20Research%20Methods/Quizzes/overnight_returns.ipynb)

## Research Paper 2 : [The Formation Process of Winners and Losers in Momentum Investing](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2610571)

### Abstract:
Previous studies have focused on which stocks are winners or losers but have paid little attention to the formation process of past returns. This paper develops a model showing that past returns and the formation process of past returns have a joint effect on future expected returns. The empirical evidence shows that the zero-investment portfolio, including stocks with specific patterns of historical prices, improves monthly momentum profit by 59%. Overall, the process of how one stock becomes a winner or loser can further distinguish the best and worst stocks in a group of winners or losers.

<img src="./Images/1. trajectory.png" width=450 height=300></img> <img src="./Images/2. relative trajectory.png" width=450 height=300></img>

### p. 1
Intermediate-term (3–12 months) momentum has been documented by Jegadeesh and Titman (1993, 2001, hereafter JT), while short-term (weekly) and long-term (3–5 years) reversals have been documented by Lehmann (1990) and Jegadeesh (1990) and by DeBondt and Thaler (1985), respectively. Various models and theories have been proposed to explain the coexistence of intermediate-term momentum and long-term reversal. However, most studies have focused primarily on which stocks are winners or losers; they have paid little attention to how those stocks become winners or losers. This paper develops a model to analyze whether the movement of historical prices is related to future expected returns.

### p. 2
This paper captures the idea that past returns and the formation process of past returns have a joint effect on future expected returns. We argue that how one stock becomes a winner or loser—that is, the movement of historical prices—plays an important role in momentum investing. Using a polynomial quadratic model to approximate the nonlinear pattern of historical prices, the model shows that as long as two stocks share the same return over the past n-month, the future expected return of the stock whose historical prices are convex shaped is not lower than one whose historical prices are concave shaped. In other words, when there are two winner (or loser) stocks, the one with convex-shaped historical prices will possess higher future expected returns than the one with concave-shaped historical prices.

### p. 3 
To test the model empirically, we regress previous daily prices in the ranking period on an ordinal time variable and the square of the ordinal time variable for each stock. The coefficient of the square of the ordinal time variable is denoted as gamma.