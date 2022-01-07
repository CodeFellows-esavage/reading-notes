## Code 401 Prep Readings

### Solving Problems
[Source](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
- Common Mistakes
  - Improper Allocation of Time: use the measure twice, cut once methodology, really lay out your code and ensure you understand the problem before you actually start coding
  - Oversolving the Solution: keep your solution simple
- Steps for Approaching a Programming Problem
  1. Read the Problem Twice: most important step, be able to explain the problem to someone else
  2. Solve Manually Using Sample Data (3 sets)
        ```
        Reverse ZEBRA
        1. Write ZEBRA
        2. Start a new word, and put “a” as the first letter.  (Why –> because it is the last letter, we want to start here)
        3. Put “r” down as the 2nd letter.  (Why –> because it is the next letter backwards from the last letter we copied)
        4. Put “b” down as the 3rd letter.  (Why –> same as above)
        5. Etc

        ```
  3. Optimize Manual Steps
        ```
        1. Write “Zebra” down.
        2. Start at the last letter in the word and create a new empty word.
        3. Append the current letter to the new word
        4. If there is a previous letter, make the previous letter the current letter and start back at 3.
        ```
  4. Write the Manual Steps as Comments/Psuedo-code
  5. Replace Comments/Psuedo-code with Real Code
  6. Optimize Real Code 

### Thinking Like a Programmer
[Source](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2)
- Have a Framework
  - Steps to Solving a Problem
  1. Understand - Know what is being asked
  2. Plan - Don't dive into a problem w/o a plan (use comments/psuedo-code to outline the steps needed to achieve the desired outcome)
  3. Divide - Don't try to solve one big problem, split it up into smaller problems, then connect the dots
  4. Stuck? - approach bugs/errors with curiosity vs irritation
  5. Practice - solve micro problems through day to day hobbies, and complete coding challenges

### The 5 Whys
[Source](https://www.mindtools.com/pages/article/newTMC_5W.htm)
- use the 5 Whys to troubleshoot, improve quality, problem solve

Steps to Using this Process:
1. Assemble a team
2. Define the problem
3. Ask "why" the problem is occuring
4. Ask "why" 4 more times for each answer generated
5. Know when to stop
6. Address the Root Cause
7. Monitor fixes

### Event Loops
[Source](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- JavaScript runtime in chrome (V8) is comprised of a heap and a stack
- Call Stack
  - single threaded, can execute one piece of code at a time
  - top of the stack is what is being executed
  - stack shrinks as code blocks are executed until nothing is in it
  - blowing the stack, when the maximum number of items in the stack exceed it's capacity (endless loops)
  - blocking - code blocks that are slow on the stack that prevent the next item in the stack from being executed
- Concurrency & the Event Loop
  - event loop look at the stack and the call back queue, if the stack is empty and there is code to be executed in the call back queue, it moves that code from the call back queue to the stack to be executed.
  - call back queue - holding place for code that has finished executing and needs to renter the queue
- don't block the call stack or the website can't render
  - rendering happens every 16 milliseconds but only if the call stack is clear
  - rendering is given higher priority over the call back queue
  - if you utilize the call back queue you can write your code in a way that allows the website to execute rendering

### The Super Mario Effect
[Source](https://www.youtube.com/watch?v=9vJRopau0g0)
- Frame challenges in a way that you are focused on the end goal while minimizing getting hung up on the failures experienced along the way. Instead try to learn as much as posible from the these failures and what actions you can take to ensure you avoid them on subsequent attempts. Approaching problems like this show a statistically improved chance of actually completing the problem.