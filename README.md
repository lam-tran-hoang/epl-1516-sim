# Simulating the English Premier League season 2015/16
## Introduction
The English Premier League is known for its competitiveness and big money. The value of a place in the top tier of English football has teams constantly battle out every match and always on the lookout for the best players. Although some of the teams have risen to dominate the league (i.e. the Big Four and more recently the Big Six), there is still room for upsets when smaller teams are pushed to the verge of relegation, or when newly-promoted teams provide surprise packages to the league. However, the degree of such surprise had never been to the extreme of **Leicester City winning the league in 2016** while exactly one year ago they were battling to avoid relegation.
#### The Expected Goal
In football, **expected goal (xG)** is a fairly recent metric to measure over/under-performance. It measures the quality of a shot based on several variables such as assist type, shot angle and distance from goal, whether it was a headed shot and whether it was defined as a big chance. Summing the xG of a team within a match gives us a rough number of **how many goals that team is expected to score**.

For example, the match between Leicester (home) and Manchester United (away) has the xG scoreline of **0.88-1.06**. The match ended 1-1, which is a fair outcome given their xG stats. Season-wise, Leicester scored 68 goals with the xG of 68.42, however, they conceded just 36 goals with a xGA (expected goal against) of 45.02. In other words, *Leicester conceded 9.02 goals less than expectations*. For context, Leicester was praised for their defensive work and fast counter-attacks throughout that season, but with **league title rival Arsenal proving to be the most wasteful in the league**, *scoring 8.53 goals less than expectations*, the probability of Leicester winning the league that season could be considerably low. By simming the seasons with xG, we could see how (un)likely Leicester win was and which teams should have achieved more (or less) in 2015/16.
# Methodology
Monte Carlo and the Poisson distribution

# Data source
Understat Kaggle
