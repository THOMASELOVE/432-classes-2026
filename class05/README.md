# 432 Class 05: 2026-01-27

[Main Site](https://thomaselove.github.io/432-2026/) | [Calendar](https://thomaselove.github.io/432-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2026/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Get Data](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2026/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Word | Quarto | Recording
:---: | :--------: | :------: | :-----: | :------: | :-------------:
05 | 2026-01-27 | **[Slides 05](https://thomaselove.github.io/432-slides-2026/slides05.html)** | **[Word 05](https://thomaselove.github.io/432-slides-2026/zslides05.docx)** | **[Code 05](https://thomaselove.github.io/432-slides-2026/slides05.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

# Today's class will be held exclusively over Zoom.

## Announcements

1. The [Minute Paper after Class 5](https://bit.ly/432-2026-min-05) is due Wednesday 2026-01-28 at noon.
2. [Lab 2](https://thomaselove.github.io/432-2026/lab2.html) is also due Wednesday 2026-01-28 at noon, to [Canvas](https://canvas.case.edu).
3. By next week, you should complete [How To Be a Modern Scientist](https://leanpub.com/modernscientist).
4. Feedback on [Lab 1](https://thomaselove.github.io/432-2026/lab1.html) should be posted to our **Shared Drive** in the **432 Grades Roster for Students - Spring 2026** by class time. 
    - You should have received your 432 Lab Code and instructions on how to use it from me via **email** last Saturday (2026-01-24).
    - An answer sketch and grading rubric for Lab 1 appeared on our **Shared Drive** last Friday (2026-01-23).
    - Let us know at **431-help** at case dot edu if you have any questions about *how to review* your grades and feedback.
5. We request that you **not dispute any grading on Labs 1-7 via email or in discussions with TAs.** Instead, should you receive a lower grade on a Lab than you feel you deserve based on the feedback the TA provides, the answer sketch and the grading rubric, submit a request for a regrade by Professor Love using the Google Form at <https://bit.ly/432-2026-lab-regrades> by the deadline in the [Calendar](https://thomaselove.github.io/432-2026/calendar.html).
    - See [Section 8.4 of the Syllabus](https://thomaselove.github.io/432-syllabus-2026/08-grading.html#lab-appeal-policy---request-a-review-via-google-form) for more details on this policy.

## Project A Data - A tip about your linear regression outcome

**Remember**: If you have yet to find a data set for Project A and ingest it into R, you will need to have done so before submitting [Lab 3](https://thomaselove.github.io/432-2026/lab3.html) next week.

In [Project A](https://thomaselove.github.io/432-2026/projA.html), you may be interested in a quantitative variable that is also a **count**, say, the number of days out of the last 30 that the subject has experienced some sort of health issue.

- We'll have ways of dealing with count outcomes in regression models in the second half of the course.
- For Project A, it's fine to use such an outcome, but you may find that there is a pronounced **floor** (lots of people have 0 as their answer) or **ceiling** (lots of people have 30 as their answer) or both.
- Just for Project A, I suggest that if you have such a variable with a large spike in the histogram at one of the ends, for example, at 0, that you take a random sample of subjects who have complete data on this outcome **and** have a value greater than 0, just so you have more variability and avoid a spike in your outcome's distribution.

This tip, plus a reminder of what counts as a quantitative outcome for the Project, are now in the [Project A instructions](https://thomaselove.github.io/432-2026/projA.html), as of 2026-01-24. Just search for **NEW (01-24)** to see the additions.

---------------

## Reminders 

1. Details on the HELP RCT are available [at this site](https://www.mosaic-web.org/mosaicData/reference/HELPrct.html) in addition to the one cited in the slides.
2. Today's material using the `ols()` and `lrm()` functions is mostly covered in the [Course Notes](https://thomaselove.github.io/432-notes/), especially in Chapters 14 and 21.
3. Frank Harrell's books on biostatistical modeling, highlighted in the [Class 4 README](https://github.com/THOMASELOVE/432-classes-2026/tree/main/class04#announcements) are your best source for follow-up beyond our Notes.

## One Last Thing

Pew Research Center's [favorite data visualizations of 2025](https://www.pewresearch.org/short-reads/2025/12/15/our-favorite-data-visualizations-of-2025/) is worth a look.

