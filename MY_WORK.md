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
| **Full Name** | [Ghazal Ali Ghallah] |
| **Student ID** | [446051422] |
| **University Email** | 446051422@std.psau.edu.sa |
| **GitHub Username** | [g219hazal] |
| **Repository Link** | [https://github.com/g219hazal/OS-Assignment1-Ghazal-Ghallah] |
 
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

### Entry 1 - [October 3, 2026]
**What I did**:Forked the starter repo and set my student ID

**Details**:
- Forked the starter repo and renamed it to OS-Assignment1-Ghazal-Ghallah
- Changed the student ID to 446051422
- Ran the program, I got 14 processes and the time quantum was 5000ms


**Challenges**:
No real challenges, the steps in the README were clear.

**Solution**:
None needed.
**Time spent**:
 20 minutes

---

### Entry 2 - [October 6, 2026]
**What I did**:
 Feature 1 priority
**Details**:
- Added a priority variable in the Process class with get and set methods
- Every process gets a random priority from 1 to 10
- The priority shows when the process is added to the ready queue
- The order of the queue did not change, it is still FIFO
**Challenges**:
No big challenges, I just had to read the code first to find where to add the priority and where to print it.
**Solution**:
I read the Process class and the addProcessToQueue() method before changing anything.
**Time spent**:
30 minutes
---

### Entry 3 - [ctober 8, 2026]
**What I did**:
Feature 2 context switch counter
**Details**:
- Added a static counter and increased it before currentThread.start()
- Printed the total at the end, it was 24
**Challenges**:
I ran the program but the total context switches line was not showing.
**Solution**:
I didn't save the file before running. After saving with Ctrl+S it worked and showed 24. I turned on Auto Save so it doesn't happen again.
**Time spent**:
45 minutes
---

### Entry 4 - [October 9, 2026]
**What I did**:
Feature 3 waiting time table
**Details**:
- Saved the time when the process is created and when it finishes using System.currentTimeMillis()
- Waiting time = finish - arrival - burst, turnaround = waiting + burst
- Made a list of all processes so I can print the table at the end
**Challenges**:
Some numbers were a little bigger than I expected, like P3 waiting time was 10208 not 10000.
**Solution**:
I learned it's because printing and creating threads also take some time, so it adds a few milliseconds every switch.
**Time spent**:
30 minutes
---

### Entry 5 - [October 9, 2026]
**What I did**:
Started working on MY_WORK.md
**Details**:
- Filled my information
- Wrote the development log
- Read all the questions in Part B and Part C
**Challenges**:
At first I didn't understand what each part of the file needs.
**Solution**:
 I read the instructions in MY_WORK.md and the README again and did the parts one by one.
**Time spent**:
2 day
---

### Entry 6 - [October 10, 2026]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

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

[I learned that in this program every process runs inside its own thread, which is created with `new Thread(process)` in addProcessToQueue(). When the main thread calls `start()`, the process thread starts running its run() method. Then the main thread calls `join()`, so it stops and waits until the process finishes its quantum before taking the next one from the queue. I also learned that `Thread.sleep()` is used to act like the process is doing work on the CPU for some time. Seeing the output helped me understand that Round-Robin is fair, because a long process like P2 does not keep the CPU, it goes back to the end of the queue. Because of that, short processes like P3 and P5 finished early instead of waiting for the long ones.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was understanding the code at the beginning. The file is long and has two classes, so at first I didn't know which part does what and where I should add my changes. The colors and the progress bars also made the code look more complicated than it really is. I was also confused about how the main thread and the process threads work together, because they run at different times. It was hard to add the features before I understood the whole flow of the program. Once I understood the flow, adding the three features was much easier.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[First, I read the README and the code again slowly before changing anything. I followed what happens to one process, from addProcessToQueue() to start(), run() and join(). After that, I added one feature at a time and ran the program after every change to make sure it still worked. I also checked my results by calculating them by hand. For example, I counted the context switches from the output: 14 in the first round, 8 in the second and 2 in the last one, which gave 24 like my program. I also checked that P3 waited about 10000ms because it had to wait for P1 and P2.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[I see multithreading every day on my laptop. When I have the browser, music and VS Code open at the same time, they all look like they are running together. But the CPU is actually switching between them very fast, and the operating system gives each one a small time slice. This is the same idea as the time quantum in my program. When one program's time is done, the CPU moves to the next one, just like a context switch in my simulation. This way no program takes the CPU forever, so the laptop stays responsive even with many apps open.]

### Optional: What would you like to learn more about?

[Other scheduling algorithms like priority scheduling, and how threads can really run at the same time.]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate. I understand start(), join() and sleep() well, but I need more practice with threads running at the same time.]

### Optional: Feedback on the assignment

[It was helpful because I could see Round-Robin working in the output instead of only reading about it.]

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

[A process is a running program that has its own memory, while a thread is a smaller unit that runs inside a process and shares its memory. In our code, the class called `Process` is only a simulated process, and the real thing that runs it is a Java thread created with `new Thread(process)` in addProcessToQueue(). The first difference is memory sharing: all the threads share the same objects, so the main thread can call `process.isFinished()` on the same object the thread changed, and they all use the same static `contextSwitches` counter. The second difference is creation cost: threads are cheap to create, my program made a new thread 24 times with no problem, while creating 24 real processes would need a separate memory space for each one and would be much slower.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process does not finish within its time quantum, it gives up the CPU and is added again to the end of the ready queue. In my output, P2 has a burst time of 11700ms and the time quantum is 5000ms, so it could not finish in one turn. It ran three times (5000ms, 5000ms, then 1700ms) and was re-queued 2 times before it finished. This is important for fairness because a long process like P2 does not keep the CPU, so short processes like P3, P5 and P7 could finish early instead of waiting behind it.]

Example from my output:
`P2 executing quantum [5000ms]
P2 completed quantum 5000ms │ Overall progress: 42%
Remaining time: 6700ms
P2 yields CPU for context switch
P2 [Priority: 9] added to ready queue │ Burst time: 11700ms

P2 executing quantum [5000ms]
Remaining time: 1700ms
P2 yields CPU for context switch
P2 [Priority: 9] added to ready queue │ Burst time: 11700ms

P2 executing quantum [1700ms]
Remaining time: 0ms
P2 finished execution`
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[In the first turn P2 used the full 5000ms and still had 6700ms left, so it went to the back of the queue. In the second turn it used another 5000ms and had 1700ms left, so it was re-queued again. In the third turn it only needed 1700ms, which is less than the quantum, so it finished. Between its turns, the other processes in the queue got their chance to run.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's thread is in the New state when it is created with `new Thread(process)` in addProcessToQueue(), before the scheduler starts. It exists but is not running yet.]

2. **Runnable**: [P1 becomes Runnable when the main thread calls `currentThread.start()` in the while loop. Now it is ready and waiting for the JVM to give it the CPU.]

3. **Running**: [P1 is Running when its run() method actually executes, which is when the output prints "P1 executing quantum [5000ms]".]

4. **Waiting**: [Inside run(), P1's thread calls `Thread.sleep(stepTime)`, so it is in a timed waiting state while it simulates work. At the same time, the main thread is waiting because it called `currentThread.join()` and cannot continue until P1 finishes its quantum.]

5. **Terminated**: [P1's thread is Terminated when run() ends after the quantum. Because P1 still had 3363ms left, addProcessToQueue() created a new thread for it, and that second thread was terminated after "P1 finished execution!". So P1 actually used two different threads.
]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU scheduling on a laptop]

**Description**:
[On my laptop I usually have the browser, music and VS Code open at the same time. The CPU can only run one thing at a time on each core, so the operating system scheduler switches between these programs very fast. Each program is like a process in my simulation, and the small time it gets is like the time quantum.
]

**Why Round-Robin works well here**:
[Round-Robin is fair because every program gets a turn and no program can keep the CPU forever. It also keeps the laptop responsive, because even if one program is doing heavy work, the others still get CPU time quickly. It is also predictable, since each program knows it will get its turn after the others, like the ready queue in my code.]

### Example 2: [ A web server]

**Description**:
[A web server, like a university website, gets requests from many students at the same time. The server can use threads to handle the requests and switch between them. Each request is like a process, and the server gives each one a short time before moving to the next.]

**Why Round-Robin works well here**:
[It is fair because every student gets served and one big request does not block everyone else. Small requests, like opening a page, finish fast, just like the short processes P3 and P5 in my output. This keeps the website responsive for all users.]

## Summary

**Key concepts I understood through these questions:**
1. How start(), join() and sleep() control the thread lifecycle
2. How Round-Robin re-queues unfinished processes to keep things fair
3. The difference between a thread and a process, and why threads are cheaper

**Concepts I need to study more:**
1. How threads run truly at the same time on multiple cores
2. Other scheduling algorithms like priority scheduling and SJF

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
