# 431 Class 26: 2023-12-07

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
26 | 2023-12-07 | **[Slides 26](https://thomaselove.github.io/431-slides-2023/class26.html)** | [Code 26](https://thomaselove.github.io/431-slides-2023/class26.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements

1. Grades and an answer sketch for Quiz 2 should be in your hands **before class time**.
2. Feedback on the Minute Paper after Class 25 should also be available **by class time**.
3. Interested in R Color Palettes? I think I've mentioned this before, but <https://github.com/EmilHvitfeldt/r-color-palettes> is a great resource.
4. Alex Reinhart's book [Statistics Done Wrong](https://www.statisticsdonewrong.com/index.html) is well worth your time.
5. Need some motivation to work with public health data and don't mind that the subject matter is horribly depressing? Here's the [Gun Violence Archive](https://www.gunviolencearchive.org/).
6. Looking for a video to watch over the break? Check out the work of [David Robinson](https://www.youtube.com/@safe4democracy), [Frank Harrell](https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA) or [Julia Silge](https://www.youtube.com/@JuliaSilge).
    - One good option is David's [Tidy Tuesday screencast: analyzing student/teacher ratios and other country statistics](https://www.youtube.com/watch?v=NoUHdrailxA)
    - Another is Julia's [Resampling to understand gender in art history textbooks](https://www.youtube.com/watch?v=Ac7V848uBuo) with this [accompanying blog post](https://juliasilge.com/blog/art-history/).
7. Need a break? Perhaps you'll enjoy these [10 GIFs for Stats/Data People](https://graphpaperdiaries.com/2017/03/15/7-gifs-for-statsdata-people/) from BS King.

## End of Class Logistics

1. Monday 2023-12-11 is the last day of TA office hours, and is also the last day for Campuswire.
2. The 431 Zoom recordings of Fall 2023 classes will disappear on 2023-12-25, so if you want them, download them before Christmas.
3. The Fall 2023 431 Course Slides, Class Notes, Website and Google Drive Folder will disappear on 2024-06-01.
4. This Spring's 432 class will begin at 1 PM on Tuesday 2024-01-16. The 432 website will go live on 2024-01-12, and all registered students will be informed via their CWRU email when it does.
5. This Spring's 500 class will begin at 8:30 AM on Thursday 2024-01-18. The 500 website will also go live on 2024-01-12, and all registered students will be informed via their CWRU email when it does.

## Remaining Deliverables

1. If you want Dr. Love to [regrade any of your Lab work](https://github.com/THOMASELOVE/431-labs-2023#lab-regrade-requests-will-be-reviewed-in-december), visit <https://bit.ly/431-lab-regrade-form-2023> by Friday 2023-12-08 at noon.
2. Optional [Lab X](https://thomaselove.github.io/431-labX/) is due at noon on 2023-12-12.
    - Here are [the success stories to date](https://github.com/THOMASELOVE/431-classes-2023/tree/main/labX). Congratulations to all of you!
3. Here is the [Project B Schedule of Presentations](https://github.com/THOMASELOVE/431-classes-2023/blob/main/projB/schedule.md).
    - Plan to join the Zoom call (or arrive at my office) five minutes before your presentation begins. Zoom information is found [on our Shared Drive in the Project B Presentations: Zoom Information document](https://docs.google.com/document/d/1ARSzHgUeoPW45ljzvecc46pHzUEQvjpDARB0a4-5418/edit?usp=sharing). 
    - Come to your presentation with a completed Project B. All of my other advice for the presentation [is available here](https://thomaselove.github.io/431-projectB-2023/checklist.html#oral-presentation-of-results).
    - There is no need to post anything to Canvas about Project B before giving your presentation.
    - Zoom information for each day of presentations will be made available to you via email **by class time today**.
4. All [Project B](https://thomaselove.github.io/431-projectB-2023/) materials (Quarto, HTML, Data and Self-Evaluation) are due at **9 AM on Sunday 2023-12-17**.
    - No late work will be accepted after 9 AM Sunday 2023-12-17.
    - If you are working with a partner, one of you should submit both the Study 1 and Study 2 reports to Canvas, and the other person should submit a one-page note to Canvas (word or PDF is best) containing your name, and stating something like “I worked on Project B with [your partner’s name] and they will submit Project B for our group.”
    - A complete set of Project B materials includes:
        1. your Quarto report for Study 1 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 1.
        2. your Quarto report for Study 2 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 2.
        3. if you worked with any data other than NHANES, your submission also needs to include your data (in the form you used to ingest the data in your Quarto file(s), so that we can run your Quarto code and obtain your HTML results.)
        4. and finally, the self-evaluation form at <https://bit.ly/431-2023-projectB-self-evaluation>, which you (and your partner, if you have one) should do separately once you've submitted your materials to Canvas.
        5. You are welcome to, but *not required to*, also post your slides (if you used them) from your presentation.

## Empirical Bayes (An Early and new 432 Topic)

- Julia Silge's YouTube video on "[Empirical Bayes for Doctor Who episodes](https://www.youtube.com/watch?v=OtDpYeiwbj8)" working with the [TidyTuesday 2023-11-28](https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-11-28/readme.md) data.
    - Here's Julia's [blog post about the Doctor Who data](https://juliasilge.com/blog/doctor-who-bayes/).
    - A 2016 blog post from Julia on [Singing the Bayesian Beginner Blues](https://juliasilge.com/blog/bayesian-blues/).
- Material from David Robinson at Variance Explained, including:
    - "[Understanding the beta distribution (using baseball statistics)](http://varianceexplained.org/statistics/beta_distribution_and_baseball/)"
    - "[Understanding Empirical Bayes Estimation (using baseball statistics)](http://varianceexplained.org/r/empirical_bayes_baseball/)"
    - David's [post announcing his e-book](http://varianceexplained.org/r/empirical-bayes-book/).
    - David's [e-book: Introduction to Empirical Bayes: Examples from Baseball Statistics](https://drob.gumroad.com/l/empirical-bayes).

## One Last Thing

Frank Harrell posted this [Biostatistical Modeling Plan](https://hbiostat.org/blog/post/modplan/), most recently on 2023-01-26. This is the kind of thing we will work towards in 432.

> This is an example statistical plan for project proposals where the goal is to develop a biostatistical model for prediction, and to do external or strong internal validation of the model.
