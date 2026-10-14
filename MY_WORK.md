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
| **Full Name** | ثامر فالح فلاح السهلي |
| **Student ID** | 445050011 |
| **University Email** | 445050011@std.psau.edu.sa |
| **GitHub Username** | ThamerAlsahli |
| **Repository Link** | https://github.com/ThamerAlsahli/OS-Assignment1-Thamer-Alsahli.git?utm_source=copilot.com |
 
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

### Entry 1 - October 10, 2026, 10:30 PM
**What I did**: 
Set up my development environment, created my GitHub account, forked the starter repository, and updated my student ID in the code.

**Details**:
Logged in using my university email.

Forked the starter repository and renamed it according to the assignment instructions.

Opened the project in VS Code and connected it to GitHub.

Updated the student ID line in SchedulerSimulation.java and ran the program to ensure it worked correctly.

**Challenges**:
VS Code did not detect Git because Git was not installed on my device.

**Solution**:

Installed Git from the official website and restarted VS Code. After that, the Source Control panel worked properly.
**Time spent**:
3 hours
---

### Entry 2 - October 11, 2026, 1:30 AM
**What I did**:
Implemented Feature 1 (Process Priority)

**Details**:
Added a priority variable to the Process class.

Modified the constructor to accept the priority value.

Generated a random priority between 1 and 10 for each process.

Updated the ready queue message to display the priority.

Tested the program to confirm that priorities were displayed correctly.
**Challenges**:
The program initially failed to run because the constructor no longer matched the original parameters.

**Solution**:
Updated all Process object creations to use the new constructor with the priority parameter.

**Time spent**:

1 hour and 30 minutes.
---

### Entry 3 - October 14, 2026, 5:40 PM
**What I did**:

Implemented Feature 2 (Context Switch Counter).
**Details**:
Added a static contextSwitches variable.

Incremented the counter before each currentThread.start().

Printed the total number of context switches at the end of the simulation.

Ran multiple tests to verify that the counter increased correctly.
**Challenges**:

At first, I mistakenly incremented the counter inside addProcessToQueue(), which produced incorrect results

**Solution**:

Moved the increment to the correct location: right before starting each thread in the main scheduling loop.

**Time spent**:
1 hour

---

### Entry 4 - October 14, 2026, 6:25 PM
**What I did**:

Implemented Feature 3 (Waiting Time and Turnaround Time).

**Details**:
Added creationTime, totalWaitingTime, and lastEnqueueTime variables to the Process class.

Recorded the creation time inside the constructor.

Calculated waiting time inside addProcessToQueue().

Created a final summary table showing Burst Time, Waiting Time, and Turnaround Time.

Tested the program to ensure the values updated correctly.

**Challenges**:

Some processes showed zero waiting time because lastEnqueueTime was not being updated.

**Solution**:

Updated lastEnqueueTime after calculating waiting time.

**Time spent**:
1 hour and 10 minutes.

### Entry 5 - October 14, 2026, 7:35 PM
**What I did**:

Started writing MY_WORK.md and organizing the documentation.

**Details**:
Filled in the Student Information section.

Prepared the Development Log structure.

Reviewed the README.md again to ensure all requirements were covered.

Drafted initial answers for the technical questions.

**Challenges**:

It was difficult to organize my thoughts for the Reflection section.

**Solution**:

Reran the simulation and reviewed the code to recall the experience and write more accurate reflections.

**Time spent**:
50 minutes
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 
Approximately 7 hours and 30 minutes.

**Most challenging part**:

Implementing waiting time calculations because it required precise tracking of enqueue timestamps.

**Most interesting learning**:
 
Understanding how Round-Robin scheduling works in practice and how threads simulate CPU time slicing.

**What I would do differently next time**:

Start writing MY_WORK.md earlier instead of leaving most of it for the end.

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

Throughout this assignment, I gained a much clearer understanding of how multithreading works in Java and how threads simulate CPU scheduling. I learned how Thread.start() creates a new execution path and how Thread.join() forces the main thread to wait until a process finishes its time quantum. The assignment also helped me understand how Thread.sleep() can be used to simulate actual CPU execution time, making the scheduling behavior more realistic. Seeing multiple threads run sequentially in a Round-Robin pattern made me appreciate how operating systems manage processes behind the scenes. I also learned how thread coordination is essential to avoid race conditions and ensure predictable output. Overall, the project gave me hands‑on experience with thread lifecycle transitions and how they relate to real CPU scheduling.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was implementing the waiting time calculation in Feature 3. It required precise tracking of when each process entered the ready queue and how long it stayed there before running again. At first, some processes showed incorrect waiting times because I wasn’t updating the enqueue timestamp properly. This made me realize how sensitive timing‑based calculations are when dealing with threads. I also had to carefully test multiple runs to ensure the waiting time and turnaround time were accurate. The challenge came mainly from understanding the exact moments when a process is “waiting” versus “running,” which is not always obvious when threads are involved.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

To overcome the challenges, I relied heavily on testing and re‑examining the logic inside the scheduling loop. I added temporary print statements to track timestamps and verify when each process was added to the queue. This helped me identify where the waiting time calculations were going wrong. I also revisited the README and re‑read the explanation of Round‑Robin scheduling to make sure my understanding matched the expected behavior. Running the simulation multiple times allowed me to compare results and confirm that the logic was finally correct. Breaking the problem into smaller steps made it much easier to fix.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is used in many real-world applications to improve performance and responsiveness. For example, web browsers use multiple threads to load pages, play videos, and handle user interactions simultaneously without freezing. Operating systems rely on threads to manage processes and ensure fair CPU time distribution, similar to the Round‑Robin simulation in this assignment. Games also use threads to handle physics, rendering, audio, and input at the same time. Even mobile apps use background threads to download data while keeping the interface smooth. This assignment helped me understand how these systems work internally and why multithreading is essential for modern software.

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

A process is an independent program with its own memory space, while a thread is a lightweight unit of execution that runs inside a process and shares its memory. In this assignment, the Process class represents a simulated process, but each one is executed using a real Java thread created with new Thread(process) inside addProcessToQueue(). Threads were used instead of actual OS processes because they are faster to create, easier to manage, and allow shared access to variables like burst time and remaining time. Using threads also makes it possible to simulate Round-Robin scheduling without launching multiple operating‑system processes. This design keeps the simulation efficient and avoids the overhead of inter‑process communication.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process does not finish within its time quantum, it is placed back into the ready queue to wait for another turn. In my simulation, processes with large burst times were re‑queued multiple times before completing.

Example from my output:
```
 P3 yields CPU for context switch
➕ P3 added to ready queue │ Burst time: 8120ms │ Priority: 7

```

**Explanation of example:**
This means P3 did not finish during its quantum and was re‑queued to ensure fairness. Re‑queueing prevents any single process from monopolizing the CPU and guarantees that all processes receive equal time slices.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: 
A process thread is in the New state immediately after it is created in addProcessToQueue() using new Thread(process).

2. **Runnable**: 
The thread becomes Runnable when it is added to the ready queue and is waiting for the scheduler loop to start it.

3. **Running**: 
The thread enters the Running state when currentThread.start() is called inside the main scheduling loop, causing the run() method to execute.

4. **Waiting**: 
During execution, the thread enters the Waiting state when Thread.sleep() is called inside run() to simulate quantum progress.

5. **Terminated**: 
The thread reaches the Terminated state after finishing its quantum and completing the run() method, or after runToCompletion() finishes for the last process.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Operating System Scheduling

**Description**:
Operating systems use Round-Robin scheduling to manage CPU time among multiple running programs, especially in time‑sharing systems. Each program receives a fixed time slice, similar to the time quantum in this assignment. This ensures fairness and prevents any single program from blocking others. The context switches in my simulation behave like OS-level context switches between processes.

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

### Example 2: Multithreaded Web Servers

**Description**:
Web servers often use threads to handle multiple client requests simultaneously. Round-Robin scheduling can be used to ensure that no single request consumes all server resources. Each request gets a small time slice, similar to how each process in my simulation receives a quantum. This improves responsiveness and prevents slow clients from delaying others.

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

## Summary

**Key concepts I understood through these questions:**
1.The difference between OS processes and Java threads.

2.How Round-Robin scheduling ensures fairness.

3.How thread lifecycle states map to real execution behavior.

**Concepts I need to study more:**
1. Advanced thread synchronization.

2. How real operating systems implement context switching at the hardware level.

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
