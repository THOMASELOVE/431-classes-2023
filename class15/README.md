# 431 Class 15: 2023-10-17

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
15 | 2023-10-17 | **[Slides 15](https://thomaselove.github.io/431-slides-2023/class15.html)** | [Code 15](https://thomaselove.github.io/431-slides-2023/class15.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements

1. There is a Minute Paper after Class 15, due Wednesday 2023-10-18 at noon. We'll post it **by class time**.
2. Today's class makes substantial use of [the pwr package in R](https://github.com/heliosdrm/pwr) to address some issues related to power and sample size calculations associated with assessing differences in population means, or in population proportions.
    - Sections 22 and 27 of our Course Notes are particularly relevant.
    - Another resource to consider is [A Practical Guide to Statistical Power and Sample Size Calculations in R](https://cran.r-project.org/web/packages/pwrss/vignettes/examples.html) which uses the `pwrss` package instead, and which looks very promising.
3. On Thursday, we will discuss statistical significance and p values further. Here are three things you might want to glance at before that session:
    - "[Not even scientists can easily explain p values](https://fivethirtyeight.com/features/not-even-scientists-can-easily-explain-p-values/)" by Christie Aschwanden at FiveThirtyEight.
    - [Statistical Inference in the 21st Century: A World Beyond p < 0.05](https://amstat.tandfonline.com/toc/utas20/73/sup1) from 2019 in *The American Statistician*.
    - The American Statistical Association’s 2016 [Statement on p-Values: Context, Process and Purpose](http://amstat.tandfonline.com/doi/full/10.1080/00031305.2016.1154108).

## Project A Proposals

- Updated Project A Proposal Status [is available here](https://github.com/THOMASELOVE/431-classes-2023/blob/main/projA/projectA_proposal.md).
- Some trivia and interesting details from [the 45 Project A Proposals are available, too](https://github.com/THOMASELOVE/431-classes-2023/blob/main/projA/projectA_plans.md).

## Four Common Issues with the Project A Proposals

- A problem lots of people had (which I mostly didn't mention, but will look for more closely in the portfolios) is that in the codebook (Section 11) you need to specify the years when the data were actually collected by County Health Rankings for your chosen outcome and predictor variables. Look [here for those details](https://www.countyhealthrankings.org/explore-health-rankings/county-health-rankings-measures).
- Try to get through all of Project A without using the word "significant". The reasons why will be clearer after next Thursday's class.
- **12** of the 45 proposals had a problem because they used something other than `date: last-modified` in their YAML. Please correct your YAML in your portfolio (we'll be looking for this.)
    - Groups in this situation were: G062, G181, G201, G261, G271, G301, G321, G371, G412, G471, G501, and G511.
- **29** of the 45 proposals neglected (at least once) to include a blank line before and after every code chunk, every header (or subheader) and every paragraph. Again, we'd really like you to fix this by the time you submit your portfolio.
    - Groups in this situation included: G032, G042, G051, G081, G092, G111, G121, G151, G161, G181, G221, G242, G252, G281, G301, G311, G342, G352, G382, G391, G412, G431, G451, G471, G492, G501, G511, G531, G561
- Project group codes are specified on the [Project A Proposal Status page](projectAproposal.md)

### Styling Your Code

You may be interested in [the styler package](https://github.com/r-lib/styler), which can be used on existing Quarto (or R or R Markdown) code to adapt it to [the tidyverse style guide](https://style.tidyverse.org/).

- This wouldn't resolve misspellings (hit F7 in RStudio) or the `date` or blank line issues mentioned above, but is still of some use.

## One Last Thing

[Teaching the Difficult Past of Statistics to Improve the Future](https://www.tandfonline.com/doi/full/10.1080/26939169.2023.2224407) by Lee Kennedy-Shaffer is an interesting paper. Here's the abstract:

> In recent years, the discipline of statistics has begun reckoning with its difficult history. Institutions are reconsidering names that have honored key historical figures in statistics who have deep ties to eugenics movements and racial and class prejudice. These names, however, continue to appear in our classrooms, where we teach the methods created by these individuals, raising the question of how instructors should address their legacies. Three examples of famous statisticians and their work—Francis Galton’s use of conditional probabilities to demonstrate “hereditary talent,” Karl Pearson’s attempt to quantify the intelligence of Jewish immigrant students, and Ronald A. Fisher’s creation of the analysis of variance to de-emphasize environment in human development—highlight the intimate ties between statistics and eugenics. These examples, along with a discussion of the context of these men, eugenics movements, and the statisticians and scientists who opposed their eugenic programs, can humanize the field for students, teach them about the challenges in accurate and unbiased data collection and analysis, and connect historical mistakes to contemporary ethical issues. Confronting this history in the classroom can both improve the teaching of the statistical methodologies themselves and begin a broader conversation about the role of statistics in the world.
