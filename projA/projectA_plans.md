# Some Details from the Project A Plans

## Two Common Problems

Of the 45 submitted project proposals,

- **12** had a problem because they used something other than `date: last-modified` in their YAML. Please correct your YAML in your portfolio (we'll be looking for this.)
    - Groups in this situation were: G062, G181, G201, G261, G271, G301, G321, G371, G412, G471, G501, and G511.
- **29** neglected (at least once) to include a blank line before and after every code chunk, every header (or subheader) and every paragraph. Again, we'd really like you to fix this by the time you submit your portfolio.
    - Groups in this situation included: G032, G042, G051, G081, G092, G111, G121, G151, G161, G181, G221, G242, G252, G281, G301, G311, G342, G352, G382, G391, G412, G431, G451, G471, G492, G501, G511, G531, G561
- Project group codes are specified on the [Project A Proposal Status page](projectAproposal.md)
- You may be interested in [the styler package](https://github.com/r-lib/styler), which can be used on existing Quarto (or R or R Markdown) code to adapt it to [the tidyverse style guide](https://style.tidyverse.org/).
    - This wouldn't resolve misspellings (hit F7 in RStudio) or the `date` or blank line issues mentioned above, but is still of some use.

## Which states were selected?

45 projects, so we have 45 selecting **OH**, naturally.

Count | State(s) | -- | Count | State(s) | -- | Count | State(s) | -- | Count | State(s)
----: | :-----: | -- | ----: | :-----: | -- | ----: | :-----: | -- | ----: | :-----: 
17 | IL | -- | 12 | TX | -- | 7 | WA | -- | 3 | KS, TN
16 | MI, NY | -- | 10 | PA | -- | 6 | KY, MD, NJ | -- | 2 | AR, ID, OR, SC, WY
15 | FL, IN | -- | 9 | MN | -- | 5 | AL, GA, IA, WV | -- | 1 | ND, NE, NM, OK, UT
14 | CA | -- | 8 | NC, WI | -- | 4 | CO, MD, MS, VA | -- | 0 | MT, SD

## How many counties in your sample?

```
3 | 40 40 
3 | 84 96 98
4 | 02 19 21 41 42                                      N = 45
4 | 50 56 70 71 76 80 94 94 99                          MEAN = 519.2 SD = 97.5
5 | 04 05 05 13 14 24 24 37 45 48                       MEDIAN  = 513
5 | 52 58 68 72 78 83 89 96 99                          QUARTILES: (453, 578)
6 | 11 21 31 39
6 |
7 | 
7 |
8 | 00 00
```

## Analysis 1 Selections 

Projects | Analysis 1 Outcome
:-: | :--------------------------------------------------------------------------------------------
7 | Diabetes prevalence
6 | Adult obesity, Poor mental health days
5 | Adult smoking, Premature death
4 | Poor or fair health
3 | Premature age-adjusted mortality
2 | Flu Vaccinations
1 | Air pollution - particulate matter, Broadband Access, Excessive drinking, Income inequality, <br /> Mammography screening, Poor physical health days, Social associations

Projects | Analysis 1 Predictor
:-: | :--------------------------------------------------------------------------------------------
6 | Adult smoking
5 | Median household income
4 | Insufficient sleep, Unemployment
3 | Excessive drinking, Physical inactivity, Rural, Uninsured
2 | Adult obesity, Age 65 and older, High School Completion
1 | Diabetes prevalence, Driving alone to work, Food environment index, Income inequality, <br /> Not proficient in English, Poor or fair health, Poor physical health days, Social associations

## Analysis 2 Selections

Projects | Analysis 2 Outcome
:-: | :--------------------------------------------------------------------------------------------
9 | Premature age-adjusted mortality
6 | Diabetes prevalence
4 | Adult obesity, Excessive drinking, Poor or fair health
3 | Poor mental health days, Poor physical health days, Premature death
2 | Food insecurity, Insufficient sleep, Physical inactivity
1 | Air pollution - particulate matter, Flu vaccinations, Social associations

Projects | Analysis 2 Predictor
:-: | :--------------------------------------------------------------------------------------------
8 | Unemployment
5 | Food insecurity, Median Household Income
3 | Adult obesity, Adult smoking, High School Completion, Income Inequality
2 | Age 65 and older, Excessive drinking, Insufficient sleep, Physical Inactivity, Rural
1 | Gender Pay Gap, Non-Hispanic White, Poor physical health days, Social associations, <br /> Uninsured

Predictor | Cutpoints for the Most Common Analysis 2 Predictors
:------------------: | -------------------------------------------------------------------------
Unemployment | (4.08, 4.72), (4.15, 4.79), (4.51, 5.29),  (4.60, 5.20), (4.65, 5.32), <br /> (4.68, 5.26), (4.99, 5.86), unsettled
Food insecurity | (10.5, 12.0), (10.5, 12.0), (11.8, 14.1), (12.4, 13.9), (12.4, 13.9)
Median Household Income | (49.5, 55.1), (51.2, 57.2), (53.9, 59.8), (56.6, 61.9), (58.3, 63.8)

## Analysis 3 Selections

Projects | Analysis 3 Outcome
:-: | :--------------------------------------------------------------------------------------------
8 | Insufficient Sleep
6 | Physical inactivity, Poor mental health days
5 | Adult obesity, Adult smoking, Food insecurity
4 | Excessive drinking
3 | Premature death
2 | Poor physical health days
1 | Diabetes prevalence

## Matches

- G092 and G471 have the same states (505 counties): OH IN KY MI PA WV and each uses Insufficient Sleep in Analysis 3.
- G032 and G412 have the same states (524 counties): OH IL IN MI MN WI and each uses Adult obesity in Analysis 3.
- G271 and G461 have the same states (340 counties): OH FL IL NJ WA WY but don't use the same variables in their three analyses.
- G242 and G431 have the same states (494 counties): OH IL IN MI NY PA but don't use the same variables in their three analyses.
- No two projects share the same Analysis 1 variables and Analysis 2 outcome.

## R Packages

- 35 projects loaded the "Big 5": (Hmisc, janitor, naniar, sessioninfo, and tidyverse) <br /> *these were the packages included in sample materials*
- One project each loaded (in addition to the Big 5):
    - broom and patchwork
    - broom and kableExtra and patchwork
    - gt and patchwork
    - htmlTable
    - kableExtra
    - knitr
    - mosaic
- One project loaded the Big 5 - sessioninfo + xfun
    - Another loaded the Big 5 - sessioninfo + xfun and gt
    - Finally, one loaded the Big 5 - sessioninfo + xfun and formattable and kableExtra and knitr

## Lines of Quarto Code

```
1 | 84 92
2 | 05 19
2 | 20 22 22 24 25 26 28 28 33 33 37 39 39            N: 45
2 | 40 42 43 44 47 51 53 53 54 59 59                  MEAN = 255.4, SD = 40.2
2 | 63 63 68 69 69 69 72 76 79                        MEDIAN = 251
2 | 80 89 92 95                                       QUARTILES: (228, 270.5)
3 | 10
3 | 27 34
HI: 419
```
