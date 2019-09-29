# Python for text analysis
*As taught at the Vrije Universiteit Amsterdam in the [Humanities Research Master: Linguistics](http://masters.vu.nl/en/programmes/linguistics-research/index.aspx) (track [Human Language Technology](http://www.cltl.nl/teaching/human-language-technology/)) and the [Minor Digital Humanities and Social Analytics (BA)](https://www.vu.nl/nl/studiegids/2017-2018/minor/c-d/digital-humanities/index.aspx).*

This is a practical course in Python, geared towards those who want to get some hands-on experience working with language data.
No knowledge of programming is required or presupposed.
We will work with Python 3.7. If you haven't worked with Python before, we recommend that you install [Anaconda](https://www.anaconda.com/download).

(If you have worked with Python 3 before, be sure to check if Jupyter Notebook
is installed on your machine. We will work extensively with notebooks. Make sure you are working with python 3.7.)

*This course is based on the material used in [previous years](https://github.com/cltl/python-for-text-analysis/releases) and in [this course](https://github.com/kadarakos/python-course).*

## Goals

This course is meant to introduce you to the basics of the Python programming language. There is a lot to discover about Python and programming in general, and you will probably learn something new every day if you continue programming after this course. Our goal for you is to become an independent programmer, who is able to find solutions to new problems. You will..

* Learn how to work with the standard library of Python
*	Learn how to deal with different file types (e.g. plain text, CSV/TSV, JSON, XML)
*	Learn how to use some external libraries (e.g. to analyse texts)
*	Learn how to document and share your code and results

We will focus on readability and understandability, so that you will be able to share your code and results with others, and re-use your code in the future. This is a practical course, in which you will get a lot of hands-on experience. Due to the nature of this course, active participation is required.

## Core principles

Every course has a set of core principles that its teachers adhere to.
We strongly believe in the principles outlined by Mike Bostock in his article
[What makes software good?](https://medium.com/@mbostock/what-makes-software-good-943557f8a488) Here they are:

* **Good software is approachable**. It can be understood completely in independent, easy pieces. You don’t need to understand everything before you can understand anything.

* **Good software is consistent**. It lets you take what you’ve learned about one part and extrapolate it to the rest. It doesn’t self-contradict. It is parsimonious, avoiding superfluous elements.

* **Good software explains itself**. It has affordances for learning and discovery. It is role-expressive and minimizes hidden magic.

* **Good software teaches**. It doesn’t just automate an existing task, but provides insight or imparts knowledge, such as a best practice or a new perspective on a problem.

* **Good software is for humans**. It is cognizant of people and the reality in which they live. It does not expect elaborate and arbitrary rules to be memorized. It anticipates the need for learning and debugging.

## Dealing with problems and what to do if you get stuck

When you are just learning how to program, it sometimes happens that you get stuck and you don't know what to do next. This is normal and even happens to very experienced programmers. Please try to follow these strategies when you get stuck:

* If you get error messages, read them carefully - they are informative! In particular, check the line in which the error occurs. If you don't understand what it says, try to google it (you will most likely find some explanation on Stackoverflow).
* Try to take a step back. Sometimes, you lose sight of the bigger picture when dealing with complicated code. Try to break down the problem into smaller problems without writing actual code (pen and paper can be quite helpful).
* Check the class material for solutions (the chapters treated in the assignment are usually a good start).
* Explain the problem to someone else (e.g. a class mate). Go through the code line by line and explain what it does (See [pair programming](https://en.wikipedia.org/wiki/Pair_programming) and [rubber duck debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging)).
* Finally, take a break! Very often, just having a fresh look at the code helps!
* If none of these steps helped, please ask us for help (see assignment notebooks for contact details).

## Courseware structure

Our materials are structured as follows:

* The `Chapters` folder contains our primary teaching material. Every week, you will work through a subset of these interactive notebooks. It is highly recommended to start looking at the material in preparation for the lectures. If you get stuck with an assignment, first see if you can find the solution in the Chapters.

* The `Assignments` folder contains the assignments that you will be asked to submit during the course.

* The `Exam` folder contains sample exams from previous years.


* The `Extra_Material` folder contains some extra reading about the Python theory which you may use for future reference. It also contains some information specifically related to natural language processing, and examples on how to organize your code and how to create a Flask website.

* The `Data` folder contains all data used in this course and more, as well as the scripts used to obtain
  this data. (So you can see what techniques we used.)

This file serves as the syllabus and a general reference for this course.

## Assignments and Grading


The course is worth 6ECTS and will consist of **4 assignments** and a **final exam**. The assignments have to be submitted after the content and tutorial session of each block (4 in total). In the third session, we will discuss the assignment in class and provide feedback. The assignments and exam are weighted as follows. Please be aware that this is a practical course - therefore, emphasis is placed on the assignments.

| Part    | weight % | | Part    | weight % |
|---------|---------|---|---------|---------|
|Assignment 1|	 9  | | Total Assignments |	60 |
|Assignment 2|	 17  | | Exam	            |	40 |
|Assignment 3|	 17  | |   |	 |
|Assignment 4|	 17  | |   |	 |
| |	   | | **Total**         |	100 |
|**Total Assignments** |	60 | | | |


### Course assignments
You are asked to hand in 4 assignments in total. The deadlines are either on Friday before 23:59 or on Tuesday before 20:00. Submission 1 day after the deadline downgrades your grade by 2 (e.g. a 9 will result in a 7).  After that, the resulting grade is a 1. We have to be strict about this, because we will discuss the assignments in class and we need time to look at your submissions. In addition, the solutions will be discussed in the feedback session and we cannot award points after the solultions have been discussed.

Submission is done through Google Drive (see links to submission forms in the assignment notebooks and in the schedule below).

Please note that a positive grade for the assignments (in total) is a requirement for passing the course. It is possible to do a resit for one assignment (with a maximum grade of 7.5), but you are only eligible to do this if you **submitted all assignments**.

### Final exam
The exam tests your knowledge of the syntax of Python, and your knowledge of the standard library. It serves as an opportunity to show what you've learned and will ensure that you have sufficient knowledge to tackle your own code projects and continue improving your python skills by yourself. You cannot pass the course without a passing grade on the exam. But don't worry: if you are able to finish the assignments, you will be fine on the exam.


## Planning
There are 4 Blocks with associated chapters and assignments:

| Block   | Chapters | Assignment   |
|---------|---------|---------|
| Block 1 | Chapters 1-4 |	 Assignment 1 |
| Block 2 |Chapters 5-11  | Assignment 2 |
| Block 3 |Chapters 12-15 |	Assignments 3a and 3b	|
| Block 4 |Chapters 16-18 | Assignments 4a and 4b |

The schedule for the entire course follows the same structure, illustrated below.

Each block will consist of three lectures.

**Lecture 1**

In the first lecture, we introduce some of the new topics. It is highly recommeded to go through the chapter notebooks in preparation for the classes. After the first lecture, you are expected to start working on the assignment and consult the chapters for things that are unclear to you. Please be aware that the assignments can most likely not be completed in a single day. Also, solving code problems is much easier if you have **sufficient time for breaks**.

**Lecture 2**

In the second lecture, we will further highlight some of the theory and you will have time to work on the assignment in class. Support will be provided by the teachers and student assistants. It is highly recommeded to prepare questions you have about the assignment. We will dedicate time for this in this lecture. You will finish the assignment between the second and third lecture, and hand it in on either Friday or Thursday.

**Lecture 3**

Finally, the third lecture is a feedback session where we will discuss some of the main problems that were encountered in the assignments. We will repeat this cycle 4 times (for each assignment).




| week | what     | when                   | description           | submission link |
|------|----------|------------------------|-----------------------|-------------|
|  36  | lecture  | Monday 09-02-2019 <br> 13:30 - 15:15 | BLOCK 1: Introduction theory | |
|  36  | lecture  | Thursday 09-05-2019 <br> 15:30 - 17:15  | BLOCK 1: Theory and work time |  |
|  36  | DEADLINE  | Friday 09-06-2019 <br> before 23:59  | SUBMIT ASSIGNMENT 1 | [submission form](https://forms.gle/sErunaA1dv9Bf2eHA) |
|  37 | lecture  | Monday 09-09-2019  <br> 13:30 - 15:15 |  BLOCK 1: Feedback assignment |  |
|  37  | lecture  | Thursday 09-12-2019  <br> 15:30 - 17:15 |  BLOCK 2: Introduction theory |  |
|  38  | lecture  | Monday 09-16-2019  <br> 13:30 - 15:15 |  BLOCK 2: Theory and work time |  |
|  38  | DEADLINE  | Tuesday 09-17-2019 <br> before 20:00  | SUBMIT ASSIGNMENT 2 | [submission form](https://forms.gle/CeLm2rfQWGsD9S7v6) |
|  38  | lecture  | Thursday 09-19-2019  <br> 15:30 - 17:15 |  BLOCK 2: Feedback assignment |  |
|  39  | lecture  | Monday 09-23-2019 <br> 13:30 - 15:15  |  BLOCK 3: Introduction theory | **Please download and replace on your computer (right click -> save as)** <br> [Chapter 12 - Importing external modules.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2012%20-%20Importing%20external%20modules.ipynb) <br> [Chapter 13 - Working with Python files.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2013%20-%20Working%20with%20Python%20files.ipynb) <br> [Chapter 14 - Reading and writing text files.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2014%20-%20Reading%20and%20writing%20text%20files.ipynb) <br> [Chapter 15 - Off to analyzing text.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2015%20-%20Off%20to%20analyzing%20text.ipynb) <br> [ASSIGNMENT-3a.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Assignments/ASSIGNMENT-3a.ipynb) <br> [ASSIGNMENT-3b.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Assignments/ASSIGNMENT-3b.ipynb) <br> |
|  39  | lecture  | Thursday 09-26-2019 <br> 15:30 - 17:15  | BLOCK 3: Theory and work time |  | 
|  39  | DEADLINE  | Friday 09-27-2019 <br> before 23:59  | SUBMIT ASSIGNMENT 3 | [submission form](https://forms.gle/JiDmuLLKxbjgA8Sn8) |
|  40  | lecture  | Monday 09-30-2019 <br> 13:30 - 15:15  |  BLOCK 3: Feedback assignment |  |
|  40  | lecture  | Thursday 10-03-2019 <br> 15:30 - 17:15  |  BLOCK 4: Introduction theory | **Please download and replace on your computer (right click --> save as):** <br> [Chapter 16 - Data formats I (CSV and TSV).ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2016%20-%20Data%20formats%20I%20(CSV%20and%20TSV).ipynb) <br> [Chapter 17 - Data formats II (JSON).ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2017%20-%20%20Data%20formats%20II%20(JSON).ipynb) <br> [Chapter 18 - Data formats III (XML).ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Chapters/Chapter%2018%20-%20Data%20formats%20III%20(XML).ipynb) <br> [ASSIGNMENT-4a.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Assignments/ASSIGNMENT-4a.ipynb) <br> [ASSIGNMENT-4b.ipynb](https://raw.githubusercontent.com/cltl/python-for-text-analysis/master/Assignments/ASSIGNMENT-4b.ipynb) |
|  41  | lecture  | Monday 10-07-2019 <br> 13:30 - 15:15  |  BLOCK 4: Theory and work time |  |
|  41  | DEADLINE  | Tuesday 10-08-2019 <br> before 20:00  | SUBMIT ASSIGNMENT 4  | [submission form](https://forms.gle/ioBtZFoT5iwvn6mX9) |
|  41  | lecture  | Thursday 10-10-2019  <br> 15:30 - 17:15 | BLOCK 4: Feedback assignment |  |
|  42  | lecture  | Monday 10-14-2019 <br> 13:30 - 15:15  | self-study (no class) |  |
|  42  | lecture  | Thursday 10-17-2019  <br> 15:30 - 17:15 |  Q&A session |  |
|  43  | EXAM  | Monday 10-21-2019 <br> 15.15-18.00  |  EXAM |  |


## Plagiarism
Basically, please don't cheat. For the weekly assignments, let us know in the comments if you have worked together with someone or if you used code from online sources, such as [stackoverflow](http://stackoverflow.com/). If you found some useful code online, do try to understand what that piece of code does. If it looks 'complicated', we expect you to provide comments in the code explaining what it does.

If you use code you found online in an assignment, please indicate it in the following way:

###Taken from [link] [date]

[code]

\###

Please use a similar format to indicate that you have worked with a classmate (e.g. mention the name instead of the link).
