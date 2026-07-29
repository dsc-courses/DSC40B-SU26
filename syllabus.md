---
layout: default
title: 📖 Syllabus
nav_order: 2
description: Course structure and policies.
---

# 📖 Syllabus
{:.no_toc}


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{: .warning }
> **Disclaimer:** The purpose of this syllabus is to give students guidance on what may be covered during the semester. I intend to follow the syllabus as closely as possible; however, I also reserve the right to modify, supplement, and/or make changes to the course as needs arise. All such changes will be communicated in advance through in-class announcements and in writing via this website and email.

## About 

A computer does not rise to the level of its hardware. It falls to the level of its algorithms.
 
You can double your RAM, upgrade your GPU, and spin up a hundred machines in the cloud, but if the algorithm underneath is doing redundant work, none of that matters. A well-chosen algorithm on a modest laptop will outperform a brute-force approach on a supercomputer. This is not a theoretical claim. It is an everyday reality.
 
The world already knows this. The route that gets a package from a warehouse to your door same-day is not the obvious one. That was from an algorithm that weighs distance, truck capacity, traffic patterns, and thousands of other vectors.  The internet itself runs on graph algorithms designed decades ago (and one in particular stood the test of time for 70 years until it was broken just last year-- more on that later). Simply put, when algorithms work, they are invisible to most of the world. When they don't, there are consequences (see: [Knight Capital](https://www.henricodolfing.ch/en/case-study-4-the-440-million-software-error-at-knight-capital/) and [Ofqual](https://www.bristol.ac.uk/cmm/research/grade/)).
 
DSC 40B is about the building blocks: how to analyze whether an algorithm is fast or slow, how to choose the right data structure for the job, and how to reason about tradeoffs like simplicity versus performance and/or exact answers versus good-enough approximations. These are not just computer science questions. They are design decisions that shape what is computationally possible.
 
Your job as a data scientist is different from that of a software engineer. A software engineer might implement a hash table; you need to know *when* a hash table is the right choice and what breaks when it isn't. A software engineer might optimize a sorting routine; you need to know *why* the problem requires sorting in the first place, and whether a different formulation avoids it entirely. This course moves between both perspectives because in practice, you will need to do both.

---

## Communication 

This quarter, we'll be using [Piazza]() as our course message board. You should be added to Piazza automatically; if not, join using this link. Please join right away as we'll be making all course announcements through Piazza.

If you have a question about anything to do with the course (you're stuck on a problem, didn't understand something from lecture, want clarification on course logistics), you can make a post on Piazza. We only ask that if your question includes some or all of an answer (even if you're not sure it's right), please make your post private so that others cannot see it. You can also post anonymously if you would prefer.

Course staff will regularly check Piazza and try to answer any questions that you have. You're also encouraged to answer questions asked by other students. Fun fact: this was what I started out doing as I made my way from student -> TA -> head TA -> instructor!

Please don't email staff members (and don't message them on social media), just make a private or public Piazza post instead!

---

## Technology 

We will be using several websites this quarter. Here's what they're all used for:

- [Course Website](https://dsc40br.com): The single source of truth for all course content. This includes lecture recordings, assignment specs, deadlines, schedule, practice problems, and past exams (even though these will be limited in assistance).
- [Course Notes](https://dsc40br.com/materials/default/notes/book.pdf): The official course notes, written by Justin Eldridge. You should refer to these throughout the quarter, as the content reflects what is covered here.
- [Piazza](): Discussion forum for announcements and communication.
- [Gradescope](https://www.gradescope.com): Platform for submitting assignments and viewing grades. You should be automatically added to Gradescope within 24 hours of enrolling.

**Canvas is used solely as the gradebook. All course content, deadlines, and announcements live on [dsc40br.com](https://dsc40br.com) and Piazza.**

---

## Course Structure 

This course is **fully asynchronous and remote**. There are no synchronous lecture sessions, discussion sections, or required real-time meetings. All content is delivered through pre-recorded lecture modules posted on the course website.

### Lectures

Lectures are pre-recorded and posted on [dsc40br.com](https://dsc40br.com). Each lecture is split into **2–3 short modules** designed for focused viewing and easy re-watching. A typical lecture consists of:

- **Module A (15–20 min):** Motivation, definitions, and the core idea.
- **Module B (20–25 min):** Algorithm/proof mechanics: pseudocode, correctness arguments, complexity derivation.
- **Module C (10–15 min, when applicable):** Worked examples, edge cases, and exam-style problems.

There are **17 lectures** spread across 5 weeks. The schedule and all recordings are available on the [course homepage](https://dsc40br.com).

You are expected to watch all lecture modules and complete the associated readings from the [course notes](https://dsc40br.com/materials/default/notes/book.pdf) before attempting that week's homework.

### Homeworks

There are **5 homework assignments** this quarter, one per week. Homeworks are the primary way you will engage with and demonstrate mastery of the material.

- **Released:** Tuesdays at 9:00 AM PT
- **Due:** Fridays at 11:59 PM PT
- **Submission:** Gradescope

**Homeworks must be typed.** You may use whatever typesetting system you prefer, whether that is Google Docs, Microsoft Word, LaTeX, etc. Since much of your academic journey will involve writing papers and using LaTeX, you are encouraged to take this quarter as an opportunity to learn the basics. Before Homework 1 is released, I will provide a LaTeX template applicable to all homeworks, along with instructions for how to use and deploy it.

**If you submit a handwritten homework, you will receive one warning. Any subsequent handwritten submission will incur a 25% penalty.**

Homework grading will involve Gradescope autograding (details TBD).

You may talk to other students in the class about the problems and discuss solution strategies, but you should not share any written communication. You can tell someone how to do a homework problem, but you cannot show them how to do it. The content of your collaboration should involve problem-solving strategy and approach, and you should not directly compare answers with classmates.

For each problem you submit, you should cite your sources by including a list of names of other students with whom you discussed the problem. Course staff does not need to be cited.

### Office Hours

To get help on assignments and concepts, course staff will be hosting office hours via **Calendly appointments**. These are 1:1 (or small group) meetings that you can book at your convenience.

- **Instructor:** [TODO]
- **Tutors:** [TODO]

Tutors will also actively monitor Piazza throughout the week.

The homework assignments for this class are challenging and most students are not able to successfully complete them from watching lectures alone. Make sure to use the [course notes](https://dsc40br.com/materials/default/notes/book.pdf), the [practice problems](https://dsc40br.com/practice/index.html), and book office hours if you need them! We are here to help you.

### Weekly Schedule

| Sunday | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday |
| -- | -- | -- | -- | -- | -- | -- |
| | | **HW released 9:00 AM** | | | **HW due 11:59 PM** | |

All deadlines are in **Pacific Time (PT)**. The most up-to-date schedule is always on the [course homepage](https://dsc40br.com).

---

## Exam 

There is **one exam** in this course: the **Final Exam**, worth **35%** of your overall grade. There is no midterm.

### Format

The Final Exam is designed to operate like a **technical interview**. Here is how it works:

1. **Book a 1-hour slot** on Calendly (TODO). The exam window and available slots will be announced in advance.
2. **At the start of your slot**, begin a Zoom recording with your camera on and screen shared (one monitor only). Only you should be in the Zoom meeting room, and your area should be free of distractions.
3. **At :05 past the hour**, an email will be automatically sent to your @ucsd.edu address containing a PDF with **3 exam questions**. Each student receives a **different subset** of questions.
4. **Answer only 1** of the 3 questions. The three questions cover different parts of the course, so you can choose the topic you are most comfortable with.
5. You have the remainder of your hour (approximately 55 minutes) to work through the question. 
6. Submit your Zoom recording link and any supporting work to Gradescope.

### What we are looking for

This is not a syntax test. We are evaluating your ability to:

- **Read and interpret** the problem correctly.
- **State assumptions and identify tradeoffs** before diving in.
- **Demonstrate intuition**: whether on a code editor, paper, or whiteboard.
- **Justify your approach**: explain *why*, not just *what*.

Each question has its own rubric calibrated to its difficulty. The full rubric will be provided before the exam (details TBD).

### Preparation

Before the official exam, we will:

- **Release a demo** showing exactly how the exam experience will look.
- **Provide a test-run opportunity** so you can verify your setup (Zoom recording, screen share, email delivery).

You may assume no two students will receive the same exam, and each exam is individually generated. Asking others in the course for what the exam will look like is going to be futile. Any details they can give you will have already been given.

**The exam date is TBD.**

---

## Policies 

### Grading

Here's how we will compute your grade.

| Component | Weight | Notes |
| --- | --- | --- |
| Homework | 65% | 5 assignments, drop lowest |
| Final Exam | 35% | |

### Late Policy, Extension Policy, and Drops

<span style="color:red">No late work will be accepted on any assignments.</span>

#### Homeworks

Instead, if you need extra time on an assignment, you can request an extension [here](). All students will receive a singular one time one day extension with no questions asked that can apply only to homeworks. After that one day extension is used, staff reserves the right to review the reason for your request to either accept or decline it. All extensions will be granted on the order of days, not hours, so the shortest extension any student will be granted is 24 hours or one day; this means all deadlines will remain at 11:59PM unless otherwise stated.

**NOTE** We will try to respond to extension requests as quickly as possible, however, we are human (and in different time zones), so if you request an extension outside of business hours, please don't expect a response until the next business day. This means, if you think you will need more time on an assignment it is better to request an extension earlier rather than later.

**NOTE** No extension requests after the 11:59pm deadline of the respective assignment will be accepted other than in extreme circumstances at the discretion of the instructor. So again, please request extensions sooner rather than later so you don't miss this deadline.

**NOTE** The last deadline by which we will accept any work from this semester is TBD (the day of the final exam). After this deadline no work will be accepted because we need to submit final grades.

**If you have something going on in your life that is impeding your ability to do your classwork on time, please reach out to us as soon as possible so we can work something out.**

#### Drops

We will drop your lowest homework. This gives you some additional flexibility for unforeseen circumstances.

#### Late adds

Students on the waitlist or who join the class late are expected to keep up with the work and submit assignments by the deadlines. We will not be lenient on deadlines for students who join the class late.

The stated policies will be strictly enforced out of fairness for all students.

### Regrade Requests

You can ask for a regrade on any assignment if you believe that we made a mistake. Remember that clarity is a part of your score: if you had the right idea but were unable to clearly communicate it, you may still not deserve full credit. We ask that you submit your regrade requests within three days of the assignment grade being released; you can submit regrade requests directly on Gradescope. Please be mindful that staff regrades the assignment, and if we missed something else, we may lower your grade further. By submitting a regrade request, you are accepting that fact. Additionally, repeated or redundant regrade requests may result in staff stopping consideration of future requests from you.

### Incomplete Grades

In the unfortunate circumstance that you become sick, suffer a loss, or otherwise experience a significant setback that is outside of your control, you may be eligible for an Incomplete grade, which allows you to complete the rest of the work at a later time. If you are experiencing challenges due to circumstances outside your control, please contact me ASAP and we can discuss the best course of action. Note that an Incomplete does not allow you to re-do work that has already been completed, only to do work that hasn't been completed, so it's best to reach out right away. Please keep in mind that you need to have at least completed the majority of the course to qualify for an incomplete.

### Academic Integrity

In this class, we expect that you will work hard, utilize allowed resources to master the course material, and act with integrity. Learning remotely presents new challenges for academic integrity, making it more important than ever to act honorably and make sure that the work you are submitting is reflective of your knowledge and abilities.

The [UCSD Policy on Integrity of Scholarship](https://academicintegrity.ucsd.edu/process/policy.html) and this syllabus list some of the standards by which you are expected to complete your academic work, but your good ethical judgment is also expected. Ignorance of the rules will not excuse you from any violations.

For this class, the following activities, among others, are considered cheating and are not allowed:
- Sharing written homework solutions with other students, or viewing written homework solutions from another student.
- Looking or asking for answers to homework problems in other texts or sources, including the internet and Generative AI tools such as ChatGPT and GitHub Copilot.
- Collaborating on exams, checking answers on exams, or communicating with any other person while taking an exam.
- Using unauthorized resources on homeworks or exams, including solutions from past iterations of this course, and AI tools such as ChatGPT and GitHub Copilot.

The following activities are examples of things that are allowed in this class:
- Discussing homework problems with classmates and the course staff.
- Reading about concepts from lecture in outside texts, including the internet, without looking for answers to specific homework questions. If you accidentally find related material in another source, you must cite the source on your homework and write up your answer without consulting the source. To do otherwise is plagiarism.
    - Note that you _can_ ask Generative AI tools, like ChatGPT, to explain ideas from class, but beware, they aren't always correct!

Remember, Academic Integrity is about doing your part to act with honesty, trust, fairness, respect, responsibility and courage. If you are suspected of dishonest conduct, you will be reported to the Academic Integrity Office. Violations of the academic integrity policy will result in failing the course, and the Dean of your college may place you on academic probation or suspend or dismiss you from UCSD. Academic integrity violations are serious and the risk is not worth it!

### A note on letter grades

_The following is adapted from [CSE 160](https://courses.cs.washington.edu/courses/cse160/20au/syllabus/index.html#curve) at the University of Washington._

My goal is to ensure that the assessment of your learning in this course is comprehensive, impartial, and equitable. Your grade in the class will be based on the number of points you earn out of the total number of points possible, and is not based on your rank relative to other students. There are no set limits to the number of grades given (e.g., everyone can get an A if everyone does well).

Under no circumstances will grades be adjusted down (except in cases of course policy violation). You can use this straight grading scale as an indicator of your minimum grade in the course at any time during the course. You should keep track of your own points so that at any time during the semester you may calculate your minimum grade based on the total number of points possible at that particular time. If and when, for any reason, you have concerns about your grade in the course, please email me to schedule a time for you to speak with me so that we can discuss study techniques or alternative strategies to help you.

---

## Support 

### Accommodations

From the [Office for Students with Disabilities (OSD)](https://osd.ucsd.edu/):

>_OSD works with students with documented disabilities to review documentation and determine reasonable accommodations. Disabilities can occur in these areas: psychological, psychiatric, learning, attention, chronic health, physical, vision, hearing, and acquired brain injuries, and may occur at any time during a student's college career. We encourage you to contact the OSD as soon as you become aware of a condition that is disabling so that we can work with you._

If you already have accommodations via OSD, please make sure that we receive your Authorization for Accommodation (AFA) letter by the end of Week 2 so that we can make arrangements for accommodations. Share your AFA letter with the instructor and the Data Science OSD Liaison, who can be reached at [dscstudent@ucsd.edu](mailto:dscstudent@ucsd.edu).

### Diversity and Inclusion

We are committed to creating an inclusive learning environment in which individual differences are respected and all students feel comfortable. If you have any suggestions as to how we could create a more inclusive setting, please let us know.
We also expect that you, as a student in this course, will honor and respect your classmates, abiding by the [UCSD Principles of Community](https://ucsd.edu/about/principles.html). Please understand that others' backgrounds, perspectives and experiences may be different than your own, and help us to build an environment where everyone is respected and able to thrive.

---

## Acknowledgements 

Thanks to other instructors of this course who have made various contributions, including but not limited to Nishant Kheterpal, Suraj Rampure, Janine Tiefenbruck, Aobo Li, Yian Ma, Gal Mishne, and Justin Eldridge. Thanks also to the many tutors and TAs who have supported this course since its inception!