# 431 Class 22: 2023-11-16

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
22 | 2023-11-16 | **[Slides 22](https://thomaselove.github.io/431-slides-2023/class22.html)** | [Code 22](https://thomaselove.github.io/431-slides-2023/class22.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements

1. Remember that 431 is canceled next Tuesday and all of CWRU is closed next Thursday. Our next class (Class 23) will be Tuesday 2023-11-28.
    - Dr. Love will be out of town and won't see email or Campuswire (essentially) between Sunday 2023-11-19 and Saturday 2023-11-25.
    - TA office hours are canceled starting SUN 2023-11-19 through SAT 2023-11-25, restarting SUN 2023-11-26.
2. Grades and feedback on Lab 6 are now available on our Course Grading Roster.
    - We have also posted a few of the responses to Lab 6 Question 5 that we liked on our Shared Drive.
3. 

## Taking Other Courses (like 432) With Me

In addition to 431, I teach two other semester-long courses, called **PQHS 432** and **PQHS 500**. I will teach both 432 and 500 in Spring 2023. Here's my advice, for what it's worth ...

- **432** is the continuation of this course (widely regarded as the "better" half.) I think **everyone** in this class should be planning to take 432 this Spring (i.e. Spring 2023), **unless** you don't feel you've received sufficient value from this course and don't need to take 432 to finish your program at CWRU, **or** you have an unshakable conflict in Spring 2023 (especially if you plan to instead take 432 in Spring 2024.)
    - I will provide the 432 website and syllabus to everyone enrolled in 432 on 2023-01-10. The Spring 2022 syllabus for 432 is [here](https://thomaselove.github.io/432-2022-syllabus/) but of course, things will change between now and January 10, in ways I will start to think about after 431 is complete on December 20. The 432 class begins on 2023-01-17, and is held on Tuesdays and Thursdays from 1:00 to 2:15 PM.
    - If you want to "get ahead" a bit on 432 over the break, do some work on the transition from R Markdown to [Quarto](https://quarto.org/docs/get-started/hello/rstudio.html).
    - Some details on 432 are available on our [post-class page](https://github.com/THOMASELOVE/431-classes-2022/tree/main/postclass).
- **500** is a project-based and more advanced course covering specific topics in the design and analysis of observational studies. 
    - I think everyone in this class who is interested in taking 500 should do so at some point. The course is mostly about using propensity scores well to help design (and analyze) data from observational studies where we want to estimate a causal effect.
    - A revised syllabus for the Spring 2023 version of the course will be available on or around January 12. The Spring 2022 syllabus for 500 is [here](https://thomaselove.github.io/500-2022-syllabus/), but of course, things will change between now and January 12, in ways I will start to think about after 431 is complete on December 20. The 500 course begins on 2023-01-19, and is held on Thursdays from 8:30 to 11 AM.
    - I especially think MS and PhD students (in any department) interested in applications of health research in real world situations should take it, as well as people looking for jobs in fields related to health care analytics.
    - For some people, it's better to complete 432 before taking 500 for several reasons, most especially ...
        1. percolation time for some of the ideas in 431/432
        2. too much of me at one time can be overwhelming
    - If Spring 2023 is your best opportunity to take 500, then I will certainly permit you to do so. Send me an email anytime if you want to discuss this.

## References from Today's Slides

- [Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/) by Jonas Kristoffer Lindeløv.
- Sterne JAC et al [Multiple imputation for missing data in epidemiological and clinical research: potential and pitfalls](https://www.bmj.com/content/338/bmj.b2393) BMJ 2009; 338:b2393.
- The mice (Multivariate Imputation by Chained Equations) package [reference page](https://amices.org/mice/).
    - Stef van Buuren, Karin Groothuis-Oudshoorn (2011). [mice: Multivariate Imputation by Chained Equations in R](https://www.jstatsoft.org/article/view/v045i03). Journal of Statistical Software, 45(3), 1-67. DOI 10.18637/jss.v045.i03.
- Framingham Heart Study at https://www.framinghamheartstudy.org/
- Heymans MW and Eekhout I [Applied Missing Data Analysis with SPSS and RStudio](https://bookdown.org/mwheymans/bookmi/)
- The `mipo` (Multiple Imputation pooled object) help file [can be found here](https://rdrr.io/cran/mice/man/mipo.html).


## One Last Thing

