---
layout: post
courses: { csse: {week: 4}, csp: {week: 9} }
codemirror: true
title: Sprint 2 Retrospective Review
description: Review of MCQ practive and past 8 weeks
permalink: /stwo_retro
---

# Sprint 2 Retrospective Review

## Past 8 Weeks

The past eight weeks have been very productive and fruitful as they were the first eight weeks of the year altogether. Here are the things we have done and finished throughout the past eight weeks!

---

### Sprint 1: Setting Up Tools & Work Habits: Weeks 0-4

During the fist four weeks of school, we focused on getting initialized and setting up tools like VSCode and GitHub. 

#### Initial Capstone Ideation

Our group decided to inherit the ACS capstone project.

**Target Audience**
Cancer patients in need of a safe space and those involved with cancer patients and would like to learn more.

**Objective**
Users need a safe space where people understand what they are going through, and can learn more about it because younger generations usually aren't aware of how cancer works at a biological level, leading to a lack of understanding of what cancer patients go through.

**Success Statement**
We know this works when we have a website where people can not only learn about what cancer is, but where people can connect and ask questions.

**Scope**
This project will not include excessive educational content.

---

### Sprint 2: Full Stack Foundations: Weeks 5-8

Sprint 2 had more of a workload. More projects, more coding.

#### Toggles Lesson

View our lesson here:
https://pages.opencodingsociety.com/sass/toggles

I enjoyed the toggles lesson, as it taught be a lot more about SASS and what is does, but it also taught me about something fun and unique. I really enjoyed learning about them.

Here is our planning issue:
https://github.com/undergroundrapclub/pages/issues/7

Gist: By the end of the lesson, students should understand what toggles are and when they should be used. They should also be able to create a basic toggle, add a label, change its starting state, and use the OCS Sass system to style it. We even made a lesson skeleton-- Here are my thoughts on it.

**1. Introduction**

We will start by explaining what a toggle is and where someone might use one, such as notifications, settings, or turning a feature on and off. Giving exmaples of how they are used in daily life such as apps or websites you would use regularly.

**2. OCS Sass Version**

We will explain that the original lesson used Aesthetihawk, but the new version will use the OCS Sass system. This section will introduce the reusable OCS classes and explain why we should use them instead of making custom CSS every time.

**3. Creating a Toggle**

We will show the basic structure of a toggle and explain what each part does. We will start with a very simple toggle before moving into things like labels and checked states so the lesson does not become too difficult too quickly.

**4. Code Runners**

We will add simple code runners throughout the lesson so students can edit the examples and test their code. The examples will start with a basic toggle and slowly add things like a label or a checked state.

The code runners will include starter code so students don't have to write everything from scratch. This will let them focus on understanding what each part of the code does.

**5. UI Runners**

We will also add UI runners that let students **see the toggle they created** while they are learning. Instead of only looking at the code, students will be able to see the actual toggle and interact with it.

For example, after changing the code to add a label or make the toggle checked, the UI runner can show the updated toggle. This makes it easier for students to understand how a change in the code affects what they see on the page.

The UI runners will stay simple and only show the parts that students are currently learning. This way, students can see their progress without having to understand a complicated interface.

**6. Accessibility**

We will explain how to make the toggle easier for everyone to use. This will include using `<label>`, making sure the toggle can be used with a keyboard, keeping focus visible, and giving the toggle an accessible name when it does not have a visible label.

A UI runner can also be used here so students can test the toggle themselves and see how it responds when they interact with it.

***7. Using OCS Sass***

We will explain how the toggle should use OCS preference variables like `--pref-text-color`, `--pref-accent-color`, `--ui-bg`, and `--ui-border`. We will keep this section simple and explain what each variable does instead of expecting students to already know Sass.

A code runner and UI runner can be used together here so students can change a Sass variable and see how it affects the toggle.

**8. Practice**

We will have students make a small settings section with two or three toggles. They will use OCS Sass classes, add labels, make one toggle checked by default, and put the toggles inside an OCS card.

Students will be able to use the UI runner to see what their finished settings section looks like and make changes if something does not look or work correctly.

**Keeping the Lesson Easy to Follow**

We will make sure the lesson does not introduce too many new concepts at once and all the students are on the same pages during interactive activites. Each section will build on the previous one, and the code and UI runners will give students a way to experiment with the code and immediately see what their changes do.

We will also keep the examples short and explain new classes or Sass variables before using them in a code example.

**What Makes This Better**

The original lesson mostly shows the different toggle options without going very far into how they fit into the rest of the site. Our new lesson will explain the purpose of each part, use the OCS Sass system, add interactive code and UI runners, and give students a chance to see and practice what they are creating.

**Expected Result**

By the end, students should be able to make a simple and reusable toggle using OCS Sass. They should also understand how to keep it accessible, test their code, and use the UI runner to see how their toggle looks and works before moving on.

#### Frontend and Backend

We learned a little about managing the front and backends of our capstone projects. They are interesting because they rely on ports and can connect to one another without a manual trigger each time.

#### APIs

We briefly touched on APIs in class and how they work in the backend. My understanding of them is rough, as it is my first time hearing about and working with them.

**What we plan to do with them**
- Have them store usernames and passwords
- Cancer risk assessment
- Further ideation TBT

---

### Practice Multiple Choice Quiz

Overall, I think the MCQ went quite well for me not using AI or rushing through any questions. I'm proud of my score; a 57/66. That's not bad. But what topics did I mess up on? Get wrong?

Which of the following best describes the role of the Internet Engineering Task Force (IETF) ?
A
Developing standards and protocols for Internet communication
B
Preventing copyrighted materials from being illegally distributed online
C
Preventing malicious software from being distributed online
D
Verifying the ownership of encrypted keys used in secured messages

Skill 5.A: Explain how computing systems work.

-

The figures represent different ways of configuring a network of physically linked computers labeled P, Q, R, and S. A line between two computers indicates that the computers can communicate directly with each other.
In which configuration is it NOT possible to have redundant routing between computers P and S?

Skill 1.D: Design and evaluate computational solutions for a purpose

-

The question below uses a robot in a grid of squares. The robot is represented as a triangle, which is initially in the bottom right square of the grid and facing toward the top of the grid.

The figure shows a grid of squares with 5 columns and 5 rows. The bottom right square of the grid contains an upward-facing triangle, representing a robot. The top left square of the grid is shaded gray. All other squares are white.

The following programs are each intended to move the robot to the gray square. Program II uses the procedure One word, Goal Reached, which returns true if the robot is in the gray square and returns 

false otherwise.
Program I: The block code consists of 5 lines. Begin block Line 1: REPEAT 4 TIMES Begin block Line 2, indented 1 tab: MOVE underscore FORWARD Line 3, indented 1 tab: ROTATE underscore LEFT Line 4, indented 1 tab: MOVE underscore FORWARD Line 5, indented 1 tab: ROTATE underscore RIGHT End block End blockProgram II: The block code consists of 5 lines. Begin block Line 1: REPEAT UNTIL, begin block, Goal Reached, 1 word with capital G and R, end block Begin block Line 2, indented 1 tab: IF, begin block, CAN underscore MOVE, begin block, forward, end block, end block Begin block Line 3, indented 2 tabs: MOVE underscore FORWARD End block Line 4, indented 1 tab: ELSE Begin block Line 5, indented 2 tabs: ROTATE underscore LEFT End block End block End block

Which of the following statements is true?
A
Program I correctly moves the robot to the gray square, but program II does not.
B
Program II correctly moves the robot to the gray square, but program I does not.
C
Both program I and program II correctly move the robot to the gray square.
D
Neither program I nor program II correctly moves the robot to the gray square.

Skill 1.D: Design and evaluate computational solutions for a purpose

-

The two code segments below are each intended to display the average of the numbers in the list One word, num List. Assume that One word, num List contains more than one value.

Program I: The block code consists of 5 lines. Line 1: sum, left arrow, zero Begin block Line 2: FOR EACH num IN num List, 1 word with capital L Begin block Line 3, indented 1 tab: sum, left arrow, sum plus num Line 4, indented 1 tab: a v g, 1 word, left arrow, sum divided by LENGTH, begin block, num List, end block End block End block Line 5: DISPLAY, begin block, a v g, end blockProgram II: The block code consists of 5 lines. Line 1: sum, left arrow, zero Begin block Line 2: FOR EACH num IN num List, 1 word with capital L Begin block Line 3, indented 1 tab: sum, left arrow, sum plus num End block End block Line 4: a v g, 1 word, left arrow, sum divided by LENGTH, begin block, num List, end block Line 5: DISPLAY, begin block, a v g, end block

Which of the following best describes the two code segments?
A
Code segment I displays the correct average, but code segment II does not.
B
Code segment II displays the correct average, but code segment I does not.
C
Both code segments display the correct average, but code segment I requires more arithmetic operations than code segment II.
D
Both code segments display the correct average, but code segment II requires more arithmetic operations than code segment I.

Skill 1.D: Design and evaluate computational solutions for a purpose

-

