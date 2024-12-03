---
layout: page
title: Workshop Summary
nav_exclude: false
nav_order: 5
description: A summary of the workshop for participants.
---

# Workshop Summary
{:.no_toc}

_View this page as a_ **Participant**{: .label .label-red }

The workshop took place on the beautiful IIT Madras campus on November 27-29. Although cyclone Fengal was waiting ominously offshore throughout the week and threatened to disrupt the event, this did not stop the 3 instructors and approximately 20 or so participants from having an active and fruitful workshop.

On Day 1 you were students; Day 2 your were teachers and Day 3 you did a great job working on books. A **lot** of material was covered, so our hope is that this page and the associated materials help you get started on your journey towards education innovation, wherever that may lead you!

![participant photo, end of workshop]([../assets/figures/week.png](https://github.com/IITM-MUDE/2024-workshop-files/raw/main/src/teachers/DSC_0219.JPG)){:width="500px"}

## How to stay in touch

Participants can contact Robert directly via email.

GitHub is also a great place to collaborate!
- The GitHub Organization [github.com/IITM-MUDE](https://github.com/IITM-MUDE){:target="_blank"} could be a place to use as a "sandbox" and help each other.
- If you are interested in **books**  in particular and would like to contribute, request a feature or complain about something visit the TeachBooks GitHub Organization at [github.com/TeachBooks](https://github.com/TeachBooks){:target="_blank"} (read the introduction; some of our key repositories are also described below).
- Use pull requests, discussions, issues and don't hesitate to tag Robert in your comments (`@rlanzafame`); however, note that response time is slower than via email.


## Table of Contents
{:toc}

---

## Overview of Activities

The activities and scope of each day are described below. The slides are provided as PDF files via the Files page [here](https://iitm-mude.github.io/2024-workshop-files/students/Workshop-Slides/){:target="_blank"}. Note that they are numbered in order presented; slide 02A was never presented directly, but contains some material about programming that came up frequently in workshop discussions.

### Day 0: Preparation Materials

Participants were asked to read this website and start the course from the perspective of a student (see initial instructions sent via email at the end of this page). This included reading in the textbook, installing software and completing the programming assignment (PA1), which was distributed via GitHub Classroom. The original email with instructions for starting the assignment is reproduced at the end of this page.

A short survey was also sent to participants to gather some background information on prior programming and software experience in an educational and non-educational setting. Key results are summarized in the introduction slides for the workshop (00_Introduction.pdf).

### Day 1: MUDE as a Student (Wednesday)

Activities:

- Welcome, introduction. Slides: 00.
- Lecture: Introduction to Workshop and MUDE. Slides: 01.
- Discussion: close with a round of feedback/reflection to inform sessions for following days. Slides: 00.

### Day 2: MUDE as a Teacher (Thursday)

Activities:

- Interactive session: MUDE as a Student. Participants work on real assignments from MUDE (WS1 and GA1 in Files). Slides 02A.
- Discussion: reflect on the assignments. Slides 02A.
- Lecture: Tools --- GitHub Pages, Classroom and Copilot (a few slides, but mostly a demonstration)
- Lecture and demonstration: TeachBooks. Slides: 04.
- Lecture: Introduction to Git (Alex Garzon Diaz). Slides: 04B.

Slides: 02 through 04.

An extra set of slides `02B_Programming.pdf` was added to summarize the programming discussions that took place throughout the first two days.

The workshop WS1 and group assignment GA1 on the Files website were the primary materials used in the interactive activity at the beginning of Day 2. To do this as a student, one could download the zip file and work in VS Code. Later solutions were added, and WS2 and GA2 were included to illustrate the full scope of two weeks of MUDE content. Note that the IITM book chapter, WS1, WS2, GA1, GA2 illustrate the theoretical content for _two_ weeks of MUDE (Weeks 1.5-1.6 during the 2024-25 academic year). Recall also that MUDE is approximately 40% of the study load during the quarter, and on average should be 16 hours of work for the students. The programming assignments from these weeks in MUDE are not included here as they involved a lot of activities with Git that were outside the scope of the IITM workshop.

### Day 3: MUDE at IIT Madras (Friday)

Activities:

- Interactive session: work on projects in small groups (mostly creating/editing a TeachBook). Slides: 05.
- Lecture: MUDE Assessment (Sandra Verhagen). Slides: 05B.
- Closing

On the last day, all participants were added to a GitHub Organization called "IITM-MUDE" ([github.com/IITM-MUDE](https://github.com/IITM-MUDE){:target="_blank"}. The three key websites used in the workshop were set up here for future reference (as well as experimentation!). Participants are all made owners of this organization, so feel free to add new repositories or modify the existing one, especially if you would like to reach out for help from the TU Delft instructors. 

## Summary of Selevted Workshop Activities

### Wednesday

During the MUDE Introduction lecture there were several discussions and questions, the most significant focusing on student group selection,  assessment format, how to grade assignments, use of Git (by teachers and students).

- How to maintain versions of assignments (i.e., notebooks, py files) and release files to students. This can be complicated; key advice is to make sure source code is easily available to students (e.g., via GitHub Classroom repositories) and that there is a way for them to easily review them in a read-only format (e.g., convert source code to HTML pages).
- Questions about non-Python resources (C, Fortran, panel programming): this is possible, but we have not implemented it in TeachBooks yet. Check out [this GitHub discussion](https://github.com/orgs/TeachBooks/discussions/22){:target="_blank"}; feel free to add comments!.
- Can we randomize things in the notebook? Yes! You can do this using typical Python libraries (e.g., `random` or `numpy.random`). You could also combine this with Sympy.
- Is there a symbolic math library in Python? Yes, it is called Sympy. Check out the [Sympy website](https://www.sympy.org/en/index.html){:target="_blank"} for more information. Here is an [example interactive page introducing Sympy](https://teachbooks.io/learn-python/08/sympy.html){:target="_blank"}. Maybe you could also combine this with the [answer checking button](https://teachbooks.io/manual/features/exercise_checking.html){:target="_blank"} (note that this is currently being converted to a dedicated package, see [this TeachBooks project](https://github.com/orgs/TeachBooks/projects/54){:target="_blank"}).
- How to reinforce/teach fundamental programming concepts? This really depends on the pre-knowledge and experience of students. One thing is for sure: it is ineffective to give high level instructions (e.g., "do analysis in Python") and assuming a BSc course has covered it. We try to: a) mix activities (e.g., consider reading code, writing pseudo-code, pair programming, peer review, the rubber duck method, etc.), and b) provide background material (e.g., see the Learn Python and Learn Programming materials in the Resources section, which are meant to be easy to include as links to the students). Consider also using pre-checks per week or per assignment to help the students identify whether they are at the appropriate level. We all agreed that repetition is effective when it comes to programming concepts. Finally, while your initial work may focus on an individual course, many of the programming challenges are probably best tackled across the curriculum; ideally follow-on courses continue to build on the programming concepts covered in your courses. This is what we would like to do in the future for MUDE as well.

The following was noted regarding the material that was sent as homework:
- Computers/environment page in the book was appreciated
- Regarding the narrative of the assignment: storytelling style on notebooks (PA1) is fine, but can see advantages of another approach such as introducing the theory/big picture first, then move on to more independent exercises
- Python warmup page was effective for helping non-Python users with prior programming experience get familiar with the language. This type of page is very easy to set up in a TeachBook.

### Thursday

#### Discussion after the review of the WS1

Several small groups were asked to comment on WS1; these are collected into themes and summarized here:

**Too far too fast**
- The level of our CE students can be lower when it comes to programming, so care should be taken to provide support and pre-requisite knowledge; conversely, care should be taken to make assignment at the appropriate level
- Very easy to make the programming part too complex; structure can help with this, though

**The notebook is very structured; perhaps it is too structured.**
- Perhaps this prevents students from learning to be independent programmers
- the structure would make it much easier and faster to grade/assess the assignments (as a teacher)
- The structure makes it easier to review (as a student)
- There is a lot of text to read; could lead to losing track of the primary instructions

**Motivation of students**
- It is clear that the teachers pu a lot of work into the assignment, which motivates the reader/student to learn
- functions can be modified easily, so it is easier to experiment
- although the focus may be on the mathematics, the format of the notebook makes it easier to learn Python as a "bonus"

## Reusing material

For many of us in MUDE open source software and permissive licenses on content are new to us. Once we started creating digital material ourselves, we realized how useful permissive licenses are: the content of others becomes much easier to use, as you are free to adapt it and use it in flexible ways. This is why we are planning to release the MUDE material under a Creative Commons Attribution license (CC BY).

You can find out more about CC licenses [here](https://creativecommons.org/share-your-work/cclicenses/){:target="_blank"}.

Because we have not completed all of the copyright checks and checked with all contributors, the material is still password protected. Unfortunately, the process won't be done until early 2025.

In the mean time, if you want to use MUDE material, some recommendations are provided below.

### MUDE Book

- Get the source code from the GitHub Repository [github.com/TeachBooks/mirror_mude_book](https://github.com/TeachBooks/mirror_mude_book/) (the `release` branch is the "final" version that the students see). This is a mirror of the source repository for the MUDE book, which is part of the TU Delft Git**Lab**, which is not yet public. Once the respotory is made public the source code can be found at [gitlab.tudelft.nl/mude/book](https://gitlab.tudelft.nl/mude/book){:target="_blank"}.
- Make any changes to the source code as needed for your book
- Note the source on the specific book, chapter or page, depending on the level of detail you want to provide.
- We recommend you include a credits page that describes all your sources (and you can also describe how you want others to reference your work). It would also be useful to describe modifications made to the source material so that others can understand how you have adapted the material (this should also be useful for you in the future as well!).

Until the MUDE book is fully open, a note on a page/chapter could look like this:
> This page/chapter uses material from the MUDE book [mude.citg.tudelft.nl/book](https://mude.citg.tudelft.nl/book){:target="_blank"}, accessed on `<date>`. `<add citation or link to credits page of book>`.

The reference is:
> Lanzafame, R., van Woudenberg, T., Verhagen, S. (2024) Modelling, Uncertainty and Data for Engineers (MUDE) Textbook, Delft University of Technology. [Unpublished online textbook]. [mude.citg.tudelft.nl/book](https://mude.citg.tudelft.nl/book){:target="_blank"}.

Once the MUDE book is fully open, the book itself will include instructions for referring to and reusing content.

Here are some examples:
- This book has an editor for the entire book, with individual authors noted for each chapter when it deviates from the editor. It is summarized on [this credits page](https://interactivetextbooks.citg.tudelft.nl/risk-reliability/credits.html){:target="_blank"}; [here is an example](https://interactivetextbooks.citg.tudelft.nl/risk-reliability/risk-analysis/overview.html){:target="_blank"} of a chapter being noted with a different author. A similar approach could be used to indicate that the source material came from the MUDE book.
- The TeachBooks Manual does the same thing, see [here](https://teachbooks.io/manual/credits.html){:target="_blank"}.
- We are actively trying to come up with a best practice for this, for example, see the discussion in [this Pull Request](https://github.com/TeachBooks/manual/pull/31){:target="_blank"}.

### MUDE Assignments

Assignments, or more generically, _educational resources_, have not been made public yet (we plan on CC BY, then they will become _open_ educational resources, OER); contact Robert directly (R.C.Lanzafame@tudelft.nl) if you have a request for specific content.

Until the ER becomes OER, the following note should be included in the file itself or the directory in which the file is located:

> This assignment/files/educational resource uses material from MUDE [mude.citg.tudelft.nl](https://mude.citg.tudelft.nl){:target="_blank"}, accessed on `<date>`.

This is especially important if your course files are shared publicly (which we hope you do under CC BY eventually!). It is not required that students see the reference to MUDE if the files/assignments are not shared publicly. In addition to the note it is advised to include a record of modifications and some sort of link to the source material in the directory where you keep assignments, for example, in a Markdown file.

The reference for assignments is:
> MUDE (2024) Modelling, Uncertainty and Data for Engineers (MUDE) Educational Resources, Delft University of Technology. [Unpublished]. [mude.citg.tudelft.nl](https://mude.citg.tudelft.nl){:target="_blank"}.

When the assignments are made fully open, they will probably be shared via a GitHub or GitLab repository along with a permissive license (ideally CC BY), and perhaps published via an OER publisher. This is expected to occur on an annual basis following the completion of an academic year.

## Git Materials

I added the MUDE Git Materials to our shared [MUDE in Madras book](https://iitm-mude.github.io/2024-workshop-book/main/intro.html){:target="_blank"}. It is also described in the TeachBooks Manual [here](https://teachbooks.io/manual/installation-and-setup/git-setup_local.html){:target="_blank"}.  This should help fix some of the git issues that were popping up on the last day (i.e., SSH setup with your GitHub account; the what, why and how of merging and Pull Requests).

The material should also give you an idea of what we do with our students regarding Git. Our goal is to not make them Git experts, but rather be aware of the key workflows, as well as GitHub (or competitors like GitLab). Mostly the students use VS Code to complete all git workflows, primarily cloning, committing and pushing. Some students voluntarily use branching with group assignments. Overall there are still some issues and we are still refining this part of our curriculum; for example, next year we need to be more explicit about the key Git commands (commit, fetch, pull, push, status, etc) so that students are more aware of what VS Code is doing. In addition, confusion in class often is compounded when there is also lack of knowledge about the file system and VS Code usage (for example, students don't save work or are working in a different folder than the git repo and think they have uploaded a specific file, but have not).

Note that one of the advantages of GitHub Classroom is that it will expose students to Git and GitHub, which is much better than learning to use a complicated educational platform (i.e., a tool that is integrated into Moodle). 

A final note on Git: remember that when working with others, you should try to work in branches as much as possible and merging to incorporate your changes (a "Pull Request" on GitHub).

## GitHub Classroom

Hopefully the experience of using this as a student was enough to see the advantage of this platform. I also showed the browser GUI a couple times. Since you all should have access to the GitHub Organization `todo`, all you need to be able to join the GitHub Classroom is to visit [this link](https://classroom.github.com/classrooms/189075451-iitm-mude-2024-workshop-classroom){:target="_blank"}. Many of your colleagues at the workshop were successfully invited as owners, so they can also give you (and anyone else) access.

We only scratched the surface in our workshop: there is a huge potential to customize the use of GItHub Classroom to the needs of your courses, and the official documentation will give you a better overview than I can. My advice is experiment often and early, and of course, test this in low-risk situations in advance (e.g., test with each other, or share "practice" materials before graded assignments). Once you get the hang of it, it becomes very fast and easy to create and deploy assignments to students (assuming the files are ready).

## Software Notes on Jupyter Books and TeachBooks

Remember, the key technology is the Python package Jupyter Book. Check out their [documentation](https://jupyterbook.org/){:target="_blank"} if you have not done so already; the [MyST syntax cheatsheet](https://jupyterbook.org/en/stable/reference/cheatsheet.html){:target="_blank"} is very useful for looking up syntax when editing the book.

Our initiative **TeachBooks** young (March, 2024) and still defining itself. At the moment it is several things:
- a group of people focused on using Jupyter Books in an educational setting
- a collection of software and example books on [github.com/teachbooks](https://github.com/teachbooks){:target="_blank"} (a GitHub _Organization_)
- always open for collaboration! visit our [github organization](https://github.com/teachBooks/){:target="_blank"} or our website [teachbooks.io](https://teachbooks.io) to learn more

Key resources to be aware of:
- The [manual](https://teachbooks.io/manual){:target="_blank"}!!!
- The [template repository](https://github.com/teachbooks/template){:target="_blank"} (we used this in the workshop; there are detailed instructions in the README)
- The [deploy book workflow](https://github.com/TeachBooks/deploy-book-workflow){:target="_blank"} is what enables all branches to build automatically. It is included in the template books by default; take a look at the documentation (or visit the [manual page](https://teachbooks.io/manual/external/deploy-book-workflow/README.html){:target="_blank"} if you want to know more.
- The [teachbooks Python package](https://github.com/teachbooks/teachbooks) adds some handy pre- and post-processing steps to the book, and will grow with time. For now, the command `teachbooks serve` is essential when you want to test interactive features locally (especially the interactive Python kernel!). Read more [here](https://teachbooks.io/manual/external/TeachBooks/README.html){:target="_blank"}. For the CLI enthusiasts, we are working on the package documentation page; contributions and ideas are also very much welcome for this via GitHub!

### Recommended Book Workflows

The [TeachBooks Manual](https://teachbooks.io/manual){:target="_blank"} lays out various workflows and tools based on User type. For example: User Type 3 contributes only in the browser (no software installation needed), whereas User Type 5 can do pretty much everything. If you are User Type 3, it is possible to build a book all on your own; however, it is also much more efficient if can get a bit of help from a Type 5 user!

Workflows are described in the manual [here](https://teachbooks.io/manual/workflows/collaboration.html#){:target="_blank"}. A brief summary is provided below.

#### User Type 3: Everything Online

For User Type 3, the following workflow is recommended:
- create a branch for your additions
- use the GitHub browser interface to edit the book (access it by pressing the period `.` from the home page)
- commit changes to the branch
- check that things look good by finding the built version of your branch in the Actions tab (this is the [deploy book workflow](https://github.com/TeachBooks/deploy-book-workflow){:target="_blank"})
- merge your branch when satisfied by creating a Pull Request (invite review or checks from colleagues as needed)

Note that User Type 3 must wait for GitHub to build the book and update the website, which can be very tedious when troubleshooting small errors in the book build process. Therefore, we recommend you ask a User Type 5 to help you with this, or simply become a User Type 5 yourself!

#### User Type 5: Build Locally

For User Type 5, the following workflow is recommended:
- create a conda environment dedicated to book building (decsribed in more detail below), for example, `book-312`
- activate the environment whenever you work on the book locally (`conda activate book-312`)
- To test the interactive pages use the `teachbooks` package to serve the book locally (`teachbooks serve`)
- commit changes to a branch, check online, push/merge (same as User Type 3)

### Conda Environment for Book Building

Robert created a file to help you create a conda environment for use with books, `book-311.yml`, which can be found in the Files page [here](https://iitm-mude.github.io/2024-workshop-files/students/){:target="_blank"}. You can create the environment by running `conda env create -f book-311.yml` from the directory where the file is located. This will create a new environment called `book-311` with all the necessary packages for building a book; it was tested by Robert on the demo book from the workshop. You can activate the environment by running `conda activate book-311`.

## Environments and Package Management

Although you were asked to create a conda environment as part of the pre-workshop homework assignment, we did not cover this in depth in the workshop. Package management and environments can be a huge help to a) you, when writing TeachBooks, and b) with your students, to avoid unnecessary "coding problems." You can see the MUDE materials for examples of how we are doing this with our students. Hint: use it, don't ignore it! Build an environment on day 1 and use it explicitly for every activity; don't stick with `base` forever. Reach out if you would like more information. As far as books go, we recommend doing the following:

In MUDE we are still refining how we use environments, as there are many different options (e.g., conda, venv, pip, poetry, mamba, etc.), each with pros and cons. For now we use conda because although it is not fast, it is reliable and can be used with different languages, not only Python. [Here is a nice explanation by Jason Moore](https://mechmotum.github.io/blog/setup-development-environment.html){:target="_blank"}, who has been using Python in education for a long time. In the end, we don't really mind that our setup isn't perfect yet, as including environments is guaranteed to be a good thing for our students as it forces interaction with the file system, command line interface, packages and other generic programming-related concepts.

## Additional Resources

We are sure the task of creating an entire book is daunting. Therefore, one step in the right direction could be to create a **workbook** instead of a full, formal textbook. This uses the same Jupyter Book/TeachBook platform, but is a less formal way to share useful code and material with your students. Here are some examples:

- a [structural reliability workbook](https://teachbooks.io/HOS-workbook/main/intro.html){:target="_blank"} (contact Robert for more info)
- [this is an optimization book](https://teachbooks.github.io/engineering-systems-optimization){:target="_blank"} by Tom van Woudenberg that that started as a workbook but is now very well developed. It has a lot of nice interactive examples
- [another book by Tom](teachbooks.io/Macaulays_method) that collects a number of examples of Macaulay's method from BSc projects, including implementation in Sympy
- [this book](https://teachbooks.io/mechanics-BSc/intro.html){:target="_blank"} by Tom van Woudenberg collects many topics, whereas [this book](https://teachbooks.io/bridging_mechanics/2024/intro.html){:target="_blank"} uses the material from the first book and organizes it in a structured way for a specific course.

Here are some additional content resources that may be useful:

- We have two books where we are adding our generic Python and Programming material. Much of the MUDE programming material is from these books. The idea is that they are useful references for the students via hyperlinks. The books are Learn Python [github.com/teachbooks/learn-python](https://github.com/teachbooks/learn-python){:target="_blank"} and Learn Programming [github.com/teachbooks/learn-programming](https://github.com/teachbooks/learn-programming){:target="_blank"}.
- More FEM material: here is the book where the MUDE FEM material comes from. It is not yet open, but I have asked the authors if they can put a license on it and open up the repository. Contact Robert if you would like source code access, he can give you an update. [interactivetextbooks.citg.tudelft.nl/computational-modelling/intro.html](https://interactivetextbooks.citg.tudelft.nl/computational-modelling/intro.html){:target="_blank"}
- The [Good Research Code Handbook](https://goodresearch.dev/index.html){:target="_blank"} is a great resource for learning about best practices in programming. It helps us on the teacher side of things, and to use as a reference point for where we would like our students to get to if they start a PhD.

Here are a few resources about programming in education that are useful:

- The [python for edu book](https://jupyter4edu.github.io/jupyter-edu-book/) has a lot of good material and ideas for classroom activities, although the platforms are now a bit dated.
- [An excellent perspective from Berkeley](https://hdsr.mitpress.mit.edu/pub/e69066t4/release/3){:target="_blank"}, where their Data Science courses have exploded in popularity, and a new college (CDSS) was recently opened. Also interesting is [the response by Allen Downey](https://hdsr.mitpress.mit.edu/pub/kk63wpuo/release/1){:target="_blank"}, who has a lot of interesting material himself as well.
- There is good description of infrastructure used in Data Science at Berkeley [here](https://ucbds-infra.github.io/ds-course-infra-guide/intro.html){:target="_blank"}
- Jason Moore and Allen Downey have done a "computation thinking" workshop several times, [here is one example that is inspiring](https://docs.google.com/presentation/d/1Ph5l0EO_OU-AqT4j1Ul08VkuIsUCid2K9btIA6OA0ic/edit?pli=1#slide=id.p){:target="_blank"}. Also a [YouTube Video](https://www.youtube.com/watch?v=lfRVRqdYdjM&ab_channel=JasonMoore){:target="_blank"}
- This is an [excellent report](https://eelc.engineering.ucdavis.edu/using-computational-thinking-to-teach-mechanical-vibrations/) by Jason more on what and how computational thinking was implemented in a mechanical vibrations course.
- Another interesting presentation about coding pedagogy is [](https://docs.google.com/presentation/d/1ua4cjVl2CERimNH1q-S29CSPjno1iGBDLZK6uEM6254/mobilepresent?slide=id.g9df979d7b5_0_73){:target="_blank"}. Also on YouTube [here](https://www.youtube.com/watch?v=4a9NxwAYt0g){:target="_blank"}.

## Email to Participants

_This email was sent to the workshop coordinators (and all participants) one week in advance. It is reproduced here for reference (links adjusted with the final URLs of the IITM-MUDE GitHub organization websites)._

It is a lot of material, but it is designed to give everyone a perspective on what it is like to be a student in MUDE, as well as direct experience with the required platforms/software, which is critical for teachers.

First, we would appreciate a bit of background information via this survey: `<survey closed>`

Then, the idea is that participants do as much of the following as possible:
1.	Read the course website
2.	Read the online textbook (1 theory chapter + 1 programming chapter)
3.	Install the software (miniconda, Visual Studio Code)
4.	Access and complete the Programming Assignment (PA1) 

The process should be-self explanatory by pretending to be a student and visiting the workshop website:
•	[https://iitm-mude.github.io/2024-workshop/](https://iitm-mude.github.io/2024-workshop/){:target="_blank"}
•	The website is set up to be as close as possible to a “real” course website
•	The outline of the workshop is included on this page 
•	All of the websites 

Note that we did our best to make this work as a “real” first course in MUDE, but this didn’t work perfectly. For example, the book chapters may contain MUDE-specific text, a few broken links, and some skills needed by participants may not be introduced (for example, Python/Conda environments, Git, etc.). Hopefully this is not too distracting for participants. In any case, so don’t hesitate to have participants contact us directly.

To access the assignment, participants will need to create a GitHub account. It is not needed to understand what Git or GitHub is, although it will be challenging for those without Jupyter notebook/Python experience. Overall, our hope is that at least a few participants complete the entire assignment as a student, and the rest at least are able to read the materials and access it to understand the scope and experience the different platforms. This will be key for giving us a common point of reference for the duration of the workshop.