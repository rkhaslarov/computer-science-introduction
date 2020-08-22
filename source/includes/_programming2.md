
# Programming basics II
> Task 4

```Homework
And here you are. Let's start the next challenge. 

What you have to do is the following:

Imagine that you were snowed under at your job and forgot to wash dishes. 
Now you have to do that immediately because your mom is coming. 
Create a flowchart of the algorithm and take into account the amount of the dishes (10).

Your friend asked you to go to grocery shopping and gave you a list. 
Create a flowchart of the algorithm (use given arrays of goods).

And the last one, you need to prepare the list of favourite films of your friend. 
Create a flowchart of the algorithm (use array).

Good luck!
```

The module opens the door to the next key topics of the programming such as variables, data types, loops and arrays. And of course, there will be intro to the functions. 

**Self-study materials**

* <a href="https://youtu.be/bum_19loj9A?list=PLBZBJbE_rGRV8D7XZ08LK6z-4zPoWzu5H" target="_blank">What Are Data Structures? (Watch)</a>
* <a href="https://youtu.be/NptnmWvkbTw" target="_blank">What is an Array? (Watch)</a>
* <a href="https://youtu.be/I8zR4TCmeZg" target="_blank">Working with variables Data Types and Arrays (Watch)</a>
* <a href="https://youtu.be/pmN9ExDf3yQ?list=PLBZBJbE_rGRV8D7XZ08LK6z-4zPoWzu5H" target="_blank">An Overview of Arrays and Memory (Watch)</a>
* <a href="https://press.rebus.community/programmingfundamentals/part/arrays/" target="_blank">Arrays (Read)</a>
* <a href="https://www.youtube.com/watch?v=PsZEGba-sRA&t=1s" target="_blank">Operators Loops and Control Structures (Watch)</a>
* <a href="https://youtu.be/ZT1DGuT6ulw" target="_blank">Flowchart and Loops (Watch)</a>
* <a href="https://www.youtube.com/watch?v=03UXhztlU0M" target="_blank">More on loops (Watch)</a>
* <a href="https://press.rebus.community/programmingfundamentals/part/loops/" target="_blank">Loops (Read)</a>
* <a href="https://youtu.be/l26oaHV7D40?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo" target="_blank">Programming Basics: Statements & Functions (Watch)</a>

## Programming basics II notes

__Arrays__

A list is a sequence of several variables, grouped together under a single name. Instead of writing a program with many variables x0, x1, x2, … you can define a single variable x and access its members x[0], x[1], x[2], etc. More importantly, you can put other expressions and variables inside the square brackets, like x[i] and x[i+1]. This allows us to deal with arbitrarily large data sets using just a single small piece of code.

One way to create an array is by enclosing several values, separated with commas, between square brackets:

myList = ["the first value in the list", 1999, 4.5]

This creates a list called myList of length 3. Each element of the list gets a number called its index: the initial element has index 0, the next element has index 1, and so forth. The individual variables comprising the list have the names
«listName»[«indexNumber»]

__Loops__

Loops are among the most basic and powerful of programming concepts. A loop in a computer program is an instruction that repeats until a specified condition is reached. In a loop structure, the loop asks a question. If the answer requires action, it is executed. The same question is asked again and again until no further action is required. Each time the question is asked is called an iteration. 

A computer programmer who needs to use the same lines of code many times in a program can use a loop to save time.

Just about every programming language includes the concept of a loop. High-level programs accommodate several types of loops. C, C++, and C# are all high-level computer programs and have the capacity to use several types of loops.

__Types of Loops__

* A for loop is a loop that runs for a preset number of times.
* A while loop is a loop that is repeated as long as an expression is true. An expression is a statement that has a value.
* A do while loop or repeat until loop repeats until an expression becomes false.
* An infinite or endless loop is a loop that repeats indefinitely because it has no terminating condition, the exit condition is never met or the loop is instructed to start over from the beginning. Although it is possible for a programmer to intentionally use an infinite loop, they are often mistakes made by new programmers.
* A nested loop appears inside any other for, while or do while loop.
* A goto statement can create a loop by jumping backward to a label, although this is generally discouraged as a bad programming practice. For some complex code, it allows a jump to a common exit point that simplifies the code.

__Loop Control Statements__

A statement that alters the execution of a loop from its designated sequence is a loop control statement. C#, for example, provides two loop control statements.

* A break statement inside a loop terminates the loop immediately.
* A continue statement jumps to the next iteration of the loop, skipping any code in between.

__Functions__

In programming, a named section of a program that performs a specific task. In this sense, a function is a type of procedure or routine. Some programming languages make a distinction between a function, which returns a value, and a procedure, which performs some operation but does not return a value.

Most programming languages come with a prewritten set of functions that are kept in a library. You can also write your own functions to perform specialized tasks.

The term function is also used synonymously with operation and command. For example, you execute the delete function to erase a word.
