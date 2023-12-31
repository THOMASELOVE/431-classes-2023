# 431 Class 25: 2023-12-05

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
25 | 2023-12-05 | **[Slides 25](https://thomaselove.github.io/431-slides-2023/class25.html)** | [Code 25](https://thomaselove.github.io/431-slides-2023/class25.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

![](figures/schunemann_2022-12-01.png) [Link to this tweet](https://twitter.com/schunemann_mac/status/1598228310756331520); [Wikipedia on the Bradford-Hill criteria](https://en.wikipedia.org/wiki/Bradford_Hill_criteria)

## Announcements

1. Today's class will be ZOOM only. Check your email or Canvas for details.
2. Grades and feedback on Lab 7 are posted to the Course Grading Roster on our Shared Drive.
3. A [YouTube Playlist of Fall 2023 431 students' favorite songs](https://youtube.com/playlist?list=PL1WkTI58Hjcivws3CSv-xCLROR7-cEFgH) is now available.
    - I asked for your Favorite Song as [part of the Project B instructions](https://thomaselove.github.io/431-projectB-2023/checklist.html#a-special-note).
    - The list of songs is also posted to our Shared Drive.
    - A [YouTube Playlist of the Fall 2022 list of favorite songs](https://youtube.com/playlist?list=PL1WkTI58HjchPCLLYcV3q48LluH5z8aeN) (which includes two of my favorites) is also available.
4. Once you've submitted Quiz 2, it would be a good time to [update your R packages](https://thomaselove.github.io/431-2023/software.html#updating-your-r-packages).
    - There is a new version of R, version 4.3.2, so you can upgrade if you like at <https://cran.case.edu/>, but I'm fine with you sticking with version 4.3.1 through the end of 2023.
5. Some [End of Class Logistics information](https://github.com/THOMASELOVE/431-classes-2023/blob/main/class26/README.md#end-of-class-logistics) is posted to [our Class 26 README](https://github.com/THOMASELOVE/431-classes-2023/blob/main/class26/README.md#end-of-class-logistics).
6. Today I will demonstrate the use of functions from the `corrplot`, `ggmice` and `caret` packages. I have added these three packages to [our recommended packages for installation](https://github.com/THOMASELOVE/431-packages/tree/main).
    - The [R Graphics Cookbook](https://r-graphics.org/) shows some interesting [ways to visualize a correlation matrix](https://r-graphics.org/recipe-miscgraph-corrmatrix), which might be helpful to you. That's the motivation for the `corrplot` package.
    - [The `ggmice` package](https://amices.org/ggmice/ind) can help you enhance your multiple imputation work with visualizations for incomplete or imputed data. I'll try to get some material about it into 432, as well as today's little demonstration.
    - [The `caret` package](https://topepo.github.io/caret/) will allow us to complete a 10-fold cross-validation of a regression model for an imputed data set.

## Quote of the Day

> Imputing one value for a missing datum cannot be correct in general, because we don’t know what value to impute with certainty (if we did, it wouldn’t be missing).

— Donald B. Rubin
 
## Remaining Deliverables

1. [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2023/tree/main/quiz2) is due at 3 PM today. Please don't miss the deadline. [The Quiz 2 Google Form](https://bit.ly/431-2023-quiz2-form) will **close at 3:30 today**.
    - Status report on [Quiz 2 form submission](https://github.com/THOMASELOVE/431-classes-2023/blob/main/class25/quiz2receipt.md).
    - Grades and an answer sketch for Quiz 2 will be available by class time Thursday.
2. There is a [Minute Paper due Wednesday 2023-12-06 at noon](https://bit.ly/431-2023-minute-25). The link is <https://bit.ly/431-2023-minute-25>.
3. Optional: If you want Dr. Love to [regrade any of your Lab work](https://github.com/THOMASELOVE/431-labs-2023#lab-regrade-requests-will-be-reviewed-in-december), visit <https://bit.ly/431-lab-regrade-form-2023> by Friday 2023-12-08 at noon.
4. Optional: [Lab X](https://thomaselove.github.io/431-labX/) is due at noon on 2023-12-12.
    - Here are [the success stories to date](https://github.com/THOMASELOVE/431-classes-2023/tree/main/labX). Congratulations to all of you!
    - I've decided not to build a demonstration video, since many of you have found good options within [the Lab X instructions](https://thomaselove.github.io/431-labX/).
5. Here is the [Project B Schedule of Presentations](https://github.com/THOMASELOVE/431-classes-2023/blob/main/projB/schedule.md).
    - Plan to join the Zoom call (or arrive at my office) five minutes before your presentation begins. Zoom information is found [on our Shared Drive in the Project B Presentations: Zoom Information document](https://docs.google.com/document/d/1ARSzHgUeoPW45ljzvecc46pHzUEQvjpDARB0a4-5418/edit?usp=sharing). 
    - Come to your presentation with a completed Project B. All of my other advice for the presentation [is available here](https://thomaselove.github.io/431-projectB-2023/checklist.html#oral-presentation-of-results).
    - There is no need to post anything to Canvas about Project B before giving your presentation.
    - Zoom information for each day of presentations will be made available to you via email **by class time today**.
6. All [Project B](https://thomaselove.github.io/431-projectB-2023/) materials (Quarto, HTML, Data and Self-Evaluation) are due at **9 AM on Sunday 2023-12-17**.
    - No late work will be accepted after 9 AM Sunday 2023-12-17.
    - If you are working with a partner, one of you should submit both the Study 1 and Study 2 reports to Canvas, and the other person should submit a one-page note to Canvas (word or PDF is best) containing your name, and stating something like “I worked on Project B with [your partner’s name] and they will submit Project B for our group.”
    - A complete set of Project B materials includes:
        1. your Quarto report for Study 1 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 1.
        2. your Quarto report for Study 2 (.qmd and .html) submitted to Canvas. Be sure that the names of your Quarto and HTML files clearly identify whose project is being submitted and that these items refer to study 2.
        3. if you worked with any data other than NHANES, your submission also needs to include your data (in the form you used to ingest the data in your Quarto file(s), so that we can run your Quarto code and obtain your HTML results.)
        4. and finally, the self-evaluation form at <https://bit.ly/431-2023-projectB-self-evaluation>, which you (and your partner, if you have one) should do separately once you've submitted your materials to Canvas.
        5. You are welcome to, but *not required to*, also post your slides (if you used them) from your presentation.

## References for Today's Class

- Harrell FE <https://hbiostat.org/bbr/> Biostatistics for Biomedical Research course materials.
- Riley RD et al. [Calculating the sample size required for developing a clinical prediction model](https://www.bmj.com/content/368/bmj.m441) BMJ 2020; 368: m441. <https://doi.org/10.1136/bmj.m441>
- van Buuren S *Flexible Imputation of Missing Data* [How Many Imputations?](https://stefvanbuuren.name/fimd/sec-howmany.html)
- [The Favorite Movies Data, Session 3](https://github.com/THOMASELOVE/431-classes-2023/blob/main/movies/session3.md)
- <https://www.flickchart.com/>
- The source of the k-fold cross-validation image is [here](https://www.kaggle.com/code/taejoopark/kfold-for-small-image-dataset-vgg16-94-test-acc).

## How Large Does R-Squared Need to Be?

Statistics by Jim has some relevant thoughts [in this blog post](https://statisticsbyjim.com/regression/how-high-r-squared/).

> A low R-squared isn’t always a problem, and a high R-squared doesn’t automatically indicate that you have a good model.

> Different research questions have different amounts of variability that are inherently unexplainable. Case in point, humans are hard to predict. Any study that attempts to predict human behavior will tend to have R-squared values less than 50%. However, if you analyze a physical process and have very good measurements, you might expect R-squared values over 90%. There is no one-size fits all best answer for how high R-squared should be.

> So, how high should R-squared be? The definitive answer is . . . it depends.
 
## One Last Thing

[What is PHI? What is Not PHI? The List of 18 Identifiers from HIPAA](https://cphs.berkeley.edu/hipaa/hipaa18.html) from the Berkeley Human Research Protection Program

The 18 identifiers are:

1. Names;
2. All geographical subdivisions smaller than a State, including street address, city, county, precinct, zip code, and their equivalent geocodes, except for the initial three digits of a zip code, if according to the current publicly available data from the Bureau of the Census: (1) The geographic unit formed by combining all zip codes with the same three initial digits contains more than 20,000 people; and (2) The initial three digits of a zip code for all such geographic units containing 20,000 or fewer people is changed to 000.
3. All elements of dates (except year) for dates directly related to an individual, including birth date, admission date, discharge date, date of death; and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older;
4. Phone numbers;
5. Fax numbers;
6. Electronic mail addresses;
7. Social Security numbers;
8. Medical record numbers;
9. Health plan beneficiary numbers;
10. Account numbers;
11. Certificate/license numbers;
12. Vehicle identifiers and serial numbers, including license plate numbers;
13. Device identifiers and serial numbers;
14. Web Universal Resource Locators (URLs);
15. Internet Protocol (IP) address numbers;
16. Biometric identifiers, including finger and voice prints;
17. Full face photographic images and any comparable images; and
18. Any other unique identifying number, characteristic, or code (note this does not mean the unique code assigned by the investigator to code the data)

There are also additional standards and criteria to protect individuals from re-identification. Any code used to replace the identifiers in data sets cannot be derived from any information related to the individual and the master codes, nor can the method to derive the codes be disclosed. For example, a subject’s initials cannot be used to code their data because the initials are derived from their name. Additionally, the researcher must not have actual knowledge that the research subject could be re-identified from the remaining identifiers in the PHI used in the research study. In other words, the information would still be considered identifiable if there was a way to identify the individual even though all of the 18 identifiers were removed.
