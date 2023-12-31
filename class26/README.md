# 431 Class 26: 2023-12-07

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](https://imgs.xkcd.com/comics/compact_graphs.png) from <https://xkcd.com/2864/>

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
26 | 2023-12-07 | **[Slides 26](https://thomaselove.github.io/431-slides-2023/class26.html)** | [Code 26](https://thomaselove.github.io/431-slides-2023/class26.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements

1. **Quiz 2**: Your grade and a link to an answer sketch for Quiz 2 should be in your email (sent yesterday.)
    - The answer sketch has some small revisions today from the one that appeared last night, addressing some questions students had.
    - If you have any questions about the Quiz, please email me **before Sunday at noon**. After that, I want to be thinking solely about projects.
2. **Course Grades**: If your course grade is a concern, the **most** important thing to do is an excellent job on all elements of Project B.
    - The second most useful thing to do is complete and submit [Lab X](https://thomaselove.github.io/431-labX/), which is due at noon on Tuesday 2023-12-12.
3. Feedback on the Minute Paper after Class 25 [is now available](https://bit.ly/431-2023-min-25-feedback).
4. Interested in R Color Palettes? I think I've mentioned this before, but <https://github.com/EmilHvitfeldt/r-color-palettes> is a great resource, and might be helpful if you're trying to do something fancy in Project B.

## End of Class Logistics

1. **Monday 2023-12-11** is the last day of TA office hours, and is also the last day for Campuswire.
2. I will post Course Grades to SIS no later than Sunday 2023-12-17. That probably means you'll see them on Monday the 18th.
3. The 431 Zoom recordings of Fall 2023 classes will **disappear on 2023-12-25**, so if you want them, download them before Christmas.
4. The Fall 2023 431 Course Slides, Class Notes, Website and Google Drive Folder will stay where they are **until 2024-06-01**.
5. Dr. Love will **not be available** from December 18 through January 2.
6. This Spring's **432** class will begin at 1 PM on Tuesday 2024-01-16. The [432 website](https://thomaselove.github.io/432-2024/) exists in an early form now, and will go live on 2024-01-12, and all registered students will be informed via their CWRU email when it does.
7. This Spring's **500** class will begin at 8:30 AM on Thursday 2024-01-18. The 500 website will appear at <https://thomaselove.github.io/500-2024/> eventually, and go live on 2024-01-12, and all registered students will be informed via their CWRU email when it does.

## Remaining Deliverables

1. If you want Dr. Love to [regrade any of your Lab work](https://github.com/THOMASELOVE/431-labs-2023#lab-regrade-requests-will-be-reviewed-in-december), visit <https://bit.ly/431-lab-regrade-form-2023> by Friday 2023-12-08 at noon.
2. Optional [Lab X](https://thomaselove.github.io/431-labX/) is due at noon on 2023-12-12.
    - Here are [the success stories to date](https://github.com/THOMASELOVE/431-classes-2023/tree/main/labX). Congratulations to all of you!
3. Here is the [Project B Schedule of Presentations](https://github.com/THOMASELOVE/431-classes-2023/blob/main/projB/schedule.md).
    - Plan to join the Zoom call (or arrive at my office) five minutes before your presentation begins. Zoom information is found [on our Shared Drive in the Project B Presentations: Zoom Information document](https://docs.google.com/document/d/1ARSzHgUeoPW45ljzvecc46pHzUEQvjpDARB0a4-5418/edit?usp=sharing). 
    - Come to your presentation with a completed Project B. All of my other advice for the presentation [is available here](https://thomaselove.github.io/431-projectB-2023/checklist.html#oral-presentation-of-results).
    - There is no need to post anything to Canvas about Project B before giving your presentation.
    - Zoom information for each day of presentations will be made available to you on our Shared Drive,
4. All [Project B](https://thomaselove.github.io/431-projectB-2023/) materials (Quarto, HTML, Data and Self-Evaluation) are due at **9 AM on Sunday 2023-12-17**.
    - No late work will be accepted after 9 AM Sunday 2023-12-17.
    - If you are working with a partner, one of you should submit both the Study 1 and Study 2 reports to Canvas, and the other person should submit a one-page note to Canvas (word or PDF is best) containing your name, and stating something like “I worked on Project B with [your partner’s name] and they will submit Project B for our group.”
    - A complete set of Project B materials includes:
        1. your Quarto report for Study 1 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 1.
        2. your Quarto report for Study 2 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 2.
        3. if you worked with any data other than NHANES, your submission also needs to include your data (in the form you used to ingest the data in your Quarto file(s), so that we can run your Quarto code and obtain your HTML results.)
        4. and finally, the self-evaluation form at <https://bit.ly/431-2023-projectB-self-evaluation>, which you (and your partner, if you have one) should do separately once you've submitted your materials to Canvas.
        5. You are welcome to, but *not required to*, also post your slides (if you used them) from your presentation.

![](figures/taylor_2020.png)

## References from Today's Slides

- [Get Started with Tidymodels](https://www.tidymodels.org/start/). The sea urchins example comes from [Build a Model](https://www.tidymodels.org/start/models/).
- [TidyTuesday and tidymodels](https://juliasilge.com/blog/intro-tidymodels/) by [Julia Silge](https://juliasilge.com/).
- I have a semi-surprise visualization example, which (after the surprise has been revealed) might interest you in reading more from [Alberto Cairo](http://www.thefunctionalart.com/2016/08/download-datasaurus-never-trust-summary.html), [Steph Locke](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html), [Tomas Westlake](https://r-mageddon.netlify.com/post/reanimating-the-datasaurus/), [Julia Silge](https://juliasilge.com/blog/datasaurus-multiclass/) and [Justin Mareika and George Fitzmaurice](https://www.autodesk.com/research/publications/same-stats-different-graphs) in addition to what you've already read about it in Spiegelhalter. 

## Empirical Bayes (An Early and new 432 Topic, if you're interested)

- Julia Silge's YouTube video on "[Empirical Bayes for Doctor Who episodes](https://www.youtube.com/watch?v=OtDpYeiwbj8)" working with the [TidyTuesday 2023-11-28](https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-11-28/readme.md) data.
    - Here's Julia's [blog post about the Doctor Who data](https://juliasilge.com/blog/doctor-who-bayes/).
    - A 2016 blog post from Julia on [Singing the Bayesian Beginner Blues](https://juliasilge.com/blog/bayesian-blues/).
- Material from David Robinson at Variance Explained, including:
    - "[Understanding the beta distribution (using baseball statistics)](http://varianceexplained.org/statistics/beta_distribution_and_baseball/)"
    - "[Understanding Empirical Bayes Estimation (using baseball statistics)](http://varianceexplained.org/r/empirical_bayes_baseball/)"
    - David's [post announcing his e-book](http://varianceexplained.org/r/empirical-bayes-book/).
    - David's [e-book: Introduction to Empirical Bayes: Examples from Baseball Statistics](https://drob.gumroad.com/l/empirical-bayes).

## Some Other Things To Look At Over Break

1. Alex Reinhart's book [Statistics Done Wrong](https://www.statisticsdonewrong.com/index.html) is well worth your time.
2. Need some motivation to work with public health data and don't mind that the subject matter is horribly depressing? Here's the [Gun Violence Archive](https://www.gunviolencearchive.org/).
3. Looking for a video to watch over the break? Check out the work of [David Robinson](https://www.youtube.com/@safe4democracy), [Frank Harrell](https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA) or [Julia Silge](https://www.youtube.com/@JuliaSilge).
    - One good option is David's [Tidy Tuesday screencast: analyzing student/teacher ratios and other country statistics](https://www.youtube.com/watch?v=NoUHdrailxA)
    - Another is Julia's [Resampling to understand gender in art history textbooks](https://www.youtube.com/watch?v=Ac7V848uBuo) with this [accompanying blog post](https://juliasilge.com/blog/art-history/).
    - Several additional "get ready for 432" recommendations are in [my response to the Minute Paper](https://bit.ly/431-2023-min-25-feedback).
4. Need a break? Perhaps you'll enjoy these [10 GIFs for Stats/Data People](https://graphpaperdiaries.com/2017/03/15/7-gifs-for-statsdata-people/) from BS King.

# Ten of the Most Important Ideas from 431

1. You have to visualize and count data to understand it.
2. 90% of statistical work could be described as data management.
3. R Markdown and the tidyverse make it easier to do the right thing.
4. Statistical significance is not a helpful concept.
5. Point estimates and confidence intervals are useful ideas.
6. Most statistical procedures are in fact regression models.
7. All statistical methods involve assumptions worth checking.
8. The bootstrap is a very useful, and somewhat underused tool.
9. Prediction models need to predict well in new situations.
10. Statistical thinking is far too important to be left to statisticians.

![](figures/cox1.png)

## One Last Thing

Frank Harrell posted this [Biostatistical Modeling Plan](https://hbiostat.org/blog/post/modplan/), most recently on 2023-01-26. This is the kind of thing we will work towards in 432.

> This is an example statistical plan for project proposals where the goal is to develop a biostatistical model for prediction, and to do external or strong internal validation of the model.
