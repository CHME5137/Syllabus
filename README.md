# Syllabus
## CHME 5137 – Computational Modeling in Chemical Engineering
Instructor: 	Prof. Richard H. West   r.west@northeastern.edu
Fall 2026: 	Tuesday and Friday, 9:50 – 11:30am,  Behrakis Hall Room 307

Schedule: https://github.com/CHME5137/Syllabus/blob/main/schedule2026.md
The schedule is tentative and will be revised throughout the semester; that page is always the current version.


## Short Catalog Description:
Building on chemical engineering fundamentals, introduces computer programming to allow simulation of physical, chemical, and biological systems.
Covers numerical experiments (eg. Monte Carlo, global sensitivity analysis) to learn the significance of parameters and model assumptions.
Students work on a research or design project throughout the course.
Prerequisites: CHME3312 and CHME3322.

## Longer Description:
This course should equip chemical engineering students to create a computational model of any physical, chemical, or biological system, and perform numerical experiments on the model to learn the significance of parameters and model assumptions.
The course will integrate thermodynamics, kinetics, transport, and mathematics, with applications in chemistry, biology, and materials science.
Faced with a modeling challenge, students will learn to define the problem, split it into sub-systems, develop mathematical models of each sub-system, implement these in Python, and thus construct a model to represent the whole process.
Monte Carlo, uncertainty analysis, and global sensitivity analysis, and Bayesian parameter estimation methods will then be used to test and learn from the model.
Students will also learn essential software carpentry skills, such as using the Linux command prompt, version control, and distributed computing on a cluster.

There will be assignments for each module, but primarily the assessment will be project based, with students working on their project throughout the semester.
The final project report should be publication-quality, and students should expect to be able to submit to a peer-reviewed journal with minimal extra work.

Topics include:
* Introduction to Python computer language, the Anaconda distribution, and a few libraries (NumPy, SciPy, Matplotlib)
* Using the command prompt and Linux terminal, and computer clusters.
* Distributed version control with Git
* Writing scientific reports with LaTeX
* Basic Python programming
* Importing, storing, manipulating, and exporting data
* Solving nonlinear algebraic equations
* Solving ordinary differential equations
* Simulating chemical kinetics and thermodynamics with Cantera
* Regression and machine learning; empirical models.
* Monte Carlo simulations
* Global and local sensitivity analysis
* Bayesian Parameter Estimation
* Debugging

## Course textbook:

No book is required. Prices below are publisher list prices as of September 2026;
they drift, and second-hand copies are usually much cheaper.

**Recommended (not required):**
Modeling and Simulation in Python
Author: Allen B. Downey
Publisher: [No Starch Press](https://nostarch.com/modeling-and-simulation-python), May 2023
280 pages
Print, which includes the ebook: $44.99 (also [on Amazon](https://amzn.to/3R4LaJP))
Ebook alone (PDF, Mobi, ePub): $35.99
But you don't need to buy it: the whole book is [**FREE!** and open-source](https://greenteapress.com/wp/modsimpy/)
from Green Tea Press (CC BY-NC-SA 4.0)
https://allendowney.github.io/ModSimPy/


**Another good choice (not required):**
[A Student’s Guide to Python for Physical Modeling: Second Edition](https://press.princeton.edu/books/paperback/9780691223650/a-students-guide-to-python-for-physical-modeling)
Authors: Jesse M. Kinder & Philip Nelson
Publisher: Princeton University Press, August 2021
Paperback: $36.00
eBook (EPUB or PDF): $36.00
240 pages
http://physicalmodelingwithpython.blogspot.com

### Other books that may be of interest:
[Mathematical Modeling in Chemical Engineering](https://www.cambridge.org/9781107049697)
Author: Anders Rasmuson, Bengt Andersson, Louise Olsson, Ronnie Andersson
Publisher: Cambridge University Press, May 2014
Hard cover: about $75 (see the publisher's page for the current price)
eBook available
192 pages

[Effective Computation in Physics](https://www.oreilly.com/library/view/effective-computation-in/9781491901564/)
Field guide to research with Python.
Authors: Anthony Scopatz, Kathryn D. Huff
Publisher: O’Reilly Media, June 2015
550 pages
O’Reilly no longer sells this in print themselves — it is part of the O’Reilly
online subscription, and print copies are about $60 from other sellers.
http://physics.codes

### Other teaching material:
"Practical Numerical Methods with Python" is an open, online course hosted on an independent installation of the Open edX software platform for MOOCs, first run by Lorena A. Barba, George Washington University. https://github.com/numerical-mooc/

Anselmo Buso and Monica Giomo (2011). Mathematical Modeling in Chemical Engineering: A Tool to Analyse Complex Systems, Numerical Simulations of Physical and Engineering Processes, Prof. Jan Awrejcewicz (Ed.), ISBN: 978-953-307-620-1, InTech, Available from: http://dx.doi.org/10.5772/24806

Software Carpentry - Teaching basic lab skills for research computing.
All of our lessons are freely available under the Creative Commons - Attribution License.
http://software-carpentry.org/lessons/

## TRACE participation
Participation in the Teacher Rating And Course Evaluation (TRACE) survey at the end of the course is important and expected.
But don't wait until then to give feedback!
Tell the instructor as soon as you have an idea that might improve the course.

## Use of AI

*Claude (Opus 5) was used to help draft this policy, combining Department guidance, University policy, and the instructor's own experience and judgment.*

This is an elective, and the goal is AI **fluency**: by the end of the course you should be able to judge not just *how* to use these tools but *when*, and to evaluate what they hand back.
Under the Chemical Engineering Department's AI guidance (approved 25 August 2026) elective courses are "permitted as defined in the course" — so what follows is the definition for this course.
It supplements Northeastern's [Policy 125](https://policies.northeastern.edu/policy125/) and the Provost's [Standards for the Use of Generative AI in Teaching and Learning](https://provost.northeastern.edu/wp-content/uploads/2025/07/Standards-and-Recommendations-for-the-Use-of-Generative-AI-in-Teaching-and-Learning-at-Northeastern-FINAL-07.01.25.pdf).
Where they conflict, University policy governs.

### The principle

Use AI to *learn* something.
Never use AI to *skip* learning something and hand in the artifact.

Those two can produce identical-looking submissions — the same working code, the same paragraph — which is why the distinction has to be one you make honestly, for yourself.
A useful test: tomorrow, without the AI, could you do it again?
If not, you didn't learn it, and the bill comes due later in this course, in your research, and in every situation your career hands you where nobody is there to prompt.

Sometimes struggling with something unaided is simply the fastest way to learn it.
Where an assignment restricts AI, that is why.

### Read the label on each assignment

**The rule that matters is the one on the assignment in front of you, not the one you remember from last week.**
Every assignment carries one of four labels:

| Label | What it means |
|---|---|
| **Prohibited** | Don't use AI on this one. The assignment will say why. |
| **Permitted** | Allowed, within the scope the assignment states. Say what you used. |
| **Encouraged** | Use it, and document how. |
| **Required** | Using AI *is* the assignment. Follow its instructions. |

These vary a lot across the semester, deliberately.
Some assignments are about learning to use AI well — writing code with it, debugging with it, finding your way around an unfamiliar library.
Some let you use it as a tutor to understand a method, while still asking you to write the thing yourself.
Some prohibit it because the struggle is the point.
Check before you start, and ask me if a label is unclear or seems wrong for what you're trying to do.

Labels for the assignments planned so far are in the [schedule](https://github.com/CHME5137/Syllabus/blob/main/schedule2026.md).

### What I expect from you

* **Say what you did.**
  Whenever AI use is permitted, encouraged or required, include a short note with your submission: which tool, and what you used it for.
  A sentence or two usually does it — "Claude wrote the plotting boilerplate, I wrote the integrator", or "I asked ChatGPT to explain what the error message meant".
  For code you paste in more or less as-is, put the credit in a comment at the point of use, exactly as you would for something off Stack Overflow.
* **Verify everything.**
  These tools produce fluent, confident, wrong answers, and they do it most readily at the edges where you are least equipped to notice.
  You are responsible for what you submit, whether or not a model wrote it.
* **Verify safety-critical output independently.**
  Several topics here — combustion, reaction kinetics, anything touching materials handling — are safety-sensitive.
  Departmental guidance is explicit that AI output in these areas needs independent human verification, not a sanity check.
  Submitting an AI-generated hazard or safety analysis as your own work is an integrity violation and a genuinely dangerous professional habit.
* **Don't feed it things that aren't yours to share.**
  Many of you will bring projects from your research groups.
  Unpublished results, anything patentable that hasn't been disclosed yet, and data covered by a sponsor or federal award agreement should not go into a commercial AI tool.
  Pending intellectual property is the highest-stakes case: pasting it into a chatbot can count as prior-art disclosure and can cost your group a patent.
  If your project touches any of this, check with your advisor first — and tell me if it constrains what you can do for the course, because we can work around it.

### What you can expect from me

* **I use AI tools to support my work.**
  Some course materials, examples, and this syllabus, are drafted with AI assistance.
  I read, run, and edit everything before you see it, and I am responsible for its accuracy.
  Where the process is interesting or instructive I would rather show it to you than hide it.
* **The grades I assign are my own.**
  I do not use AI to decide what open-ended work is worth.
* **You may opt in to AI feedback on your drafts.**
  Sometimes I will invite you to run your own work past an AI tool for formative feedback.
  It is your choice and taking it up or declining it has no bearing on your grade.
  If you do use it, mention it in your AI note, and tell me whether the feedback was actually any good.
  The data restrictions still apply: don't put unpublished, sponsor-restricted, or not-yet-disclosed work into a tool to get feedback on it.
* **I do not use AI detection tools.**
  If I have a question about how you produced something, I will ask you to walk me through it — which is usually a good conversation anyway.

### For both of us

* **A chatbot is not office hours.**
  It cannot read my mind, does not know what we covered on Tuesday, and will not notice if you have misunderstood the goal rather than the method.
  Come and talk to me.
* **Budget the time honestly.**
  AI is fast at producing something and slow at producing something good.
  Debugging code you don't understand, written by a model that also doesn't understand it, is one of the worse ways to spend an evening.
  Plan for verification, not just generation.
* **Notice what it costs.**
  Training and running these models consumes real energy and water, and the infrastructure doesn't get sited evenly.
  "Should I use AI for this?" is partly an engineering question about whether it's the right tool for the job, and partly a question about what it costs and who bears that cost.

### How this maps to the AI Readiness framework

Northeastern describes four dimensions of AI readiness.
This course's assignments touch all four:

1. **Understanding AI and Data** — *how does AI work?*
   We point these tools at real modelling problems and look at where and why they fail.
2. **Critical Thinking and Judgement** — *how do I evaluate AI output?*
   The central one for us.
   Numerical answers can be checked against convergence, limiting cases, and conservation laws, which makes this an unusually good course in which to practise not taking an answer on trust.
3. **Ethical and Responsible Use** — attribution, data handling, and the costs above.
4. **Human-Centricity, Emotional Intelligence, and Creativity** — deciding when *not* to reach for it.

## Academic integrity.
Academic dishonesty violates the most fundamental values of an intellectual community and undermines the achievements of the entire University.
Please be familiar with the Northeastern University Academic Integrity Policy which you can find at  https://catalog.northeastern.edu/handbook/policies-regulations/academic-integrity/.
Read it at least once per semester, to remind yourself the details.
Relating to this course:
* Don't pretend someone else's work is your own.
  Don't pretend you did something you didn't.
* Using code snippets found online is a common way to program, but in an academic setting especially it is important that you add a comment where you got it from.
* Collaboration with classmates is usually encouraged in this course, but unauthorized collaboration when explicitly asked not to is cheating.
  In any case: when helping others, try not to just give them your code, but help them figure it out themselves.
  They will learn better, and you will also learn from it.
* AI assistants and coding agents are a substantial part of this course; see [Use of AI](#use-of-ai) above for the full expectations.
  The short version: check the label on each assignment, acknowledge what you used and what for, verify what it gives you, and never use it to skip learning something.

## Student Accommodations
Northeastern University and Disability Access Services (DAS) are committed to providing disability services that enable students who qualify under Section 504 of the Rehabilitation Act and The Americans With Disabilities Act Amendments Act (ADAAA) to participate fully in the activities of the university.
To receive accommodations through DAS, students must provide documentation of a disability that demonstrates a current substantial limitation.
Accommodations are approved based on a review of the information that is submitted and reviews are done on a case-by-case basis.
For more information, visit https://disabilityaccessservices.northeastern.edu.

## Outreach, Engagement, Belonging
Northeastern University is committed to fostering a community of belonging, which is essential to the advancement of our mission of teaching and research.
Our university is stronger as a result of the varied backgrounds, experiences, and perspectives that all members of our global community bring to the pursuit of knowledge.
Embracing this pluralism is not the work of one office, department, or academic unit.
It is a shared responsibility that spans disciplines and boundaries.
By harnessing the power of our differences, we will continue to light the path to bold new ideas and life-changing discoveries.

It is my intention that students from all backgrounds and perspectives will be well served by this course, and that the diverse experiences that students bring to this class will be viewed as an asset.
I welcome individuals of all ages, backgrounds, beliefs, ethnicities, genders, gender identities, gender expressions, national origins, religious affiliations, sexual orientations, socioeconomic background, family education level, ability – and other visible and nonvisible differences.
All members of this class are expected to contribute to a respectful, welcoming and belonging environment for every other member of the class.
Your suggestions are encouraged and appreciated.

For more information the Northeastern University site about Belonging is at https://belonging.northeastern.edu and the Chemical Engineering Department's statement on Belonging is at https://che.northeastern.edu/community/belonging/


## Policy on Sexual and Gender-Based Harassment and Title IX The Northeastern
University [Policy on Sexual and Gender-Based Harassment and Title IX](https://policies.northeastern.edu/policy104/) articulates how the University will respond to reported allegations of Sexual Harassment, Quid Pro Quo Harassment, Sexual Assault, Domestic Violence, Intimate Partner Violence, Dating Violence, Stalking, Gender-Based Harassment and Retaliation, and provides a consolidated statement of the rights and responsibilities under University policies and Title IX, as amended by the Violence Against Women Reauthorization Act of 2013 and the U.S. Department of Education and Office for Civil Rights’ revised regulations in 2020 to the Title IX of the Education Amendments of 1972 (Title IX), 20 U.S.C. § 1681. The policy describes how areas within the University will coordinate the provision of interim remedies and the prompt and effective investigation of allegations of Prohibited Offenses. This policy applies to all members of the University community, including students and prospective students, employees and prospective employees, faculty, staff and volunteers in connection with university activities. It further applies to on- or off-campus behavior involving students. Please visit http://www.northeastern.edu/ouec for a complete list of reporting options and further information.

## Recording of Classes
Classes may be recorded to enable all students to review material covered in synchronous classes. Please contact me if you have any concerns.

## Attendance
Please stay home if you think you might have a communicable illness - we will accommodate your absence.
With that said, please come to class whenever you can - we all benefit from having you here when healthy - and please let me know as soon as possible if you're going to miss a class.
The virtual meetings on the class calendar are there to facilitate making recordings; they are not intended to encourage remote participation or to excuse truancy.

## Course Outcomes
These outcomes are listed on the official syllabus, and include mappings to ABET Student Outcomes (SO’s 1-7).
* Use Python programming language to create simple scripts with conditionals, loops, operations, and functions. (SO 1)
* Learn how to use scientific Python libraries such as NumPy and SciPy to, for example, solve nonlinear equations, solve differential equations, optimize functions, and regress parameters. (SO 7)
* Implement a Kinetic Monte Carlo simulation. (SO 1)
* Use the Linux command prompt to navigate a file system, perform simple file operations, and launch programs.
* Use the Git version control system to initialize, stage, commit, push, pull, branch, and merge.
* Use the LaTeX document preparation system to write publication-quality technical reports. (SO3)
* Create a computational model of any physical, chemical, or biological system. (SO1)
* Perform global sensitivity analysis on a model to learn the significance of parameters and model assumptions. (SO 6, 4)

I aim to be responsive to the interests of the current cohort.
We may get ambitious and add some goals as we go.
