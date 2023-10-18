# 431 Class 16: 2023-10-19

[Main Website](https://thomaselove.github.io/431-2023/) | [Calendar](https://thomaselove.github.io/431-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2023/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](https://imgs.xkcd.com/comics/epistemic_uncertainty.png)

Source: https://xkcd.com/2440/, where the hover text for this entry is "Luckily, unlike in our previous study, we have no reason to believe Evangeline the Adulterator gained access to our stored doses. *Epistemology* is the investigation of what distinguishes justified belief from opinion. It is a branch of philosophy dealing with the theory of knowledge, especially with regard to its methods, validity, and scope. 

## Today's Slides

Class | Date | Slides | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
16 | 2023-10-19 | **[Slides 16](https://thomaselove.github.io/431-slides-2023/class16.html)** | [Code 16](https://thomaselove.github.io/431-slides-2023/class16.qmd) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- To print RevealJS slides **to pdf** from the Slides Link above, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

## Announcements

1. Remember that we don't have class next Tuesday 2023-10-24, or TA hours next Monday or Tuesday thanks to Fall Break. Campuswire will be open.
2. Feedback on the Minute Paper after Class 15 will be posted **by class time**.
3. An answer sketch for Lab 4 will be posted **by class time**.

## Breakout Session 2 on Favorite Movies

We'll spend 15 minutes today on [Breakout 2](https://github.com/THOMASELOVE/431-classes-2023/blob/main/movies/breakout2.md) today. Please join the group you were with on Tuesday, or (if you missed Tuesday's class) join an existing group.

## Materials Discussed in Today's Class

- Ronald L. Wasserstein, Allen L. Schirm & Nicole A. Lazar (2019) [Moving to a World Beyond "p < 0.05"](https://www.tandfonline.com/doi/full/10.1080/00031305.2019.1583913), *The American Statistician*, 73:sup1, 1-19, DOI: [10.1080/00031305.2019.1583913](https://doi.org/10.1080/00031305.2019.1583913). 
    - Ron gave a [one-hour talk you can watch here](https://t.co/GbQF01h4jU) on "[Helping to move to a world beyond p < 0.05](https://t.co/GbQF01h4jU)" which I cannot recommend enough.
- Ronald L. Wasserstein & Nicole A. Lazar (2016) [The ASA's Statement on p-Values: Context, Process, and Purpose](https://www.tandfonline.com/doi/full/10.1080/00031305.2016.1154108), *The American Statistician*, 70:2, 129-133, DOI:
[10.1080/00031305.2016.1154108](https://doi.org/10.1080/00031305.2016.1154108).
- [The Growing Importance of Reproducibility and Responsible Workflow in the Data Science and Statistics Curriculum](https://www.tandfonline.com/doi/full/10.1080/26939169.2022.2141001) by Nicholas J. Horton, Rohan Alexander, Micaela Parker, Aneta Piekut & Colin Rundel (2022) *Journal of Statistics and Data Science Education*, 30:3, 207-208, DOI: 10.1080/26939169.2022.2141001

Some other resources for learning more after today's talk are:

- Frank E. Harrell's [A Litany of Problems with *p*-values](https://www.fharrell.com/post/pval-litany/) blog post most recently updated in 2020.
- William Briggs' [Everything Wrong with P-values Under One Roof](http://wmbriggs.com/post/26125/) which links to a detailed article on the subject.
- Jeffrey Leek and Roger Peng [P-values are just the tip of the iceberg](references/Leek_and_Peng_2015_Pvalues_Nature.pdf)
- Jeffrey D Blume, Lucy D'Agostino McGowan, William D. Dupont, Robert A Greevy [Second-generation p values: Improved rigor, reproducibility and transparency in statistical analyses](references/Blume_etal_2018_Second_Generation_P_Values.pdf)
- Andrew Gelman and John Carlin [Beyond Power Calculations: Assessing Type S (Sign) and Type M (Magnitude) Errors](references/Gelman_Carlin_2014_Beyond_Power_Calculations.pdf)
- [Scientists rise up against statistical significance](https://www.nature.com/articles/d41586-019-00857-9) in *Nature* 2019-03-20
- [It's time to talk about ditching statistical significance](https://www.nature.com/articles/d41586-019-00874-8) also in *Nature* 2019-03-19.
- Briggs, William M., 2019. [Everything Wrong with P-Values Under One Roof](http://wmbriggs.com/post/26125/). In Beyond Traditional Probabilistic Methods in Economics, V Kreinovich, NN Thach, ND Trung, DV Thanh (eds.), pp 22–44. DOI 978-3-030-04200-4_2
- the "PROBABLE CAUSE" graphic reprinted in this [Nature piece by Regina Nuzzo](https://www.nature.com/news/scientific-method-statistical-errors-1.14700), originally from T. Sellke et al. in *The American Statistician*, 2001.
- and several great pieces by Christie Aschwanden at 538:
    - "[Not Even Scientists Can Easily Explain P-Values](https://fivethirtyeight.com/features/not-even-scientists-can-easily-explain-p-values/)", and
    - "[Statisticians Found One Thing They Can Agree On: It's Time To Stop Misusing P-values](https://fivethirtyeight.com/features/statisticians-found-one-thing-they-can-agree-on-its-time-to-stop-misusing-p-values/)", and
    - "[Science Isn't Broken](https://fivethirtyeight.com/features/science-isnt-broken/#part1)" with graphics by Ritchie King.
- You may also be interested in this piece at pbs.org about a NOVA program entitled "[Rethinking Science's Magic Number](https://www.pbs.org/wgbh/nova/article/rethinking-sciences-magic-number/)".
- I have given several talks on "Rethinking Statistical Significance" in recent years. The Github repository (90 minutes at MetroHealth Medical Center and the Center for Health Care Research and Policy, with an audio recording) is at https://github.com/THOMASELOVE/rethink, if you're a glutton for punishment.
- [Why p values are like puppies](https://www.youtube.com/watch?v=9jW9G8MO4PQ) is a 3:29 YouTube Video by Cassie Kozyrkov, MS, Chief Decision Scientist, Google Inc. It explains how to understand and interpret *p* values in an intuitive way using an example based on puppies.


## What to Work on This Weekend (through Wednesday)

1. [Lab 5](https://github.com/THOMASELOVE/431-labs-2023/blob/main/lab05/lab05.pdf) due **THURSDAY** 2023-10-26.
    - Although this Lab has 10 questions, you are to answer only seven. Everyone will answer questions 1, 5, 9 and 10, but some will then choose to answer 2-4 and others 6-8. Doing all ten questions will yield no benefit to your grade on the Lab, although it might help increase your understanding for the Project.
2. Project A, due Tuesday 2023-10-31.
3. Read *The Art of Statistics* through Chapter 9.
4. It's never too early to start working on [Lab X](https://thomaselove.github.io/431-labX/).

Remember: no class Tuesday and no office hours Monday or Tuesday.

## One Last Thing

EJ Daza, [Ditch “Statistical Significance” — But Keep Statistical Evidence. How? A statistician shares a writing sample](https://towardsdatascience.com/ditch-statistical-significance-8b6532c175cb). *Towards Data Science*, 14 June 2021.
