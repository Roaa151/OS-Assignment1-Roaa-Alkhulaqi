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
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
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

### Entry 1 - [October 10, 2026, 4:02]
**What I did**:Forked the starter repository and set up my student ID (Part 1)

**Details**:
- Created/used my GitHub account with my university email.
- Forked `makopt/OS-Assignment1-Starter-481`, renamed it, and kept it public.
- Changed the student ID on line 150 to my own ID (446540228).
- Committed and pushed: `Update student ID for random number generation`

**Challenges**:I had to make sure every change was committed and pushed to GitHub and that the commits used my university email.

**Solution**:I used the Source Control panel in VS Code (stage, commit, Sync Changes) and then checked the commit list on github.com to confirm the commits appeared.

**Time spent**: around 7 min

---

### Entry 2 - [October 10, 2026, 4:12]
**What I did**:Read the full starter code and ran the program for the first time.

**Details**:
Read the classes Process and SchedulerSimulation: run(), runToCompletion(), addProcessToQueue() and the scheduler loop that calls Thread.start() and Thread.join().
Ran the program from the IDE and checked my unique parameters: 13 processes and a time quantum of 2000ms.
Followed P1 (burst time 4720ms) through the output to understand how Round-Robin re-queues a process.

**Challenges**:The console showed ? instead of the symbols (⚡, ✓, ▶, ➕).

**Solution**:I found that this was only a console character-encoding problem, not a bug in the logic, so the simulation itself was correct.

**Time spent**: 2 hours

---

### Entry 3 - [October 10, 2026, 8:42]
**What I did**:Feature 1: Process Priority.

**Details**:
Added a priority field (1-10, 10 = highest) with getPriority() and setPriority() to the Process class.
Created Random priorityRandom = new Random(studentID + 1) in main and assigned a priority to each process right after it is created.
Added a line in addProcessToQueue() that prints the priority every time a process enters the ready queue. The queue order stays FIFO.
Committed: Feature 1: introduced process priority and display.

**Challenges**:(1) Each new line moved the line numbers of the code below it, so it was hard to know where the next addition belonged. (2) My first comment line was indented too far to the right. (3) Using the existing random object to generate priorities would have changed all later random burst times.

**Solution**:(1) I searched for the exact code text with Ctrl+F (for example added to ready queue) instead of trusting line numbers. (2) I fixed the indentation so the comment matches the code under it. (3) I used a separate Random and compared the new output with the old one: the burst times were identical (P1 = 4720ms, P2 = 4528ms).

**Time spent**: 15 minutes

---

### Entry 4 - [October 10, 2026, 8:51]
**What I did**:Feature 2: Context Switch Counter.

**Details**:
Added private static int contextSwitchCount = 0; to SchedulerSimulation.
Added contextSwitchCount++; just before currentThread.start() in the scheduler loop, so it counts each time a process gets the CPU.
Printed Total context switches after the final "ALL PROCESSES COMPLETED" banner. My run printed 30.
Committed: feature 2: implemented context switch mechanism.

**Challenges**:I was not sure whether the printed total (30) was correct, and where exactly to place the increment so that runToCompletion() is not counted as an extra switch.

**Solution**:I counted the dispatches by hand from the output: 13 in the first round, 12 in the second and 5 in the third, which is 30. I placed the increment only before start(), because runToCompletion() continues the same process without switching.

**Time spent**: 5 minutes

---

### Entry 5 - [October 10, 2026, 8:55]
**What I did**:Feature 3: Waiting Time Tracking.

**Details**:
Added waitingTime and readyQueueEntryTime fields and the methods markEnteredReadyQueue(), markStartedRunning(), getWaitingTime() and getTurnaroundTime() to Process.
Used System.currentTimeMillis() to record when a process enters the ready queue and to add the waiting time when it is dispatched.
Stored all processes in a List<Process> and printed a final table with Process Name, Burst Time, Waiting Time and Turnaround Time (= Waiting Time + Burst Time), plus the averages.
Committed: feature 3: added waiting time calculation and reporting.

**Challenges**:This feature needed changes in many places (imports, fields, methods, main, addProcessToQueue(), and the end of main), and I was afraid of forgetting one and getting a cannot find symbol error. Also, waiting time has to be added over all rounds, not measured once.

**Solution**:I followed the steps in order and used Ctrl+F to check that each new name (such as markStartedRunning) appeared both in its definition and where it is used. I accumulated the waiting time with += every time the process is dispatched, and I ran the program to check the table.

**Time spent**: 4 minutes

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

**Total time spent on assignment**: [7 hours]

**Most challenging part**: Adding the new code in the correct places inside the existing program. Every insertion changed the line numbers below it, so I had to search for the exact code text instead of trusting line numbers. Feature 3 was the hardest because it needed changes in many places: the imports, the `Process` fields and methods, `main`, and `addProcessToQueue()`. I also needed time to understand how the `Process` objects, the `Thread` objects, the queue and the `processMap` work together.

**Most interesting learning**: A Java thread cannot be restarted, so `addProcessToQueue()` creates a new `Thread` for the same `Process` every time it returns to the ready queue, and the `processMap` connects each thread back to its process. I also found it interesting that Round-Robin gave short processes like P9 (1685ms) a quick finish while long ones like P1 (4720ms) needed three turns, with 30 context switches in total.

**What I would do differently next time**:I would start earlier and work over several days instead of one day, commit after every small step, and write each development log entry right after each work session while I still remember the details

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

[I learned that in Java a task can be written as a Runnable and executed by a Thread; in this program the Process class implements Runnable and its run() method simulates one time quantum. I learned that Thread.start() creates the new flow of execution, and that calling run() directly would not create a new thread. Thread.sleep() is used inside run() to simulate the CPU working, and Thread.join() makes the main scheduler thread wait until the process thread finishes its quantum. Because of join(), only one process runs at a time, which imitates a single CPU. I was surprised that a thread cannot be started twice, so addProcessToQueue() creates a new Thread for the same Process every time it returns to the queue. I also learned how Round-Robin shares the CPU fairly: in my output P9 (1685ms) finished in its first turn, while P1 (4720ms) needed three turns.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was adding the new code in the correct places inside a program I had not written. It was hard because every line I inserted moved the line numbers of the code below it, so I could not rely on them to find the next position. Feature 3 was the hardest case, because it needed changes in many places: the imports, the new fields and methods in Process, the lists in main, the call inside addProcessToQueue(), and the final table at the end of main. I was afraid of forgetting one of these places and getting a cannot find symbol error. This was also difficult because I first had to understand how the Process objects, the Thread objects, the queue and the processMap work together. In the end I understood that the scheduler loop in main controls everything, and the Process class only knows how to run one quantum.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I started by reading the README.md and the whole code before changing anything. Instead of trusting line numbers, I searched for the exact code text with Ctrl+F, for example added to ready queue and currentThread.start();, to find where each addition belonged. I added the features one at a time and ran the program after each one, so any error was easy to locate. To be sure Feature 1 did not break anything, I compared the new output with the old one and saw that the burst times were identical (P1 = 4720ms, P2 = 4528ms). For Feature 2 I verified the result by hand: 13 dispatches in the first round, 12 in the second and 5 in the third gives 30, the same as the printed total. I also committed after each feature using the Source Control panel, so I always had a working version to return to.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in a web browser, where one thread can render the page while another downloads images and another handles my clicks, so the browser does not freeze. A music player also uses threads: one plays the audio while another updates the interface and loads the next song. In games, separate threads can handle graphics, sound and network communication at the same time. A web server uses a thread for each client request, so many users are served together; this is similar to my simulation, where many processes share the CPU. The ideas from this assignment appear there: the time quantum is the time slice given to each task, the ready queue is the list of waiting requests, and a context switch is the cost of moving from one task to another. I now understand that a good design balances fairness and responsiveness against the overhead of too many context switches, like the 30 switches in my run.]

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

[A process is an independent program in execution with its own address space and resources, while a thread is a lightweight unit of execution inside a process that shares the code, heap and open files with the other threads of that process (Silberschatz, Galvin and Gagne, Operating System Concepts, 10th ed., Ch. 3 and 4). In SchedulerSimulation.java the class named Process is only a simulated process (name, burstTime, remainingTime); it is executed by a real Java thread created with new Thread(process) in addProcessToQueue(). We used threads because they share memory: the main thread and the process threads use the same Process objects and the same processMap, for example remainingTime is updated inside run() and then read by isFinished() in main without any inter-process communication. Creating a thread is also cheaper than creating a separate OS process, and switching between threads is faster because no new address space is needed, while separate processes would need pipes or sockets to exchange the same data.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process uses its whole time quantum without finishing, it is preempted, yields the CPU and is added again to the tail of the ready queue by addProcessToQueue(). In my output P1 has a burst time of 4720ms and the quantum is 2000ms: it ran 2000ms (remaining 2720ms) and was re-queued, ran another 2000ms (remaining 720ms) and was re-queued again, and on its third turn it ran the last 720ms and finished, so P1 was re-queued 2 times. This is important for fairness because no process can keep the CPU for a long time: every process gets a turn in each round, and short processes such as P9 (1685ms) finish in their first turn without waiting for the long ones.]

Example from my output:
```
[  ? P1 executing quantum [2000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P1 completed quantum 2000ms │ Overall progress: [████████░░░░░░░░░░░░] 42%
     Remaining time: 2720ms
  ? P1 yields CPU for context switch

  ? P1 added to ready queue │ Burst time: 4720ms
     Priority: 8 (10 = highest)
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 ? P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P13 ? P1]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[P1 used the full 2000ms quantum, so 2720ms were still remaining. It yielded the CPU, was added again at the end of the ready queue (after P13) and had to wait for all the other processes to get their turn before running again.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's thread is in the New state after new Thread(process) is executed in addProcessToQueue(), before it is started.]

2. **Runnable**: [After currentThread.start() in the scheduler loop, the thread is Runnable and ready to be scheduled by the JVM/OS.]

3. **Running**: [When the CPU executes the thread, its run() method is running: it prints "P1 executing quantum [2000ms]" and updates the progress bar.]

4. **Waiting**: [Inside run(), the call Thread.sleep(stepTime) puts P1's thread in a timed waiting state for a short time in each of the 5 steps, and at the same time the main thread is waiting at currentThread.join() until P1's thread ends.]

5. **Terminated**: [When run() returns (after printing "yields CPU" or "finished execution"), the thread is Terminated and join() returns. A terminated thread cannot be restarted, so P1 got a new Thread object for each of its 3 turns in my run.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[Description: A desktop operating system runs many programs together (browser, editor, music player). The OS scheduler gives each ready process or thread a short time slice (quantum) on the CPU, then performs a context switch and gives the CPU to the next one in the ready queue. In my simulation, each Process plays the role of a program, the time quantum is 2000ms, and the ready queue is the processQueue.]

**Why Round-Robin works well here**:
[It is fair because every program gets the CPU regularly and none can monopolize it. It is responsive because interactive programs get a turn quickly, and it is predictable because the maximum waiting time depends on the number of processes and the quantum. The cost is context-switch overhead, like the 30 switches counted in my run.]

### Example 2: [Name of application/scenario]

**Description**:
[A web server receives requests from many users at the same time. Each request is handled by a thread, and the server (or the OS) gives these threads CPU time in turns. The requests are like my processes, and the waiting requests are like the ready queue.]

**Why Round-Robin works well here**:
[It is fair because a very slow request cannot block the short requests behind it, like P9 finishing quickly in my output. It keeps response times reasonable for all users, and the time slice makes the waiting time predictable. Too many threads, however, increase context switching, so servers limit the number of threads.]

## Summary

**Key concepts I understood through these questions:**
1.Round-Robin scheduling with a time quantum and a FIFO ready queue (fairness and re-queueing).
2.Thread lifecycle and the roles of start(), sleep() and join(); a thread cannot be restarted.
3.Context switches have a cost (30 in my run), and Waiting Time + Burst Time = Turnaround Time.

**Concepts I need to study more:**
1.Thread synchronization (race conditions, locks, deadlock).
2.Other scheduling algorithms (priority scheduling, multilevel queue)

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
