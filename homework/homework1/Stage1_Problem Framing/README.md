
# Project Title
**Stage:** Problem Framing & Scoping (Stage 01)

## Problem Statement
<1–2 paragraphs: what problem & why it matters>
This projects aims to understand impact of a newly planned hedging program on our general account. As a large life insurance company, many of our liabilities include a guaranteed rate of 5% on our most popular Universal life product. This opens our company to large losses in a low rate environment as seen in the past decade. While rates are elevated, it is necessary to analyze and understand the benefit of new hedging program in different rate environments and its impact. 

## Stakeholder & User
<Who decides? Who uses the output? Timing & workflow context>
Primary users will be office of the general account and C-suite executives such as the CFO. The program will need to be presented and understood by all parties for approval to be given by the board. This matters as the past 10 years, riskier investments have been required to meet minimum guarantees. In addition, it will allow more competitive rates. Timing will need to be kept annual, or even more frequently to understand the health of the program, and its overall impacts to the top & bottom line.


## Useful Answer & Decision
<Descriptive / Predictive / Causal; metric; artifact to deliver>

Descriptive- Clear dashboards of impact of interest rate hedging currently, with additional paths showing present value of future surplus in a 30 year projetion period. This includes looking at a stochastic analysis impact, and a deterministic analysis.

Predicitive- Forecasts future impact on average of 2500 stochastic scenarios, and current forecast. 

Casual-Impacts of interest rates and current layout of general account portfolio will change the overall imapct of the hedging program. 

## Assumptions & Constraints
<Bullets: data availability, capacity, latency, compliance, etc.>
Current data availability is strong as interal data is held consistent for regulatory purpose. 
Capatcity issues arise as right answer may need to be tested multiple times, which include multiple runs which is costly.
Latency factors of future interest rate movements is unknown, even stochastic run needs to imply some future direction and speed of rates.
Factors above will need to be sensitivity tested to allow comfort in realiability of results.


## Known Unknowns / Risks
<Bullets: what’s uncertain; how you’ll test or monitor>

Future direction of rates is the largest risk which is always unknown. The stochastic modeling can allow multiple scenarios to be tested and understood for users understanding. For example, we can paint a picture around where the hedging program would hurt us the most, i.e. high interest rate environments. This can allow ample time to understand and deliver next steps. 

## Lifecycle Mapping
Goal → Stage → Deliverable
- <Goal A> → Problem Framing & Scoping (Stage 01) → <Deliverable X>

1- Utilize current mainframe to alter and include new hedging program to understand interest rate risk. (Goal)
2- Create set baseline of current environment, testing if results are compliant with a Subjet Matter Experts understanding. (Stage)
3-Continue improvements and updates to the model to account for ever changing portfolio position and management actions. (Stage)
4-Formulate a consistent template of results to present to board on progress, material impacts, and  storytelling. (Deliverables)

## Repo Plan
/data/, /src/, /notebooks/, /docs/ ; cadence for updates
