# CS 475/575 - Introduction to Parallel Programming

## Course Description
Theoretical and practical survey of parallel programming, including a discussion of parallel architectures, parallel programming paradigms, and parallel algorithms. Programming one or more parallel computers in a higher-level parallel language.

## Coronavirus Information
Your well-being is our #1 concern! I want all of you to have ready-access to the latest information. Find it here.

**Attention Ecampusers!**

A special welcome to all you Ecampusers! It is good to have a cohort here that comes from all over the world. That makes you very special!

You will experience the same course that the on-campus students experience. Same material, same notes, same projects, same quizzes, same tests, and same online Office Hours. There are recorded videos that go along with the notes (they are called "LV" for "Lecture Videos" and you will see them in the same table that has links to the notes).

Like I do whenever I have Ecampus students, I have setup a time every week to do a Live Lecture so that you can hear a discussion of the topics with the chance to ask live questions. For this course, it will be Wednesdays at 3:00 PDT. They are on Zoom at: https://oregonstate.zoom.us/j/8340727662?pwd=b01tZ0hJUzdHNUtrdTRqSkdwbG4zdz09 During the LL, you can also ask questions in the Zoom Chat, and I will answer them during the LL and in a document that I will post in the same place I post the recorded LL videos. On-campus Parallelers are welcome to come as well.

These Live Lectures will be recorded so that if you miss them, you can catch them later.

Thanks, Ecampusers, for being here!

**Stuff You Should Be Interested In:**

* I have created a short mid-quarter check-in survey. Find it here. It is helpful to me if you would take it. It helps me make the remainder of the class as useful to you as possible. Thanks.
* For you on-campusers -- class on Wednesday, May 3, is cancelled. Instead, I will hold Office Hours in my office (Kelley 2117: 2nd floor, south side). Come by for any reason!
* Graduation! Graduation! Graduation! Save The Date Alerts!
  1. On Friday, June 16 (the Friday of Finals Week), EECS will hold its annual Graduation Celebration. The event runs from 3:00-5:30 at Gill Coliseum and there is a reception afterwards in the plaza just outside. Invite your friends and families to join us to celebrate your extraordinary achievement!   Ecampusers: this includes you too! Go here for more information. This year's keynote speaker will be Sharada Bose (1984, B.S. computer science; 1988, M.S. computer science). She is the recipient of OSU's first Diversity, Equity and Inclusion Alumni Legacy Award in 2020.
  2. The all-university graduation is the next day, Saturday, June 17. Ecampusers: this includes you too! Go here for more information. This year's commencement speaker will be Charity Dean, Ph.D., Class of 2000, CEO of The Public Health Company.
  3. And, as if that isn't enough, Ecampus is holding a special reception for all online graduates, Saturday morning, June 17, 7:30-9:00 AM, leaving you plenty of time to lineup for the all-university graduation. Go here for more information. 
* Here is how to secure-shell your way into the flip servers:
    ssh flip.engr.oregonstate.edu
    Find more information here.
 * So that you can plan for the tests:
  * There will be two tests. Each will be taken on Canvas, will be multiple choice, and will be open-notes (no proctoring -- I'm counting on your honesty). You will have 60 minutes.
  * Test #1 will open in Week #5 on Wednesday, May 3 at 12:01 PM PDT (one minute after noon). It will close on Sunday, May 7, at 11:59 PM PDT (one minute before midnight).
  * Test #2 will open in Finals Week on Wednesday, June 14 at 12:01 PM PDT (one minute after noon). It will close on Sunday, June 18, at 11:59 PM PDT (one minute before midnight). 

## What We Will Be Doing

The goals of this course are to leave you "career-ready" (i.e., both work-ready and research-ready) for tasks that require you to speed the execution of programs using parallelism.

CS 475/575 topics include:
* Moore's Law and Multicore
* Multicore programming using OpenMP
* Speedups and Amdahl's Law
* Hyperthreading
* Caching issues and False Sharing
* Data Decomposition
* Functional Decomposition
* Single Instruction Multiple Data (SIMD)
* GPU Computing, including CUDA and OpenCL
* OpenCL / OpenGL Interoperability
* Message Passing Interface (MPI) 

## Prerequisites and Course Incoming Expectations

This course will use C/C++ for most of its programming. You should be comfortable with the concepts of function calls, arrays, for-loops, structures, arrays of structures, structures of arrays, pointers, stacks, queues, trees, and linked lists. It is strongly suggested that you not use CS 475/575 as an opportunity to learn programming for the first time.

Many of the assignments can be done on the OSU Linux systems, which you will have ready-access to.

It would be good if you already know how to use the Linux command line and tools such as: ls, mv, cp, mkdir, cd, pwd, rm, echo, gcc/g++, and diversion to a file. It will also help if you know at least one Linux-based editor (vim is good).

This class does a lot of graphing performance data. You will need access to a program that will let you enter data into a 2D table and graph it. E(xcel is good, but there are others). You will need to be able to copy-and-paste those tables and graphs into a word processing document, add your own text around them, and then produce a PDF file from it.

## Professor
The class is being taught by Professor Mike Bailey.

Office: 	Kelley 2117 (2nd floor, south side)
Email: 	mjb@cs.oregonstate.edu
Phone: 	541-737-2542

**Notes in place of a textbook**
Course material will consist of my notes and web pages.
All required course materials for this class will cost you $0.00 (i.e., free).
On-campus Section of the Class

Our on-campus class time is: Monday and Wednesday, 12:00 - 1:50. All of our classes will be in the Learning Innovation Center (LiNC), room 128.

Online Section of the Class

The lectures for the Ecampus version of the class will be asynchronous, that is, you are free to review the notes and watch the videos whenever it suits you. But, be careful not to fall behind! The programming projects, and their due dates, will assume that you have been keeping up with the material.

I will also be conducting Live Lectures every Wednesday at 3:00 Pacific Time so that you have a chance to ask questions during the presentation of the material.

lect the Best (imho...) OpenCL Platform/Device 	selectopencldevice.cpp

## Projects

Project 6 is Not Yet Finalized!

Note: The flip machines do not have GPU cards in them, so CUDA and OpenCL will not run there. (You can compile there, you just can't run.) If your own system has a GPU, you can try using that. You can also use rabbit or the DGX machine, but please be good about sharing them.

Project # 	Points 	Title 	Due Date 	Lecture Video
0 	30 	Simple OpenMP Experiment 	April 10 	LV
1 	100 	OpenMP: Monte Carlo Simulation 	April 18 	LV
2 	100 	Functional Decomposition 	April 30 	LV
3 	100 	Mutex Stack Challenge 	May 10 	LV
4 	60 	Vectorized Array Multiplication and Reduction using SSE 	May 17 	LV
5 	100 	CUDA: Monte Carlo Simulation 	May 25 	LV
6 	100 	OpenCL 	June 4 	LV
7 	120 	MPI 	June 13 -- No BDs 	LV
575-only paper 	100 	Paper Analysis Project 	June 13 -- No BDs 	LV

**Note:** The flip machines do not have GPU cards in them, so CUDA and OpenCL will not run there. (You can compile there, you just can't run.) If your own system has a GPU, you can try using that. You can also use rabbit or the DGX machine, but please be good about sharing them.

## Project Turn-In Procedures

    Your project turnins will be electronic.

    Your electronic turnin will be done at http://teach.engr.oregonstate.edu and will consist of:
        A PDF report. The PDF file should include:
            A cover page (name, email address, project name)
            Key snippets of code, if applicable
            Tables of data
            Graphs of data
            Your conclusions: how did things turn out? Why? 
        Source files of everything (.cpp, .cu, .cl). 

    You can zip up all the source files you are turning in if you want. But, do not put the PDF file in a .zip. Please turn it in separately so I can run my gather-up-all-the-PDFs script.

    Submissions are due at 23:59:59 on the listed due date.

    Your project will be graded and the score posted to your Canvas Grades. If you lost any points, there will be a Canvas comment about it. If you want to reply to the comment, please do it via email, not the Canvas Comments -- I am much more reachable on email. 

Bonus Days and Late Assignments

Projects are due at 23:59:59 on the listed due date, with the following exception:

Each of you has been granted 5 Bonus Days, which are no-questions-asked one-day extensions which may be applied to any project, subject to the following rules:

    No more than 2 Bonus Days may be applied to any one project
    Bonus Days cannot be applied to quizzes
    Bonus Days cannot be applied to tests
    Bonus Days cannot be applied to Project #7 or the 575 Paper Project 

If you turn in a project three or more days late, the score is a zero.

If you turn in a project late and don't have enough Bonus Days left to spend on it, the score is a zero.

You don't need to ask me, or even tell me. that you are using Bonus Days. Just turn your project in late. I have a script that will check your turn-in date and deduct the proper number of Bonus Days.

It is your job to track your Bonus Day usage. But, if you lose track, feel free to email me and ask me to look it up.

## Grading

Your scores will be posted on Canvas

CS 475/575 will be graded on a fill-the-bucket basis. There will be 8 programming projects, 10 quizzes, and two tests. You get to keep all the points you earn.

Those taking the class as CS 575 will also do a 100-point essay summarizing a research paper. (Those taking the class as CS 475 will get a free 100 points for this assignment.)

All programming projects will be turned in on Teach, http://teach.engr.oregonstate.edu .

The quizzes will be done on Canvas. They will open each Friday at 12:01 PM and will close Sunday night at 23:59 (=11:59 PM). Canvas is very unforgiving about due times -- don't push it.

Your final grade will be based on your overall class point total. Based on an available point total of 1110, grade cutoffs will be no higher than:

Points 	Grade
1060 	A 
1040 	A- 
1020 	B+
1000 	B 
980 	B- 
960 	C+
940 	C 
920 	C- 
900 	D+
880 	D 
860 	D- 

Notice that this grade scale is not 90%-80%-70%-60%. That is because I do such a soft grade on the projects.

## Class Rules
* Computer Security: We take computer security very seriously. Please use intelligently-chosen passwords and protect them. Anyone caught abusing the system or causing deliberate damage will be asked to drop the class and the matter will be turned over to the Dean's Office.
* Working Together: It is OK to work together by sharing information and teaching each other, but each person's projects must be original work with no sharing of code.
* Cheating: You are expected to do your own work. Sharing code is considered cheating. Anyone caught cheating will fail this class, and the matter will be turned over to the Dean's Office. 
