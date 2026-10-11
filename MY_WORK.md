# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [renad gareb alajmi] |
| **Student ID** | [445052072] |
| **University Email** | [445052072]@std.psau.edu.sa |
| **GitHub Username** | [yrenad108] |
| **Repository Link** | [https://github.com/renad108/OS-Assignment1-renad-alajmi]|
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 8 — 5pm:]
**What I did**: Updated the student ID in SchedulerSimulation.java

**Details**:
- Opened SchedulerSimulation.java and located the studentID variable.
- Replaced the default student ID with my own ID: 445052072.
**Challenges**: did not face any problems 
**Solution**: no Solution was needed
**Time spent**: 30 min
---

### Entry 2 - [10 oct - 2pm]


**What I did**:
Implemented Feature 1
**Details**:
- Added a priority variable to the Process class.
- Updated the constructor to accept a priority value.
- Used random.nextInt(10) + 1 to generate a random priority between 1 and 10.
- Modified the ready queue message to display each process's priority.
**Challenges**: getting the random priority values to appear correctly
**Solution**:
I checked how priorities were generated and passed to the Process constructor, then updated the code and tested the outpu
**Time spent**:
50 min
---

### Entry 3 - [10 oct  - 3 pm ]
**What I did**:Implemented Feature 2: Context Switch Counter

**Details**:
- Added a static variable named contextSwitchCount to the SchedulerSimulation class.
- Incremented the counter before calling currentThread.start().
- Added a statement to display the total number of context switches at the end of the simulation.
- Kept the original Round-Robin scheduling behavior unchanged.
**Challenges**:
I needed to identify the correct location in the scheduler loop to increment the counter
**Solution**:
I located currentThread.start() and placed contextSwitchCount++ directly before it. I then checked the final output to verify that the total was displayed 
**Time spent**:
35 min
---

### Entry 4 - [10 oct - 4pm]
**What I did**:Implemented Feature 3: Waiting Time Tracking

**Details**:
- Added readyQueueEntryTime and waitingTime variables to the Process class.
- Used System.currentTimeMillis() to record when a process entered the ready queue.
- Added methods to accumulate waiting time when a process was selected for execution.
- Created an ArrayList to keep track of all processes.
- Added a final table showing process name, burst time, waiting time, and turnaround time.
**Challenges**:
finding the correct methods and insertion points in the Java file
**Solution**:
searched for specific lines using VS Code and added the changes step by step
**Time spent**:
1 hr 
---

### Entry 5 - [10 oct  - 5 pm]
**What I did**: Tested and verified the updated CPU scheduling simulation

**Details**:
- Saved the updated SchedulerSimulation.java file.
- Ran the Java program using the Run option in VS Code.
- Checked the displayed process priorities and the total context switch count.
- Verified that the PROCESS STATISTICS table appeared at the end.
- Confirmed that turnaround time was calculated as waiting time plus burst time.

**Challenges**:
accidentally deleted the statement that displayed the total context switch count while editing the final output section
**Solution**:
restored the deleted statement and continued adding the statistics table in the correct location
**Time spent**:
30 min 
---

### Entry 6 - [ 11 oct - 5 pm]
**What I did**: Organized my GitHub commits and documented the assignment

**Details**:
- Created separate commits for the three implemented features.
- Pushed the code changes to my GitHub repository.
- Updated the student information section in MY_WORK.md.
- Documented my development activities and the challenges I faced
**Challenges**:
needed to make sure that the code changes and documentation were organized correctly
**Solution**:
checked the assignment instructions, and reviewed the required sections before preparing the final submission
**Time spent**:
3 hr
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [9 hours]

**Most challenging part**: implementing waiting time tracking because I needed to identify exactly when each process entered and left the ready queue

**Most interesting learning**: learned how Round-Robin scheduling gives processes CPU time in turns, how Java threads are started and joined

**What I would do differently next time**:
test each feature immediately after implementing it
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how Java threads can be used to simulate CPU scheduling through this assignment. Implementing Runnable allows the Process to define the work for a thread and start begins everything while join waits until it is finished. Sleep helps show the time spent executing
Round Robin was the part where processes take turns. The time quantum and waiting times with context switches affected the results quite a bit. It seems like some parts of that are harder to track than others ]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Accumulating waiting time correctly when processes returned was tricky from the start. I had trouble knowing exactly where to put the new variables and methods inside the java code. 
Tracking the ready queue entries and exits added to that. This meant being careful not to change the scheduling logic that was already working. It feels like this one took more attention than the others since it spread across multiple sections. I am not totally sure how it all fit together at first.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I broke things down into smaller steps mostly because it felt less overwhelming that way. Using search in VS Code helped find the methods without scrolling forever. I put in the waiting time variables before touching the scheduling loop. Checking how markReady and recordStart worked with the ready queue took longer than expected. There was a lot to keep track of. At some point I deleted the context switch output by mistake but restored it and slowed down after. Running the program showed the table was there. I think the order mattered more than I first realized. It worked out.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is useful for applications that need to do several things without forcing the users to wait unnecessarily. For example, a web browser can have different threads loading content and responding to the user. A music app can play audio, while another thread handles user controls. Operating systems also schedule multiple threads to share CPU resources in an efficient manner. The Round-Robin simulation gave me an understanding of why fair CPU scheduling and time quantum is important. These ideas can help developers to create applications that are more responsive and efficient]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent program that is executing. A thread is a smaller unit of execution within a process. Processes generally run in separate memory spaces, whereas threads within a process share memory and resources. Threads are cheaper to create and have less overhead than separate processes. 
In my SchedulerSimulation.java code, the Process class represents a simulated process. new Thread(process) creates an actual Java thread that will execute the run() method. Threads were used as they enable efficient simulation of CPU scheduling without the need to spawn separate operating system processes.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process does not complete within its time quantum, it is moved to the end of the ready queue to allow other processes to execute. In my simulation time quantum was 4000 ms and process P1 had burst time of 9603 ms. P1 ran for 4000 ms in first turn and had 5603 ms remaining. It was re-queued twice and ran three times altogether before it was done. 
This behavior promotes fairness because the other processes get CPU time instead of letting P1 use the CPU all the time.]

Example from my output:
```
[P1 executing quantum [4000ms]
Remaining time: 5603ms
P1 yields CPU for context switch
P1 added to ready queue

P1 executing quantum [4000ms]
Remaining time: 1603ms
P1 yields CPU for context switch
P1 added to ready queue]
```

**Explanation of example:**
[P1 burst time was 9603 ms and time quantum was 4000 ms. When P1 was run for the first time, it took 4000 ms and had 5603 ms remaining. Since it was not finished, it was placed back at the end of the ready queue. 
During the second execution, it ran for another 4000 ms and had 1603 ms remaining, so it was re-queued again. This shows the opportunity of other processes to use the CPU by Round-Robin scheduling.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's thread enters the New state when new Thread(process) is called inside addProcessToQueue()]

2. **Runnable**: [When the scheduler calls currentThread.start(), P1's thread becomes runnable and waits for CPU execution]

3. **Running**: [ P1's thread executes the run() method when the Java thread scheduler gives it CPU time]

4. **Waiting**: [P1 enters the Timed Waiting state when Thread.sleep() is called inside run(). Meanwhile, the main thread waits for P1's thread to finish by calling currentThread.join().
5. **Terminated**: [P1's thread terminates when its run() method finishes. If the simulated process still has remaining burst time, a new Java thread is created for its next execution turn]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling in an Operating System]

**Description**:
[An operating system needs to manage multiple runnable threads from different applications. These threads share the CPU and need regular opportunities to execute.]

**Why Round-Robin works well here**:
[Round-Robin scheduling gives each runnable thread a limited time quantum before allowing another thread to run. This improves fairness and responsiveness because one CPU-intensive task cannot continuously occupy the CPU. In my simulation, the timeQuantum variable controls the execution time, and the context switch counter tracks scheduling turns.]

### Example 2: [A Server Handling Multiple Client Requests
]
**Description**:
[A server may receive requests from several clients at the same time. Each client request can be represented as a task that needs processing time.
]

**Why Round-Robin works well here**:
[A Round-Robin approach can help distribute CPU time fairly between runnable tasks. This prevents one long CPU-intensive task from delaying all other requests. Similarly, my simulation adds unfinished processes back to the ready queue so other processes can execute.]

## Summary

**Key concepts I understood through these questions:**
1.The difference between processes and threads
2.How Round-Robin scheduling uses a time quantum and a FIFO ready queue to distribute CPU time fairly
3.How Java threads are created, started, paused, and completed

**Concepts I need to study more:**
1.Thread synchronization, race conditions, and how shared data is protected.
2.How real operating systems perform context switching and manage thread scheduling.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
