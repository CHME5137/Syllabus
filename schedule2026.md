# Topics and dates for 2026

Tuesdays and Fridays, 9:50 – 11:30am, Behrakis Room 307.

> **This schedule is tentative and will change.**
> Topics past the next week or so are only a plan: what we cover
> and when depends on how fast we go, what you're interested in, and how the
> projects develop. Expect topics to move, split, merge, or get dropped. The
> dates and the no-class days are fixed; everything attached to them is not.
> This page is the live version — check it rather than a copy you downloaded.

Each assignment on Canvas says whether and how you may use AI on it;
see [Use of AI](README.md#use-of-ai) in the syllabus for what the labels mean.

Fall 2026 term runs Wednesday September 9 to Sunday December 13.
Neither Indigenous Peoples Day (Monday October 12) nor Veterans Day
(Wednesday November 11) falls on a class day this year, so the only
cancellation is the Friday of fall break. That leaves 26 meetings,
one fewer than 2025.

## Lecture 1 - Friday September 11
* Introduction
* Meeting each other
* What we hope to learn, what we expect to cover
* Why modeling?
  - discovery (choose better experiments [sensitivity and uncertainty analyses]; do the impossible [ask "what if?"])
  - design (predict and simulate)

## Assignment 1
Register for and install GitHub, VS Code, Claude and Miniconda, then log in to Explorer. Due Friday September 18. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3500413).

## Lecture 2 - Tuesday September 15

Simple Python.
* Python basics
  - types (int, float, str)
  - lists, arrays
  - loops
  - functions
* Jupyter notebook
* VSCode
* CodingBat Python practice

## Assignment 2. Python book reviews.
Ten resources, and which is best for you. Partially due Friday September 18 (at least the six required). Finally due Tuesday September 22. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496809).

## Lecture 3 - Friday September 18
* Differential equations
  - concept
  - discretization
  - Simple Euler method
* Convergence

## Lecture 4 - Tuesday September 22
* Book Reviews
* Managing your Python environment
  - why not to install into the global environment
  - `venv`, `pip`, `conda`; `requirements.txt` and `environment.yml`
  - Jupyter kernels, and why `pip install` and your notebook can disagree
  - `module load` on the Explorer cluster
  - https://softwaredevengresearch.github.io/software-development-research/managing-environment.html
* ~~2-Step Adams Bashforth~~ (moved to Lecture 5)
* ~~Convergence~~ (moved to Lecture 5)

Environments took the whole second half, so Adams–Bashforth moved to Lecture 5.

## Assignment 3.
Implement 2-step Adams–Bashforth in Python, and find out when it goes unstable. Due Friday October 2. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496808).

## Lecture 5 - Friday September 25
* 2-Step Adams Bashforth
  - https://en.wikipedia.org/wiki/Linear_multistep_method#Two-step_Adams–Bashforth
* Convergence
  - order of convergence
  - required accuracy
* Bash
  - `$PATH`, `which`, `source`, and what `module load` and `activate` actually do
  - https://www.w3schools.com/bash/index.php

## Unix tutorial, in three parts
Work through an Explorer edition of the Surrey *UNIX Tutorial for Beginners*; each part ends in a short quiz. Part A due Friday October 2, part B Tuesday October 6, part C Tuesday October 13. [On Canvas](https://northeastern.instructure.com/courses/259534/modules/1925166).

## Assignment 4.
Read the git parable, take some notes. Due Tuesday September 29. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496813).

## Lecture 6 - Tuesday September 29
* Git
  - Parable and discussion
  - Some demo

## Assignment 5.
Make a git commit, and pull request, https://github.com/CHME5137/github-assignment. Due Tuesday October 6. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496814).

## Lecture 7 - Friday October 2

* Project ideas
  - inputs, black box, outputs
  - brainstorm: lots of one-slide ideas, in a shared deck
* GitHub lab: fork, clone, branch, commit, push, pull request, and merge conflicts

Tuesday's lab didn't fit, so it took the second half, and notebooks in git moved to
Lecture 9 to go with jupytext.

## Lecture 8 - Tuesday October 6

* GitHub assignment: reviewing and merging pull requests, and merge conflicts
* Differential Equations, using SciPy's solve_ivp
  - required accuracy: `rtol` and `atol`
  - stiff problems: `method=`
  - rabbits and foxes, as a coupled system (homework)

## Rabbits and foxes with solve_ivp
Rabbits and foxes again, with SciPy's `solve_ivp`: events, tolerances and methods. In your fork of https://github.com/CHME5137/differential-equations. Due Tuesday October 13. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3520567).

## Assignment 6.
Learn git branching at https://learngitbranching.js.org/. Due Friday October 9. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496815).

## Lecture 9 - Friday October 9
* Project planning - slide summaries.
  Before class, add one fuller idea slide to the deck from Lecture 7.
* Jupyter notebooks in git: what goes wrong, and habits that help
  (read [notebooks-and-git.md](https://github.com/CHME5137/github-assignment/blob/main/notebooks-and-git.md) first)
* Jupytext: pair each notebook with a `.py` script,
  for clean diffs and merges, and to run a notebook as a batch job
* Explorer cluster: batch jobs
  (the rest of Explorer was covered in Lectures 2–4)

## Lecture 10 - Tuesday October 13
* Kinetic Monte Carlo
  - how the rejection free algorithm works

## Assignment 7.
Read assigned chapter of Debugging book. Due Friday October 16. [On Canvas](https://northeastern.instructure.com/courses/259534/assignments/3496811).

## Lecture 11 - Friday October 16
* Debugging

## Lecture 12 - Tuesday October 20
* Probability
* Bayes' theorem
* Parameter estimation
* Regression

## Lecture 13 - Friday October 23

* Regression
  - Linear regression (`scipy.stats.linregress`)
  - Nonlinear regression (`scipy.optimize.curve_fit`)
  - Polynomial regression
  - Regression with uncertain x values (eg. `scipy.odr`)

## Lecture 14 - Tuesday October 27
* PDEs and BVPs

## Lecture 15 - Friday October 30
* Sensitivity analysis

## Lecture 16 - Tuesday November 3
* Submarine example
   - with sensitivity analysis
* Oxygen pipe combustion example
   - with search for oxidation kinetics

## Lecture 17 - Friday November 6
* Project Proposals

## Lecture 18 - Tuesday November 10
Prof West at AIChE Annual Meeting (November 8-12, Minneapolis).
Work on project proposals.

## Lecture 19 - Friday November 13
* LaTeX

## Lecture 20 - Tuesday November 17

* Cantera.

## Lecture 21 - Friday November 20

* Project selections.

## Lecture 22 - Tuesday November 24

* Work on projects. With help.

## Fall Break - Friday November 27

No class. (Fall break runs November 25-29; classes resume Monday November 30.)

## Lecture 23 - Tuesday December 1

* Population Balance Models.

## Lecture 24 - Friday December 4

* Machine Learning

## Lecture 25 - Tuesday December 8

* Presentations.

## Lecture 26 - Friday December 11

* Remaining presentations
* Bayesian Parameter Estimation

### Final Project Reports due December 10th

Due 11:59pm the night before the last lecture. (Last day of full-semester
classes is December 13; the final exam period runs December 14-20.)


### Homeworks
This is a list of possible homework assignments that we might pick from.
Nothing here is assigned until it's announced in class.

- [x] Bash
- [ ] Book reviews
- [ ] Rabbits and foxes diffusing
- [ ] CodingBat Python practice
- [ ] Runge-Kutta RK4 and convergence
- [ ] Flesh out a project
- [ ] Improve a project outline
- [ ] Kinetic Monte Carlo
- [ ] Regression
- [ ] Git and github
- [ ] Explorer
- [ ] Sensitivity
- [ ] LaTeX

### Topics
This is not a manifesto or contract, but a reminder list of things it would be cool to cover. i.e. it's too long and we won't cover them all.

- [ ] Python
- [ ] CodingBat
- [ ] Convergence
- [ ] ODEs
  - [ ] Simple Euler
  - [ ] RK4
  - [ ] SciPy
- [ ] Kinetic Monte Carlo
  - [ ] Code optimization
- [ ] PDEs
- [ ] Debugging
- [ ] Regression
- [ ] Bayesian Parameter Estimation
- [ ] Bash
- [ ] Explorer cluster
- [ ] LaTeX
- [ ] Population Balance Modeling
- [ ] Sensitivity Analysis
- [ ] Cantera
- [ ] Pandas (polyethylene?)
- [ ] Machine Learning
- [ ] VSCode
- [ ] Programming with LLMs and coding agents

## Other resources

The 2025 schedule is at https://github.com/CHME5137/Syllabus/blob/main/schedule2025.md

- Co-Pilot
  - https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming/tree/main/Getting-Started-with-GitHub-Copilot
