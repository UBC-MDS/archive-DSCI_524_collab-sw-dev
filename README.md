# DSCI 524: Collaborative Software Development

How to exploit practices from collaborative software development techniques in data scientific workflows. Appropriate use of the software life cycle, unit testing / continuous integration, and packaging for use by others.

## Learning Outcomes

By the end of the course, students are expected to be able to:

* interpret software licenses to understand how others' projects can be used
* complete a project that demonstrates appropriate use of collaborative software development processes and tools, including:
  * packaging code for use by others, including the specification of dependencies/requirements.
  * using distributed version control and issue tracking to manage the multi-person project.
  * writing comprehensive test suites 
  * handling exceptional cases in a function or method with exceptions or assert statements
  * selecting software licenses that best suit the project

## Course Format
This is a project-based course where you will work collaboratively in groups to develop a Python and a R software package. In lecture and lab, we'll work on the skills and concepts that you need to learn to complete the project. 


## Assessments

| Deliverable | % grade |
|------------|----------|
| In-class participation | 10% |
| Project proposal + Milestone1 | 20% |
| Milestone 2 | 20% |
| Milestone 3  | 20% |
| Final project | 20% |
| Team work | 10% |

| Lab | topic | lab/milestone due dates |
|-----|------|-------------------|
| 2018-02-05 | Project Proposal and Milestone 1: writing unit tests for functions & setting up package structure | 2019-02-09 |
| 2018-02-12 | Milestone 2: writing the functions for the package  | 2019-02-16 |
| 2018-02-26 | Milestone 3: writing any additional tests that are required, selecting a license | 2019-03-02 |
| 2018-03-05 | Milestone 4: complete project including exception handling and setting up continuous integration testing |  2019-03-09 |
| NA | Team project reflection |  2019-03-10 |



## Lecture Schedule
| Date       |  Day  | Topic | Instructor | Required pre-work | Readings and Resources|
|------------|-------|-------|------------|-------------------|-----------------------|
| 2019-02-04 |  Mon  |packaging code in Python: pip (Python), blackbox unit testing | Meghan | Required pre-class work: <ul><li>Register for [Software Engineering: Introduction](https://courses.edx.org/courses/course-v1:UBCx+SoftEng1x+1T2018/course/) by Reid Holmes on edX</li><li>In the Testing module, watch these videos (total of ~22 minutes of video)<ul><li>Why Test?</li><li>Properties and Process > Terminology</li><li>Properties and Process > Properties of Tests</li><li>Properties and Process > Kinds of Tests</li></ul><li>Read the first three sections the [Testing reading](http://web.mit.edu/6.005/www/fa16/classes/03-testing/) from MIT 6005 (up to and including the Choosing Test Cases by Partitioning section)</li><li>[DSCI 524 welcome survey](https://ubc.ca1.qualtrics.com/jfe/form/SV_6hs0YuEmll1qMtv)</li></ul> | <br>Resources<ul><ul><li>[Python modules and packages](https://docs.python.org/3/tutorial/modules.html)</li><li>[Hitchhiker's Guide to Python packaging](http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/index.html)</li><li>[Distributing Python modules](https://docs.python.org/3/distributing/index.html)</li><li>pytest [documentation](http://doc.pytest.org)</li><li>[R Packages: Testing](http://r-pkgs.had.co.nz/tests.html)</li><li>[Testing reading](http://web.mit.edu/6.005/www/fa16/classes/03-testing/) from MIT 6005</ul></ul> |
| 2019-02-06 |  Wed  | packaging code in R: CRAN, devtools  | Jenny | <ul> <li>[R packages tutorial1](http://stat545.com/packages06_foofactors-package.html)</li><li>[R packages tutorial2](http://stat545.com/Classroom/notes/cm105.nb.html)</li> </ul>| <ul> <li>[R Packages](<https://r-pkgs.org>) <li>[The Whole Game](https://r-pkgs.org/whole-game.html) chapter <li>[rOpenSci's packaging guide](https://ropensci.github.io/dev_guide/) <li>Jenny live code: [bit.ly/jenny-live-code](http://bit.ly/jenny-live-code) <li>[Slides *dated-but-indicative*](https://speakerdeck.com/jennybc/ubc-stat545-2015-writing-your-first-r-package) <li> [foofactors package (pre-baked)](https://github.com/jennybc/foofactors) </ul>|
|   2018-02-11 | Mon | collaborative features of version control: branching, merging, pull requests; issue tracking, milestones, project management, code reviews | Meghan | Please read sections 3.1, 3.2, 3.3 from [Chapter 3 of Pro Git](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) |<ul><li>[Pro Git Chapter 3, Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)</li><li>[Bug Writing Guidelines](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Bug_writing_guidelines) from Mozilla</li></ul> |
| 2018-02-13| Wed | continuous integration, whitebox unit testing, integration testing| Meghan | none | |
| 2018-02-25  | Wed | software licenses | guest lecture by [Paul Cyr](https://www.linkedin.com/in/paul-cyr-9403aa17) and [Meir Deutsch](https://www.linkedin.com/in/meir-deutsch-811a781) from UBC's University Industry Liaison Office  | *no pre-work*  | <ul><li>[choosealicense.com](https://choosealicense.com)</li><li>[Open Source Initiative](http://www.opensource.org)</li></ul>|
| 2018-02-27 | Wed |  meta-programming in R | Jenny | *no pre-work* | <ul> <li> [Programming in the tidyverse](https://speakerdeck.com/lionelhenry/programming-in-the-tidyverse) talk (PDF of slides) <li> [Tidy evaluation](https://tidyeval.tidyverse.org) bookdown site <li> [Working with names and expressions in your tidy eval code](https://resources.rstudio.com/rstudio-conf-2019/working-with-names-and-expressions-in-your-tidy-eval-code) talk (20 mins) <li> Tidy eval in context talk [20 min video](https://resources.rstudio.com/rstudio-conf-2019/lazy-evaluation), [slides on SpeakerDeck](https://speakerdeck.com/jennybc/tidy-eval-in-context) <li>Jenny live code: [bit.ly/jenny-live-code](http://bit.ly/jenny-live-code) </ul> |
| 2018-03-04 | Mon |  function signatures, function documentation, exception handling and including info about exceptions in the documentation | Meghan | <ul><li> install mypy (in VSCode, open a terminal and use 'pip install mypy')</ul> | <ul><li>[Errors and Exceptions from The Python Tutorial](https://docs.python.org/3/tutorial/errors.html)</li><li>[Exceptions and Debugging from Advanced R by Hadley Wickham](https://adv-r.hadley.nz/debugging.html)</li> <li>[Debugging and tracing info from Jenny's workshop material](https://whattheyforgot.org/debugging-r-code.html)</li></ul> |
| 2018-03-06  | Wed | tracing control flow when exceptions are thrown| Meghan | none | activities are in the lectures folder|

Time and location: Mondays and Wednesdays 10:30am- 11:50am in DMP 301

