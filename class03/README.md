# 431 Class 03: 2023-09-05

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
03 | 2023-09-05 | **[Slides 03](https://thomaselove.github.io/431-slides-2023/class03.html)** | [Code 03](https://thomaselove.github.io/431-slides-2023/class03.qmd)  | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements
 
1. Your first assignment is a [Minute Paper after Class 03](https://bit.ly/431-2023-minute-3), which you need to complete by NOON Wednesday 2023-09-06 (tomorrow). A Minute Paper is a short survey (completed using a Google Form) where you will answer a few questions about how the course is going for you.
    - You'll need to be logged into Google via CWRU to complete the Minute Papers. 
    - **Always** complete the Minute Paper even if you weren’t able to attend the most recent class. 
    - More on the Minute Papers [here](https://github.com/THOMASELOVE/431-minute-2023), and [in the Syllabus](https://thomaselove.github.io/431-syllabus-2023/10_assignments.html#minute-papers).

2. If you’ve spent 15 minutes working on something and are stuck, don’t keep working on it. Step away for a while, and if you return and are still stuck, **ASK FOR HELP**.
    - Use our [Campuswire discussion board](https://thomaselove.github.io/431-2023/campuswire.html) to ask (and answer) questions about the course. Open 24 hours a day, 7 days a week.
    - Attend [TA office hours](https://thomaselove.github.io/431-2023/contact.html) (which begin this afternoon) to get one-on-one help or share a computer problem. Our Shared Google Drive (431 Fall 2023 Dr Love and Students) contains Zoom links for TA office hours in a document called **TA office hours schedule and Zoom links**. No appointment is necessary. Please just drop in.
    - Professor Love will also hold "drop-in" office hours before and after each class.
    - Email Professor Love if you have any questions you don't feel comfortable asking in TA office hours or via Campuswire.

3. In our Shared Drive, you'll find a document called **A Few Comments on the Welcome to 431 Survey**, which we'll discuss briefly today.

4. I continue to threaten to show a [video from Hans Rosling](https://www.gapminder.org/fw/world-health-chart/). If I don't get to it today, I encourage you to watch it yourself (it's about 4 minutes long). 
    - The updated [World Health Chart from Gapminder](https://www.gapminder.org/fw/world-health-chart/) may be of particular interest, and includes links to the [original video](https://www.youtube.com/watch?v=jbkSRLYSojo&feature=emb_imp_woyt) I planned to show to you, and the shorter update I will show today.
    - Some related thoughts, plots and links to data can be found in [Health, Wealth and Education: Is There a Link for Countries?](https://www.stlouisfed.org/open-vault/2021/july/health-wealth-education-link-countries) posted in July 2021 by Heather Hennerich.

5. Now is the time (if you haven't already) to [get started on Lab 01](https://github.com/THOMASELOVE/431-labs-2023), which is due Tuesday 2023-09-12 at Noon. 
    - While you don't need to develop a Quarto file for Lab 01, you do need to use R and R Studio a bit. We have provided you with a template for Lab 1 to help you get started.
    - You also need to have read at least the introduction (and ideally, Chapter 1) of Spiegelhalter's *The Art of Statistics*.

## Ten Interesting/Fun Facts about Students in this semester's 431 class

1. I have a tattoo that glows under UV light
2. I love to sing and used to sing with the Cleveland Orchestra Chorus!
3. I play drums in a local band.
4. I played college football during my undergrad.
5. I was trained in opera vocal performance.
6. I worked as a crime scene investigator and forensic scientist for 7 to 8 years
7. My family makes maple syrup here in geauga county
8. I love gardening! Started to learn about botany this summer as well to get better at gardening and just expand my general knowledge.
9. This is now the third year I've biked with Case's VeloSano team, a cancer research fundraiser with Cleveland Clinic.
10. I tried out for the Canadian National Team for Tae Kwon Do in 1987

## Extra Materials for Class 03 found in the [Class 03 data subfolder](https://github.com/THOMASELOVE/431-classes-2023/tree/main/class03/data)

These items are also part of the updated [431-data page](https://github.com/THOMASELOVE/431-data).

- [431-first-r-template.qmd](data/431-first-r-template.qmd) is the **template** I will start with in developing today's materials.
- [431-class03-all-code.qmd](data/431-class03-all-code.qmd) is a revision of the template that includes all of the code I will develop today in [the slides](https://thomaselove.github.io/431-slides-2023/class03.html).
- [quick_survey_2023.csv](data/quick_survey_2023.csv) contains the data from our [Quick Survey in Class 02 (pdf)](https://github.com/THOMASELOVE/431-classes-2023/blob/main/class02/431_surveyhandout_1perstudent_2023-08-31.pdf) for you and for students in the 2014-2022 versions of 431.

### Analytic Questions We'll Address Today

1. What is the distribution of pulse rates among students in 431 since 2014?
2. Does the distribution of student heights change materially over time?
3. Is a Normal distribution a good model for our data?
4. Do taller people appear to have paid less for their most recent haircut?
5. Do students have a more substantial tobacco history if they prefer to speak English or a language other than English?

### R Tools We'll Demonstrate Using Today's Materials

In addition to demonstrating general approaches for creating R projects and Quarto files, and loading R packages, we'll demonstrate most (if not quite all) of the following key ideas...

1. Ingesting data with `read_csv` from a csv (comma-separated version text) file to create a tibble (data frame.)
2. Six key verbs from the `tidyverse`: `count`, `filter`, `select`, `mutate`, `group_by` and `summarize`
3. Using the pipe: `|>` to push information through a pipeline.
4. Using the assignment operator `<-` to assign results to a variable or tibble or other sort of object.
5. Summarizing data with `summary`, `tabyl` and with `mosaic::favstats`
6. Dealing with missing data via the creation of complete-case analyses with `filter(complete.cases(.))`
7. Converting categorical variables to factors with `as_factor`, and recoding the levels of those factors with `fct_recode`
8. Building plots using `ggplot` and the `ggplot2` package
    - Setting the x and y variables with `aes()`
    - Using `geom_histogram()` to obtain histograms of quantities
    - Using `geom_boxplot()` and `geom_violin()` for comparisons of quantities across categories (groups)
    - Using `geom_point()` and `geom_smooth()` to build scatterplots of the association between quantities and fit linear models and loess smooths to data
    - Building multiple plots with `facet_grid()` and `facet_wrap()` and by using `aes(group = ., color = .)` to divide plots by a category
    - Using `labs()` to set axis labels, main and sub-titles
    - Using `guides(col = "none")` to delete legends from a plot where color is used to separate groups
9. Using `lm` to fit and `summary(lm())` to summarize a straight-line ordinary least squares linear regression model
10. Using `sessioninfo::session_info()` to describe information about your installation of R at the end of your session.

All of this material is also demonstrated in early Chapters of the [Course Notes](https://thomaselove.github.io/431-notes/), and we will review (and augment) these ideas in class over the next few weeks.

## What Should I Be Working On?

1. The [Minute Paper after Class 03](https://bit.ly/431-2023-minute-3), which is due at **noon Wednesday 2023-09-06**.
2. Get R and RStudio up and running effectively, if you haven't done so already. Consult the TAs in their office hours or ask questions on Campuswire if you need help.
3. Read through Chapter 1 of Spiegelhalter's *The Art of Statistics*, and through Chapter 3 of [R for Data Science](https://r4ds.hadley.nz/).
4. Complete [Lab 01](https://github.com/THOMASELOVE/431-labs-2023) by its deadline: **Tuesday 2023-09-12 at Noon**.
5. If you've not already done so, complete [these Tasks we'd hoped you'd do last weekend](https://github.com/THOMASELOVE/431-classes-2023/tree/main/class02#things-to-do-this-weekend).

## One More Thing

Thanks very much to the 29 of you who completed the requirements of [Section 13 of the Syllabus](https://thomaselove.github.io/431-syllabus-2023/13_movies.html) on time, and thus received a little class participation credit. Opportunities like this will appear through the semester, so keep an eye out for them. 

In the meantime, those of you who didn't complete this task already, **please do so today**. Thanks!


