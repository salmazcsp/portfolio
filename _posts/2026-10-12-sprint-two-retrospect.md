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

# Practice Multiple Choice Quiz — Retrospective Review

I scored **57/66** on the practice multiple-choice quiz, meaning I got **9 questions wrong** overall. I am proud of this score because I completed the quiz without using AI and without rushing through the questions. However, reviewing the results shows that there are several areas I need to improve.

My biggest weakness was **Skill 1.D: Design and evaluate computational solutions for a purpose**, where I missed **4 questions**. The other missed questions were spread across Skills 5.A, 2.B, 4.B, and 3.C.

## Skill 1.D — Design and Evaluate Computational Solutions for a Purpose
**Questions missed: 4**

This was my weakest skill on the quiz. Missing 4 questions in the same skill suggests that I need to work on more than just one specific concept. I may understand individual programming concepts but struggle when I have to decide whether a computational solution is the **best or most appropriate solution for a particular purpose**.

Questions involving this skill can require me to evaluate things such as efficiency, functionality, usability, limitations, and whether a solution actually meets the requirements of a problem. I may have focused too much on whether an answer *could* work rather than whether it was the **best solution for the stated purpose**.

### What I need to improve
I should pay closer attention to the exact requirements of a problem before choosing an answer. Instead of immediately looking for an answer that seems technically correct, I should ask:

- What is the purpose of the program or solution?
- What requirements does it need to satisfy?
- Which solution is the most efficient or appropriate?
- Are there limitations or trade-offs?
- Does the solution actually solve the problem described?

### Retrospective
The main lesson from these mistakes is that I need to think more about the **design and evaluation of a solution**, rather than just whether I understand the code. I should practice comparing multiple possible solutions and explaining why one is better than another.

**Action plan:** I will practice questions where I have to evaluate algorithms, programs, or computational solutions based on their purpose and requirements. I will also make sure to justify *why* an answer is the best solution rather than simply identifying an answer that works.

---

## Skill 5.A — Explain How Computing Systems Work
**Questions missed: 2**

I missed 2 questions involving how computing systems work. This suggests that I may need to strengthen my understanding of what happens inside a computing system and how its different components interact.

These questions can involve concepts such as hardware, software, memory, storage, processing, networks, and how information moves through a computer system.

### What I need to improve
I should make sure I understand the **relationships between components**, rather than memorizing definitions individually. For example, I should be able to explain what happens when a program is executed and how the processor, memory, storage, and other components contribute.

### Retrospective
I may have recognized some of the terminology but not fully understood how the pieces work together. If a question changes the scenario, simply memorizing a definition may not be enough.

**Action plan:** I will review the major components of computing systems and practice explaining what each component does and how they interact during different tasks.

---

## Skill 2.B — Implement and Apply an Algorithm
**Questions missed: 1**

I missed 1 question involving implementing or applying an algorithm. This is a relatively small weakness compared with Skill 1.D, but it still shows that I should be more careful when following algorithmic steps.

Questions in this area require me to understand how an algorithm works and correctly apply it to a problem or piece of code.

### What I need to improve
I should slow down when tracing an algorithm and make sure I follow **every step in the correct order**. If variables change throughout an algorithm, I should keep track of their values rather than trying to mentally skip steps.

### Retrospective
This mistake may have been caused by overlooking a step or assuming what the algorithm would do instead of actually tracing it.

**Action plan:** I will practice tracing algorithms manually using a table or written steps. For more complicated algorithms, I will record the value of important variables after each step.

---

## Skill 4.B — Determine the Result of Code Segments
**Questions missed: 1**

I missed 1 question involving determining the result of a code segment. This means I generally understand how code works, but I may have made an error when tracing a specific piece of code.

These questions require careful attention to things like conditionals, loops, variable changes, operators, and the order in which statements execute.

### What I need to improve
I should avoid assuming what the code will do based on its overall appearance. Instead, I should trace the code line by line.

For example, I should keep track of:

1. The initial values of variables.
2. Which condition is being evaluated.
3. Which branch of a conditional executes.
4. How loops change variables.
5. What the final output will be.

### Retrospective
Because I only missed one question in this skill, I don't think this is a major weakness. However, it shows that I should be more precise when tracing code rather than relying on intuition.

**Action plan:** I will practice short code-tracing problems and write down variable values as they change.

---

## Skill 3.C — Explain How Abstraction Manages Complexity
**Questions missed: 1**

I missed 1 question involving abstraction. This suggests that I may understand the general idea of abstraction but need to be more precise about **why abstraction is useful**.

Abstraction allows programmers to hide unnecessary implementation details and focus on the important features of a system. This helps manage complexity because programmers can use a function, procedure, library, or other abstraction without needing to understand every detail of how it works internally.

### What I need to improve
I should remember that abstraction is not simply about "hiding code." Its purpose is to allow a programmer to work with a system at a higher level without needing to deal with every underlying detail.

### Retrospective
I may have confused abstraction with another programming concept or selected an answer that described what abstraction does without explaining **how it reduces complexity**.

**Action plan:** I will practice identifying examples of abstraction and explaining exactly what details are being hidden and how that makes a program easier to develop or understand.

---

# Overall Reflection

My score of **57/66 (about 86%)** shows that I have a solid understanding of the material overall. I did not struggle equally with every skill. Instead, my mistakes were concentrated in a few areas.

| Skill | Questions Missed | Priority |
|---|---:|---|
| **1.D — Design and evaluate computational solutions** | **4** |  Highest |
| **5.A — Explain how computing systems work** | **2** |  High |
| **2.B — Implement and apply an algorithm** | **1** |  Moderate |
| **4.B — Determine the result of code segments** | **1** |  Moderate |
| **3.C — Explain how abstraction manages complexity** | **1** |  Moderate |
| **Total** | **9** | |

The biggest takeaway from this quiz is that **Skill 1.D should be my main focus**. I missed almost half of all my incorrect questions in that one skill. Rather than simply doing more questions randomly, I should specifically practice evaluating computational solutions and thinking about whether a solution meets a particular purpose, requirement, or constraint.

My next priority should be **Skill 5.A**, followed by reviewing the three skills where I only missed one question each.

Overall, I am happy with my performance. The **57/66** score shows that I already have a strong foundation, and the mistakes give me a clear idea of what to focus on before the next assessment.