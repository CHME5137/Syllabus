# Topics and dates for 2026

Tuesdays and Fridays, 9:50 – 11:30am, Behrakis Room 307.

> **This schedule is tentative and will change.**
> Topics past the next week or so are only a plan: what we cover
> and when depends on how fast we go, what you're interested in, and how the
> projects develop. Expect topics to move, split, merge, or get dropped. The
> dates and the no-class days are fixed; everything attached to them is not.
> This page is the live version — check it rather than a copy you downloaded.

### AI on assignments

Every assignment below carries one of four labels — **Prohibited**, **Permitted**, **Encouraged**, **Required** — with the scope spelled out underneath it.
See [Use of AI](README.md#use-of-ai) in the syllabus for what the labels mean and why they differ from one assignment to the next.
Anything not yet labelled will be before it is assigned.

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
Due Friday September 18.
**AI: Permitted.**
Nothing here is a skill I'm assessing — if a chatbot gets you through an installation error faster, good.

Register for and/or install the following.
* [GitHub Student Developer Pack](https://education.github.com/pack) — you'll need a [GitHub account](https://github.com/join) first, then apply with your Northeastern email.
  It's free, and it includes **GitHub Copilot Student**: AI code completion inside VS Code, plus the JetBrains IDEs, cloud credits, and a long list of other things.
  Verification can take a few days, so don't leave it until Thursday night.
* [Visual Studio Code](https://code.visualstudio.com/)
* [Claude, via the Northeastern portal](https://claude.northeastern.edu/) — free to all NU students; just sign in with your Northeastern account.
  Use this rather than the public claude.ai: it's the instance the University has reviewed and approved, and Northeastern states that Anthropic will not train on your inputs.
  (Restricted or confidential research data still shouldn't go in — see [Use of AI](README.md#use-of-ai).)
* [Anaconda (Miniconda)](https://docs.conda.io/en/latest/miniconda.html)

**You do not need to request an Explorer cluster account this year.** I have asked Research Computing to create
accounts for the whole class, which should take about a week. Once yours exists, try logging in
([Connecting instructions](https://rc-docs.northeastern.edu/en/explorer-main/connectingtocluster/index.html)).

Tell me how you got on using the **Assignment 1: Accounts and software setup** quiz on Canvas.
Re-take it as you finish things — there's no limit on attempts, and it keeps whatever you have already
marked as done, so you'll only be asked about what's outstanding. It doesn't count towards your final grade;
it's how I find out who needs a hand.

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
**AI: Prohibited.**
The whole point is *your* judgement of the book — whether it explains things in a way that works for you.
An AI has not read it the way you have, and cannot tell you whether it helped you.

Ten reviews: six required resources, any three from a second list,
plus one resource you find yourself. Two questions each
(who would you recommend it to, and what are the drawbacks),
then a synthesis saying which is best *for you*.
Graded on judgement rather than coverage — see the rubric on Canvas.

Partially due Friday September 18 (at least the six required).
Finally due Tuesday September 22.

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
* 2-Step Adams Bashforth
  - https://en.wikipedia.org/wiki/Linear_multistep_method#Two-step_Adams–Bashforth
* Convergence
  - order of convergence
  - required accuracy
  - (Richardson extrapolation deferred to later in the term)

## Assignment 3.
**AI: Permitted as a tutor, prohibited as an author.**
Ask it to explain the method, to walk you through the derivation, or to tell you what a NumPy error means.
Do not ask it for the implementation.
Getting an integrator working yourself, from the maths, is the single most transferable thing in this course, and it is worth the struggle.

Implement 2-step Adams Bashforth in Python

## Lecture 5 - Friday September 25
* Bash
  - https://www.w3schools.com/bash/index.php
* Project scope and planning
  - inputs, black box, outputs

## Assignment 4.
**AI: Prohibited.**
It's a short, well-written story and the notes are for you.
A summary of a summary teaches nobody anything.

Read the git parable, take some notes.

## Lecture 6 - Tuesday September 29
* Git
  - Parable and discussion
  - Some demo

## Assignment 5.
**AI: Encouraged.**
Git's interface is famously unfriendly and asking an assistant what a command is about to do — before you run it — is exactly the right use.
Say what you asked and what it told you.

Make a git commit, and pull request, https://github.com/CHME5137/github-assignment

## Lecture 7 - Friday October 2

* More GitHub.
* Project planning - slide summaries.

## Lecture 8 - Tuesday October 6

* More GitHub
* Differential Equations, using SciPy's solve_ivp

## Assignment 6.
**AI: Prohibited.**
It's an interactive puzzle game; handing the puzzles to a model skips the only thing it does.
Build the mental model of branches yourself.

https://learngitbranching.js.org/

## Lecture 9 - Friday October 9
* Explorer cluster
* Catch-up / buffer

## Lecture 10 - Tuesday October 13
* Kinetic Monte Carlo
  - how the rejection free algorithm works

## Assignment 7.
**AI: Prohibited.**
Read the chapter.

Read assigned chapter of Debugging book

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
* Jupytext
* Sensitivity analysis

## Lecture 16 - Tuesday November 3
* Submarine example
   - with sensitivity analysis
* Oxygen pipe combustion example
   - with search for oxidation kinetics

## Lecture 17 - Friday November 6
* Project Proposals

**Projects — AI: Encouraged, with documentation.**
For the project and the final report, use whatever helps you build a better model, and keep a record of how you used it.
Two limits: verify anything safety-related independently, and do not put unpublished or sponsor-restricted research data into a commercial tool.
See [Use of AI](README.md#use-of-ai).

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

- [ ] Bash
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
