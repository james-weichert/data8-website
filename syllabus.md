---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Course policies and information.
---

# Syllabus &#x1F4D6;
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Welcome	&#x1F44B;

Welcome to Data 6 Summer 2022! On behalf of the Data 6 course staff, we’re excited to be teaching you this summer and hope you enjoy this class as much as we enjoy teaching it. Whether you’re a first-time college student or a seasoned veteran student, Data 6 is the perfect course to get started with coding and data science. This course is specifically designed without any prerequisites or assumed prior knowledge of computer science or statistics — we will teach you **everything** you need to succeed in this class and prepare you for further data science and/or computer science classes. Along the way, you’ll gain practical experience working with data and using Python code to extract useful insights from real-world data sets. Even if this is the last data science class you ever take, we hope you’ll learn useful skills that you can apply to your own major or field of study, especially in the social sciences.

One of—in our opinion—the best parts of data science at Berkeley is the opportunity to learn from other students. All members of course staff are current undergraduates at UC Berkeley who have taken other data science classes and have experience teaching in classes like [Data 8](http://data8.org/). Believe it or not, we were all once students taking introductory data science and computer science classes and were just as confused and overwhelmed as you. We know what it’s like to step into a class feeling out of place, but also know what it’s like to finish a class feeling fulfilled and confident in your ability to succeed in data science and computer science at Berkeley. You are here for a reason — you are all talented students and are all more than capable of being great data scientists, computer scientists, engineers, social scientists, and more. We want to do our best to support you this summer, so please don’t hesitate to reach out to any of us via email or [Ed](https://edstem.org/us/courses/22794/discussion/) if you have any questions or concerns.

We are continually revising course materials, assignments, and policies to improve the course and make this the best learning experience for you all. We welcome constructive feedback about what we can improve, and will try our best to incorporate your feedback into future lectures and assignments.

Again, welcome to Data 6 — we can’t wait to meet you and are super excited to be teaching you this summer!

Best,
[James](https://data6.org/su22/staff/#instructors) and [Will](https://data6.org/su22/staff/#instructors)

<hr>

## About	&#x1F9D0;

From the course catalog: Data 6 is an introduction to computational thinking and quantitative reasoning, designed to prepare students for further coursework in data science, computer science, and statistics (in particular, Foundations of Data Science, Data 8). This course emphasizes the use of computation to gain insight about quantitative problems with real data from the social sciences.

Data 6 uses the Python programming language to teach computation. It also uses the [Jupyter Notebook](https://jupyter.org/) environment, which makes it easy to get started with programming without needing to use a text editor or terminal and is very popular in data science applications. Jupyter Notebooks are also used in courses like [Data 8](http://data8.org/) and [Data 100](https://ds100.org/), so it’s helpful to get a head start using them.

This class serves a different purpose than several other classes that may sound similar. Specifically:
* [**Data 8**](http://data8.org/): Data 8 (Foundations of Data Science) is the first course in the requirement sequence for the UC Berkeley data science major and minor. While some of the topics in Data 8 are similar, Data 6 does not cover nearly as much statistics and inference as Data 8. Instead, we dive deeper into the mechanics of Python and how to use Python to generate insights from data using real-world data sets (mostly from the social sciences). After taking Data 6, you will be more than well-equipped to take (and succeed in) Data 8.
* [**CS 10**](https://cs10.org/sp22/): CS 10 (The Beauty and Joy of Computing) is a similar class to Data 6 in that it is intended as an introduction to computing that assumes no prior experience with programming. However, CS 10 focuses less on Python and data science, and more on abstract ideas in computer science. It is a fantastic alternative (or complement) to Data 6.
* [**CS 61A**](https://cs61a.org/) and [**CS 88**](https://cs88-website.github.io/sp22/): Both CS 61A (Structure and Interpretation of Computer Programs) and CS 88 (Computational Structures in Data Science) also teach Python, but serve a slightly different purpose than Data 6 — namely, these courses are designed to introduce students to computer science, not to computing *in* data science. They cover the Python language in far greater detail than we will, but they do not cover how to work with real-world data. These courses are also substantially more fast-paced than Data 6, so they are excellent courses to take after Data 6 and/or Data 8.

For the Summer 2022 iteration of Data 6, we have rearranged the order of some topics to more gradually ramp up to more advanced concepts and give you the tools to work with real-world data earlier on in the semester. This new ordering means that some of the lectures will be out of sync with the ordering of materials from previous iterations of the course. If you want to review material from past semesters, just keep in mind that you may not have learned certain concepts yet, and that’s perfectly ok.

The rough topic breakdown for this summer is as follows:
* Week 1: Introduction to Python and Jupyter Notebooks
* Week 2: Data Visualization
* Week 3: Working with real-world tabular data using the `datascience` Python library
* Week 4: Python Functions and Control
* Week 5: More Python (and more real-world applications)
* Week 6: Probability and Simulation

Lecture slides will be posted to the website right before each lecture to allow you to follow along if you want. You are also welcome to experiment with the concepts you’ve learned by writing or editing code in the Jupyter Notebooks we provide for each lecture (feel free to change it however you want — we promise you won’t break anything). **There is no one textbook that covers the content of this course the way we intend on covering, so all of the material you’ll need to succeed in Data 6 will be presented in lecture, labs, homeworks, and discussions.** If you want to review additional material, we will post optional readings from online textbooks for other courses (e.g. Data 8) along with most lectures. You can read more [here](https://data6.org/su22/resources/).

## Logistics &#x1F5D3;

**Lecture**: Mondays & Wednesdays, 10-12PM; Tuesdays & Thursdays, 10AM-11AM in [Wheeler](https://www.berkeley.edu/map?wheeler) 212

**Lab**: (Usually) Tuesdays & Thursdays, 11AM-12PM in [Wheeler](https://www.berkeley.edu/map?wheeler) 212

**Discussion**: Fridays, 10AM-12PM in [Dwinelle](https://www.berkeley.edu/map?dwinelle) 105 & 130

**Office Hours (Optional)**: Tuesdays & Thursdays, 1PM-3PM in [Evans](https://www.berkeley.edu/map?evans) 6

The full schedule is available on the [Schedule](http://data6.org/su22/schedule) page.

## Course Components	&#x1F4D2;
While this course is designed to fit into a six-week summer session, the pace of Data 6 over the summer is roughly twice as fast as the pace of a 3-unit class in the fall or spring semester. To compensate for the fast pace of the summer, we have more lectures and lab time than during the academic year. We do our best to make sure that we spend enough time on each concept, and that the material is approachable for all students. But if you feel like things are going too fast, let us know and we will try to slow down!

Part of making sure that we're providing the best learning experience for you is checking in on your progress and getting feedback about the pace of the class. Each week, we will send out a survey asking for your feedback on how comfortable you are with the previous week's concepts and how we can better support you going forward. Responding to the weekly surveys constitutes 5% of your [final grade](https://data6.org/su22/syllabus/#grading), but the surveys are graded on completion. The surveys will be anonymous and we encourage you to be honest about how you're feeling and how you're doing in the class so we can better support you.

All of the course components (lectures, labs, discussions, homeworks, office hours, and quizzes/exams) are designed to provide valuable learning experiences and help you master core concepts in data science and computing.      

### Lecture
There will be four lectures per week. In lecture, we’ll introduce you to new ideas and concepts in programming and data science. Lectures will be recorded and posted after class for you to review in the future. All lecture resources (slides, code, supplemental readings) will be linked on the course website. We will begin on [Berkeley Time](https://www.sfgate.com/bayarea/article/Berkeley-Time-10-minutes-late-university-policy-13182558.php) (10 minutes after the hour), and **attendance is mandatory**. In the event that you have to miss a lecture, let us know and you can catch up by watching the lecture recording later.

During each lecture, there will be a few points at which we stop and ask you to answer a short question. We call these questions Quick Checks. They serve two purposes:
* For us to get a gauge of how well the class understands the material we’re currently covering
* For you to get a gauge of how well you understand the material we’re currently covering

**Quick Checks are graded on completion, not correctness**. It’s not important to get these questions right on your first try – but it’s important to try them. You will be given time in lecture to answer them. If you have to miss a lecture for whatever reason, just answer that lecture’s Quick Check whenever you catch up on the lecture.

Additionally, in some lecture notebooks, we will post optional practice problems. These are not required, but we recommend that you complete them.

### Lab
There are (usually) two lab sections per week that follow immediately after the Tuesday and Thursday lectures. In lab, we’ll spend the first ~10 minutes going over some demos that are relevant to that week’s material. You'll spend the remaining ~40 minutes working on the lab notebook that is available on the course website. Lab notebooks will give you an opportunity to apply the concepts you learn in lecture to real-world data and to practice coding in Python. While working on lab notebooks is required, **the notebooks themselves are not graded** — so don't worry if you don't finish the full notebook by the end of the lab.

Lab notebooks are also great opportunities to work on problems with your peers. The hope is that by participating and collaborating during labs, you will be able to better understand the concepts and finish your homework more quickly. **Discussing questions and approaches to problems with classmates is highly encouraged**, but please note that you must always write your own answers and code in your jupyter notebooks, both on labs and homeworks.

### Discussion
Each Friday, we will have a discussion section led by your [uGSI](https://data6.org/su22/staff/#undergraduate-student-instructors-ugsis). In these sections, we will discuss ethical and social issues in computing and data, such as privacy and algorithmic bias. To prepare for these discussions, you might be asked to complete some short prep work consisting of a few short readings. We will posts the readings on the course website at the beginning of the week.

On some Fridays, we might have guest speakers or do review for an upcoming quiz or final.

**Participation during discussion (and other parts of the course) is part of your grade.** We hope to have you drive our discussions, so we encourage you to ask questions, raise new points, or make connections to your own experiences.

Sometimes, discussion topics will include content covering sensitive issues, like racial bias in algorithms or the implications of data-driven policing and sentencing decisions. These issues are important to discuss because they are real-world consequences of data science and algorithms. Part of being a good data scientist is understanding the impact of your work, and working to mitigate the disparate impacts that data science might have on certain populations. We also always welcome feedback on how we approach and talk about these topics as instructors.

### Homework
You learn data science by **doing** data science, not by just listening to lectures or reading a textbook. As such, homework assignments will be your primary source of learning in this class.

Homeworks will consist mainly of programming problems that challenge you to apply the skills you learned in recent lectures to accomplish tasks involving real data. The homeworks use autograder tests that will tell you if you are on the right track. There are additional autograder tests that will not be visible to you that we will use to grade your work, so don't assume that just because the public autograder tests are passing that your answers are all correct. **Always remeber to double check your code!** Most homeworks will also include a few written response problems, where you will have to type your answer in text. These problems will be manually graded by a human on course staff, and often there is no single 'right' solution. We are mainly looking for you to show understanding of what you are doing and to explain your reasoning behind certain answers.

Homeworks, like all course materials, can be accessed by clicking on the correct link on the course website. Clicking on a link to a homework will bring you to your own copy of the homework notebook in DataHub, which allows you to work on the homework online. Once you're done with the homework, you will run the very last cell in the notebook to generate a `.zip` file, which you will then upload to Gradescope so that we can grade it. We will go over this process in more detail in lab.

There are 5 homework assignments, which correspond to roughly one per week. In general, homework assignments will be released on Thursday afternoon and will be due the following Thursday at 11 PM. See the [Policies](#policies-) section for our extensions and late submissions policy, as well as the homework drop policy.

Homework assignments are meant to be completed individually, but we encourage you to discuss approaches with others; see our [Academic Honesty policy](#academic-honesty) below for acceptable forms of collaboration.

### Office Hours and Ed
In addition to lecture, lab and discussion, we will host office hours each week. In office hours, you will get a chance to ask questions about assignments and work with your peers on problems. You can also ask conceptual questions about lecture material. See the [course schedule](http://www.data6.org/su22/schedule) for more details about office hours.

While office hours are not mandatory, we **highly recommend** attending them regularly. Most students find that office hours help them to work through assigments, and find other students who are working on the same problems. Attending Data 6 office hours is also a great way to familiarize yourself with the office hours environment for a lot of data science and computer science classes, where you will have to rely on working with peers due to a limited number of available TAs.

Aside from office hours, we also encourage you to ask and answer questions about assignments and concepts on Ed. You can think about Ed as "24/7 office hours". While you shouldn't be surprised if a member of course staff answers your question at 1 AM, please be patient after posting a question on Ed — we have a lot of questions to answer. It also helps to search Ed to see if someone else has asked a similar question, and if that question has already been answered.

### Quizzes and Exams
This course does not have a midterm. Instead, we will have two short quizzes in class, each worth 10% of your final grade. Quizzes are **not** cumulative, so they will focus only on (roughly) the past two weeks worth of lecture content. Quizzes are intended to test your understanding of key concepts, but are not intended to 'trick' you. We will also hold review sessions during discussion before each quiz to help you prepare. The tentative dates for the quizzes are:
* Quiz 1: Monday, July 18th
* Quiz 2: Monday, August 1st

We will have a final exam during the campus-assigned slot: **Friday August 12th, 10AM - 12PM.** The exam is worth 15% of your grade, and **taking the exam is a requirement for passing the class.** Unlike the quizzes, the final exam will be cumulative.

We will post more details about quizzes and exams on Ed.

## Communication	&#x1F4AC;

This class **does not** use bCourses — all of the materials and assignments for the class can be found on the Data 6 website.

For class communication, we will be using Ed Discussion (or simply “Ed,” as we will call it), the campus’ discussion platform. Ed is where you will see announcements from course staff, ask questions about course material, and get help from staff and other students on assignments and concepts. Ed allows students to respond to questions from other students, so we hope you will help out your classmates by responding to questions you have the answer to, or asking questions about things you’re confused about. It’s likely that other students have many of the same questions as you! Please review the Ed etiquette guidelines before posting on Ed.

You will be added to Ed automatically, but email James ([jweichert@berkeley.edu](jweichert@berkeley.edu)) if you’re not sure how to access it.


## Technology &#x1F4BB;

We will be using several websites this semester. Here’s what they’re all used for:
* [Course Website](https://data6.org/su22/): where all content and assignments will be posted.
* [Ed](https://edstem.org/us/courses/22794/discussion/): discussion forum where all announcements will be sent, and where all student-staff and student-student communication will occur.
* [DataHub](http://datahub.berkeley.edu/): we use DataHub to host jupyter notebook assignments. Don’t worry too much about how this works, just access all assignments by clicking the link on the Data 6 website.
* [Gradescope](https://www.gradescope.com/courses/402405): where all homeworks will be submitted and all grades will live. (We don’t use bCourses)

Since all Data 6 material is accessible online, there are no requirements in terms of specific computer hardware. All you need is a laptop with internet and a web browser (Google Chrome or Firefox tend to work best). If you looking to purchase a laptop for college, Prof. Yan put together this [helpful guide](https://docs.google.com/document/d/1avUDkT5yvW_XycvVYP9LevJP791a9CdxuCAzQB1tYfc/edit?usp=sharing).

Here are a few helpful resources when it comes to technology:
* Read this [Berkeley IT website](https://technology.berkeley.edu/wi-fi) to learn how to connect to the campus WiFi network, Eduroam.
* The [Student Technology Equity Program](https://technology.berkeley.edu/STEP) provides free laptop loans for students.

## Policies &#x1F4D1;

### Grading

Here's how we will calculate your final grade:

| **Component** | **Weight** | **Notes** |
| Participation | 15% | Participation in lecture, labs, and discussions |
| In-Class Quick Checks | 5% | Graded on completion, no drops |
| Weekly Surveys | 5% | Graded on completion, no drops |
| Homeworks | 40% | 5 homeworks with 1 homework drop (10% each) |
| Quizzes | 20% | 2 quizzes (10% each) |
| Final Exam | 15% | In-Class on 8/12 |

### Participation
Participation is 15% of your final grade, so we expect you to participate during labs and discussion sections. Participation can take a variety of forms, including asking questions, working with peers on problems, volunteering answers, and completing practice problems.

You can also get credit for participation by asking questions during lecture, and asking and answering questions on Ed.

### Weekly Surveys
Each week, we will send out a survey to hear how you’re doing, both academically and personally. We will use survey responses to better support students throughout the semester, identify concepts we need to review, and generally improve the course.

The surveys will be anonymous and we encourage you to be honest about how you're feeling and how you're doing in the class so we can better support you. Since the surveys are anonymous, if you need individual support (e.g. you are struggling on assignments, you are worried about your performance on a quiz, etc.) we encourage you to send a private message to course staff on Ed. You are also welcome to email us directly.

Weekly surveys will be released on the course website at the same time we release homework assignments (on Thursdays) and will be due the following week. There are no drops for surveys but we will be lenient with their deadlines.

### Homework Drops and Extra Credit
There will be 5 homework assignments, but we will automatically drop your lowest homework assignment score. This means each homework is worth 10% of your overall grade in the class. If you decide to 'use' a homework drop for a particular assignment, you don't have to submit that homework if you don't want to. But remember that all homeworks cover material that is 'in scope' for the final exam, so we still encourage you to work through all of the homework assignments.

In order to encourage you to start and finish homework assignments early, you can receive 1 extra credit point (homework bonus point) if you submit your homework by **11PM on Wednesday** (24 hours before the regular deadline). We will add this extra credit point to your homework grade.   

### Late Policy and Extensions
Homework assignments are due on Gradescope at 11PM on Thursdays. We will have a small, undisclosed grace period to account for any technical difficulties; if you face any issues while submitting, please post on Ed ASAP (ideally before the deadline).

If you submit your homework late and do not have an extension (see below), we will still accept your submission up to two days late with a 30% late penalty per day. So if you scored 90% on a homework and submitted 12 hours after the deadline, your grade for that homework would be 63%. If you submitted 36 hours after the deadline, your grade for that homework would be 36%. We will not accept homeworks past two days after the submission deadline.

**Extensions**: Things happen, and we don't want to penalize you because of circumstances that are out of your control. To request an extension on a homework, please email **both** James and Will with the reason for your request and the number of days you are requesting an extension for (maximum of 2 days). As long as your request is within reason, there's a good chance of it being granted, in which case we will add the extension to your submission on Gradescope.

If you require assignment extensions as a DSP accommodations, please see the DSP [accommodations](#accommodations-) process below.

### Academic Honesty
This may be the first class you take at UC Berkeley, or the first college class you have ever taken — we know that taking your first class can be stressful. But the main point of this class (and of data science in general) is to try things out and learn from your mistakes, not necessarily to get everything right on the first try. This class is designed to encourage you to learn through exploration, so we hope you focus on learning skills that you might use later, instead of focusing on getting a good grade.

Data science is a collaborative activity. As such, we encourage you to discuss homework and lab assignments at a high level with other students. With that said, you must write all code and solutions individually in your own words. **Rather than copying someone else's work, ask for help.** You are not alone in this course! We're here to help you succeed, and if you invest the time to learn the materal and complete the assignments, you won't need to copy any answers (taken from CS 61A). If you use code you found online, please cite it in a comment and briefly explain what the code does.

### A Note on Letter Grades
*The following is adapted from Data 6 Summer 2021 and from [CSE 160](https://courses.cs.washington.edu/courses/cse160/20au/syllabus/index.html#curve) at the University of Washington.*

**This class is not curved** in the sense that we have set a class average (at, for example, a B+) and require that half of the class receive a grade lower than that. If everyone does well and shows mastery of the material, everyone will receive and A.

We will, however, curve to ensure that demonstrating a sufficient understanding and mastery of key concepts will be enough to receive an A in the class. There is no pre-determined score (e.g. 90% of all possible points) that will earn an A or a B or a C or any other grade. To determine final grades, we will ask questions like "Did this student master the material?" and "Did this student show improvement over the course of the class?".

**In other words, we may curve up, but will never curve down.**

Try your best not to worry about grades, and we'll reciprocate by being fair and lenient. We're in this together, and we want you to focus on learning, not grades.

## Accommodations	&#x1F91D;
Everyone learns differently, and supporting each student individually is part of our job as instructors. We will make every effort to accommodate students to ensure that you can learn safely and comfortably.

If you have a disability, you can email James ([jweichert@berkeley.edu](jweichert@berkeley.edu)) and Will ([willfurtado@berkeley.edu](willfurtado@berkeley.edu)) and we can discuss options for accommodations. You can also communicate with the [Disabled Students Program](https://dsp.berkeley.edu/) (DSP) to have your DSP specialist send us a letter of accommodation letting us know what accommodations we need to provide. **You are *not* required to talk with us directly about your disability if you wish to work through DSP instead.**

If you are a first-time student and anticipating DSP accommodations in furture classes, we recommend starting the DSP onboarding process over the summer when DSP is less busy. In past years, the DSP intake process has taken up to four weeks for some students. Once you register with DSP, the process for requesting accommodations in each of your classes is usually much smoother.

If you have reached out to DSP but have not heard back yet, we will gladly honor your accommodations while DSP processes your intake. Just let us know!

## Campus Resources &#x1F3EB;

Here are some links to campus resources that may also be helpful:
* [University Health Services](https://uhs.berkeley.edu/)
* [UHS Counseling and Psychological Services](https://uhs.berkeley.edu/caps)
* [UC Berkeley Sexual Violence Services](https://svsh.berkeley.edu/)
* [Campus Academic Accommodations Hub](https://evcp.berkeley.edu/programs-resources/academic-accommodations-hub)
* [ASUC Student Advocate's Office](https://advocate.berkeley.edu/)
* [Basic Needs Center](https://basicneeds.berkeley.edu/)
* [Student Learning Center](https://slc.berkeley.edu/)

## Acknowledgements 🙏

The Summer 2022 version of Data 6 is based on [Data 94](http://data94.org/), created and taught by [Suraj Rampure](https://rampure.org/) in Spring 2021 at UC Berkeley, and the Summer 2021 version of [Data 6](http://data6.org/su21/), taught by Ian Castro and Isaac Merritt. Data 6 and Data 94 are loosely based on Data C6, taught by Ian Castro in Summer 2020 at UC Berkeley, which in turn was based on Data 8R, taught by Henry Milner in Summer 2017, also at UC Berkeley. These classes were based on [Data 8](http://data8.org/) at UC Berkeley.

For Summer 2022, Professors [Lisa Yan](https://www2.eecs.berkeley.edu/Faculty/Homepages/yanlisa.html) and [Deborah Nolan](https://statistics.berkeley.edu/people/deborah-nolan) have updated some of the curriculum and assignments in collaboration with faculty at Tuskegee University and with help from Will Furtado, Kevin Miao and James Weichert.

When creating Data 6, we've referred to the materials of several other courses:

- [Data 8](http://data8.org), [CS 10](http://cs10.org), and [CS 61A](http://cs61a.org) at UC Berkeley
- [CS 106A](http://cs106a.stanford.edu) at Stanford
- [CSE 160](https://courses.cs.washington.edu/courses/cse160/) at the University of Washington

---

The website uses [Just the Class](https://kevinl.info/just-the-class/).
