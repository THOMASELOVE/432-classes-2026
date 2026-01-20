# 432 Class 03: 2026-01-20

[Main Site](https://thomaselove.github.io/432-2026/) | [Calendar](https://thomaselove.github.io/432-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2026/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Get Data](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2026/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | PDF | Quarto | Recording
:---: | :--------: | :------: | :-----: | :------: | :-------------:
03 | 2026-01-20 | **[Slides 03](https://thomaselove.github.io/432-slides-2026/slides03.html)** | **[PDF 03](slides03.pdf)** | **[Code 03](https://thomaselove.github.io/432-slides-2025/slides03.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Today we discusss logistic regression. Chapters 19-20  [Notes](https://thomaselove.github.io/432-notes/) in Chapters 19-20 will be a good place to supplement what we do today.
2. Remember that [Lab 1](https://thomaselove.github.io/432-2026/lab1.html) is due on Wednesday 2026-01-21 at noon.
3. The [Minute Paper after today's class 3](https://bit.ly/432-2026-min-03) is also due Wednesday 2026-01-21 at noon.
4. After today's class, you should be able to do [Lab 2](https://thomaselove.github.io/432-2026/lab2.html), which is due on Wednesday 2026-01-28 at noon.
5. If you need more advice on switching from R Markdown to Quarto, or why you should do so, [we recommend this](https://quarto.org/docs/computations/r.html).

## From the "Welcome to 432 Survey" (*n* = 35)

Question | 1 | 2 | 3 | 4 | 5 | 6 | Mean | SD
:----------------------------------------------: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: 
**How excited are you about taking this course?** <br/> 1 = I have nightmares about this class. <br/> 6 = I can't wait to get started. | 0 <br/> -- | 1 <br/> (3%) | 6 <br/> (17%) | 8 <br/> (23%) | 13 <br/> (37%) | 7 <br/> (20%) | **4.54** | **1.09**

Question | 1 | 2 | 3 | 4 | Mean | SD
:----------------------------------------------: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----:
**How comfortable are you with R?** <br/> 1 = I'm going to need a lot of refreshing. <br /> 4 = I use R all the time. | 0 <br/> -- | 5 <br/> (14%) | 22 <br/> (63%) | 8 <br/> (23%) | **3.09** | **0.61**
**How comfortable are you with Quarto?** <br/> 1 = What is Quarto? <br/> 4 = I'm pretty comfortable with Quarto. | 1 <br/> (3%) | 2 <br/> (6%) | 23 <br/> (66%) | 9 <br/> (26%) | **3.14** | **0.65**

Pearson correlation of *R comfort* with *Quarto comfort* = 0.19, with *n* = 35

## Ten thoughts on [Project A](https://thomaselove.github.io/432-2026/projA.html)

1. Read **all of** [the Project A instructions](https://thomaselove.github.io/432-2026/projA.html) before you get started. **Details matter**.
2. The three main parts of project A are all due in late February at the time specified on [the Course Calendar](https://thomaselove.github.io/432-2026/calendar.html):
    - An HTML report, [described here](https://thomaselove.github.io/432-2026/projA.html#the-project-a-report), written using Quarto [and our template]((https://raw.githubusercontent.com/THOMASELOVE/432-data/refs/heads/master/data/432_projectA_template.qmd)), along with the Quarto code you used, and
    - A cleaned and tidy data file that can be used to replicate your work, and
    - A recorded video presentation, [described here](https://thomaselove.github.io/432-2026/projA.html#the-project-a-presentation), which describes some findings from your Project in less than 5 minutes. `mp4` or `mov` is preferred as the format.
3. In addition, questions in [Lab 3](https://thomaselove.github.io/432-2026/lab3.html) and [Lab 4](https://thomaselove.github.io/432-2026/lab4.html) will require you to present some elementary results from your data. Lab 3 is due at the **start** of February (see [the Calendar](https://thomaselove.github.io/432-2026/calendar.html),) so you'll need to have your data in R by that time.
4. Everyone will need to do at least one of the two projects this semester alone. You can have a partner on Project A, or have a partner on Project B, but not both. You can also work alone on both Projects.
5. There is a [Quarto template for your Project A Report](https://raw.githubusercontent.com/THOMASELOVE/432-data/refs/heads/master/data/432_projectA_template.qmd). We require the use of this template in preparing your work.
6. There is a [demonstration project A](https://thomaselove.github.io/432-2026/432_projectA_demo.html), built by me, which provides HTML results and the Quarto code.
7. [What makes a data set acceptable?](https://thomaselove.github.io/432-2026/projA.html#what-makes-a-data-set-acceptable) is described in detail. **You should have your data in R by 2026-02-01**.
    - It is an **excellent idea** to [run a data set past us](https://thomaselove.github.io/432-2026/projA.html#running-a-data-set-past-us-for-project-a) before you are first required to tell us about what you're doing as part of Lab 3. To check to see if we're OK with data you propose to use, [follow the instructions here](https://thomaselove.github.io/432-2026/projA.html#running-a-data-set-past-us-for-project-a). Note that there is no formal *proposal* for Project A.
    - Here are a few potentially [good data sets to use](https://thomaselove.github.io/432-2026/projA.html#good-data-sets-to-use), if you're looking for ideas.
    - Here are [some of the data sets we will not accept](https://thomaselove.github.io/432-2026/projA.html#data-sets-we-will-not-accept-for-project-a) for Project A.
8. Your audience for the presentation and the report includes Professor Love, the teaching assistants and your fellow students. Prepare your presentation and report with that audience in mind. What will they need to know to understand what you’ve done, and get excited about it?
9. Questions about Project A may be directed to the TAs or Dr. Love or to `431-help at case dot edu` at any time.
10. Again, read **all of** [the Project A instructions](https://thomaselove.github.io/432-2026/projA.html) before you get started. **Details matter**.

Project B instructions will be posted later this semester.

## One Last Thing

![](https://imgs.xkcd.com/comics/data_point.png) [Source](https://xkcd.com/2713)

