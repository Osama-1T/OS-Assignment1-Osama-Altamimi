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
| **Full Name** | Osama Mohammed Altamimi |
| **Student ID** | 446050713 |
| **University Email** | 446050713@std.psau.edu.sa |
| **GitHub Username** | Osama-1T |
| **Repository Link** | https://github.com/Osama-1T/OS-Assignment1-Osama-Altamimi |
 
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

### Entry 1 - [07/10/2026 - 5:10 pm]
**What I did**:
Set up Git and prepared my project in VS Code.
**Details**:
Installed Git on my Windows computer.
Forked the starter repository and renamed it.
Cloned my repository to my computer.
Opened the Java project in VS Code.
**Challenges**:
 At first, the code . command was not recognized in PowerShell.
**Solution**:
I opened VS Code manually and used File to Open Folder to access my project.
**Time spent**: one and half hour 

---

### Entry 2 - [09/10/2026 - 6:38 Am]
**What I did**:
 Updated my student ID and prepared my first Git commit.
**Details**:
Opened the Java project in VS Code.
Replaced the default student ID with my university ID.
Used Source Control to save my changes.
Learned how to commit and push changes to GitHub
**Challenges**:
I was not familiar with the Git commit process in VS Code.
**Solution**:
I learned how to use Source Control, write a commit message, and push my changes to GitHub.
**Time spent**: one hour .

---

### Entry 3 - [09/10/2026 - 7:52 Am]
**What I did**:
 Added a priority value to each process.
**Details**:
Added a priority field to the Process class.
Generated priority values between 1 and 10.
Displayed each process’s priority in the Ready Queue.
Kept the Round Robin scheduling order unchanged.

**Challenges**:
 I needed to display process priorities without changing the FIFO scheduling behavior.
**Solution**:
 I used priority only as additional process information and kept the Ready Queue in its original order.

**Time spent**:
one hour .
---

### Entry 4 - [13/10/2026 - 10:53 pm] \\ i fixed feature 2 and sent it with feature 3 commit . (i'm not sent a private file for fixed feature 2 )

**What I did**:
 Added a context switch counter to the scheduler.
**Details**:
Added a counter to tr   ack process execution.
Increased the counter when a process started running.
Displayed the total number of context switches at the end.
Later corrected the counter declaration to make it static.

**Challenges**:
My first counter declaration was inside the main method instead of being a static class variable.

**Solution**:
 I moved the counter declaration outside main and used static int contextSwitchCount = 0;.
**Time spent**:
two hour
---

### Entry 5 - [13/10/2026 - 10:53 pm] 
**What I did**:
Implemented waiting time and turnaround time calculations.
**Details**:
Used System.currentTimeMillis() to measure waiting time.
Recorded when processes entered and left the Ready Queue.
Calculated turnaround time by adding waiting time and burst time.
Created a final performance table.
**Challenges**:
 At first, the final table displayed only the column headings without any process results.
**Solution**:
I added a list to keep all processes and used a for loop to print their final results.
**Time spent**:
two hour and half . 
---

### Entry 6 - [Optional 13/10/2026 - 11:30 pm]
**What I did**:
Fixed project issues, tested the simulation, and prepared the final code updates.
**Details**:
Found that I had opened an extra Java file from the Downloads folder.
Returned to the correct SchedulerSimulation.java file in my GitHub project.
Stopped a previous running instance before running the program again.
Successfully tested the simulation with 13 processes.
Checked the final table and the context switch counter.
Prepared a new commit to fix the earlier Feature 3 implementation.

**Challenges**:
I received a Java filename error and a message saying another instance was already running.
**Solution**:
 I opened the correct project file, stopped the previous run, and tested the program again. The simulation completed and displayed the performance results.
**Time spent**:
one hour and half .
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

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

[I learned that multithreading allows one program to work on multiple tasks using different threads. 
I understood that the CPU can switch between tasks very quickly, so the user may not notice the switching.
In this assignment, I saw how Round Robin scheduling gives each process a small amount of time to execute.
I also learned that start() begins a thread and join() makes the current thread wait until another thread finishes.
The sleep() method pauses the current thread for a certain amount of time. 
Before this assignment, I did not fully understand how threads work, 
but the simulation helped me understand them better.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was Feature 3, especially calculating the waiting time.
 At first, I found it difficult because a process can return to the ready queue more than once in Round Robin scheduling. I needed to understand how to calculate the total waiting time instead of counting only one waiting period. Another problem was that my program ran, but the final performance table showed only the column headings. 
 I was confused because I expected to see the results for every process. These two problems made Feature 3 the most difficult part of the assignment for me.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame the challenges by checking the code step by step. First, I learned that a process can wait several times in the ready queue, so I needed to add its waiting periods together. Then, I reviewed how the processes were added to the queue. To fix the empty results table, I added an allProcesses list to keep references to all the processes. I used a for loop to display the waiting time and turnaround time for each process. Finally, I ran the program again and checked that the results appeared in the table.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be useful in real-world applications, especially video games. In a game, different tasks need to be handled, such as loading data and receiving player input. A background thread can load data while the main thread keeps the game responsive. This helps the player continue interacting with the game instead of waiting for every task to finish. From my Round Robin assignment, I learned that scheduling is important when several tasks need CPU time.]

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

[A process has its own memory space, while threads in the same process share memory. Creating a process is usually more expensive than creating a thread. Each thread has its own execution path and stack, while a process runs independently with its own resources. In SchedulerSimulation.java, we used threads to simulate process scheduling inside one Java program because they are easier to manage and usually require fewer resources than separate processes. For example, the code uses new Thread(process) to create a thread for a simulated process.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[My ready queue uses FIFO, which means First In, First Out. The process that enters the queue first gets CPU time first. In SchedulerSimulation.java, the scheduler uses processQueue.poll() to take the first thread from the queue. If a process still has remaining burst time after its time quantum, it returns to the end of the queue when other processes are waiting. The priority values are displayed, but they do not change the scheduling order.]

Example from my output:
```
[P7 executing quantum [2000ms]
Remaining time: 2221ms
P7 yields CPU for context switch
P7 added to ready queue]
```

**Explanation of example:**
[Explanation of example:

In my output, P7 executes for a time quantum of 2000ms. After that, it still has 2221ms of remaining burst time, so it has not finished. P7 yields the CPU and is added back to the ready queue. This allows the next process to get CPU time, following the Round Robin scheduling method.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [ P1 enters the New state when new Thread(process) creates its thread inside addProcessToQueue(), before start() is called.]

2. **Runnable**: [P1 becomes Runnable when the scheduler calls currentThread.start().]

3. **Running**: [P1 starts running when the CPU executes its run() method.]

4. **Waiting**: [The main thread enters the Waiting state when it calls currentThread.join(), while P1 enters TIMED_WAITING when it calls Thread.sleep().]

5. **Terminated**: [P1 enters the Terminated state when its run() method finishes executing.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System Multitasking]

**Description**:
[An operating system can use Round Robin scheduling to share CPU time between tasks such as a browser, Word, and a music player. Each task acts like a process in my simulation and receives a short time quantum before the CPU switches to another task.]

**Why Round-Robin works well here**:
[This provides fairness because no single task can use the CPU continuously while others are ready. It also improves responsiveness because each task gets regular opportunities to execute.]

### Example 2: [Multiplayer Game Server]

**Description**:
[A multiplayer game server could use a Round Robin approach to schedule processing tasks for different players. Each task acts like a process in my simulation and receives a limited time quantum before the server switches to another task.]

**Why Round-Robin works well here**:
[This helps prevent one player’s long task from delaying all other players’ tasks. It also improves fairness and responsiveness by giving each task a regular chance to execute.]

## Summary

**Key concepts I understood through these questions:**
1.Round Robin scheduling uses FIFO and gives each process a time quantum before moving to the next process.
2.I learned the difference between threads and processes, and how threads share memory inside the same process.
3.I understood the thread lifecycle and how start(), sleep(), and join() work in my simulation.

**Concepts I need to study more:**
1.How context switching works inside a real operating system.
2.How thread synchronization prevents problems when multiple threads access shared data.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [✅] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [✅] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [✅] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [✅] Student ID is set in `SchedulerSimulation.java` (line 150)
- [✅] Code compiles and runs with no errors
- [✅] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✅] Each feature has clear comments

**Commits**
- [✅] **At least 3 meaningful commits, ideally 6 or more**
- [✅] **One commit per feature**
- [✅] Commits are spread over **different dates** (not all in the last hour)
- [✅] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [✅] Full name and student ID filled in at the top
- [✅] Development log has **5+ entries** on different dates
- [✅] Reflection: 4 questions, 5-7 sentences each
- [✅] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [✅] No `[...]` placeholders left
- [✅] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
