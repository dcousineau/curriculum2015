#Lesson 1 - Command line

![image](http://i.imgur.com/FJ5Hsq0.jpg)

## Before class

### Objective

Students will be able to use the basic CRUD (create, read, update, and delete) commands in the terminal. 

### Key points

* A terminal is a way to talk to a computer using commands.
* Commands specify the action you want the computer to do for you.
* Folders can contain folders and/or files. Taken in total, this forms a file hierarchy.

### Assessment

1. Complete the [exit-ticket](assessments/exit_ticket.md)

Students will show progress toward reaching the objective based on their performance on the exit-ticket quiz.

### Vocabulary

* Terminal
* Command
* Path / directory
* Directory structure / hierarchy
* GUI (Graphical User Interface)

### References


* [Presentation Slides](https://docs.google.com/presentation/d/1B1waYai67ysg7eqhc9Mm1O6fG7XO_WIPkCZxOiwyhj4/edit?usp=sharing)
* http://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything

## During class

### Do-now

1. Attendance: Teacher takes student attendance
2. Students are logging into their Cloud 9 account and creating the file structure on slide one of the [Presentation Slides](https://docs.google.com/presentation/d/1B1waYai67ysg7eqhc9Mm1O6fG7XO_WIPkCZxOiwyhj4/edit?usp=sharing)

### Opening

Today we will learn about the command line. This is important because the command line enables us to work in an environment without a visual interface. Before computers had the fancy interface or GUIs you are use to they were just terminals. 

What are files? What are folders? How do I view them in Windows? How about Mac? How do I go about copying a file? How about a folder? When I copy a folder, what happens to everything inside of it? How about if I want to rename a file? And delete a file?

When we perform any of the above operations in Windows or Mac, the operating system is translating our actions into command lines. Let's take a deeper look.

### Introduction of new material ("I do")

#### Basics

The **terminal** is a place where we talk to a computer. In the terminal, we issue **commands** to the computer. These commands are instructions that we would like the computer to do for us. Typically, if the command was executed successfully, the computer will not respond with anything.

The Basics are covered in slides 2-6 of the [Presentation Slides](https://docs.google.com/presentation/d/1B1waYai67ysg7eqhc9Mm1O6fG7XO_WIPkCZxOiwyhj4/edit?usp=sharing)

##### Directory

When I open Cloud9 and click on Window->New Terminal, I see something like:

![image](http://i.imgur.com/qDJZEpS.jpg)

Let's focus on the blue text. It says:

```
/home/ubuntu/workspace
```
This is the current **directory** (or path) that I am in. A directory a way to locate a file or folder. In this case, I am in the "workspace" folder which is inside the "ubuntu" folder which is inside the "home" folder. 

##### Running a command

I'm going to go back to Cloud9 and type in the command ``pwd``. After this, I press the "Enter" key. 

```
dopeboy@demo:/home/ubuntu/workspace $ pwd
/home/ubuntu/workspace
dopeboy@demo:/home/ubuntu/workspace $ 
```
This command instructed the computer to print the directory that I am in (which is same thing as the text in green). After it finished printing it out, it made a new line in anticipation of my next command.

#### List files and folders

How do we find all the files and folders in the directory we are in?

```
dopeboy@demo:/home/ubuntu/workspace $ ls
README.md*  hello-world.html  hello.js
dopeboy@demo:/home/ubuntu/workspace $ 
```
The `ls` command lists all the files and folders in the directory I am in. In my case, I have three files.

#### Copy a file

How do we copy a file?

```
dopeboy@demo:/home/ubuntu/workspace $ ls
README.md*  hello-world.html  hello.js
dopeboy@demo:/home/ubuntu/workspace $ cp hello.js duplicate_hello.js
dopeboy@demo:/home/ubuntu/workspace $ ls
README.md*  duplicate_hello.js  hello-world.html  hello.js
dopeboy@demo:/home/ubuntu/workspace $ 
```
The `cp` command copies a file. Notice that two filenames were supplied to the command. We can think of these filenames as *parameters* to the command. In this case, the first parameter is the name of the file we want to copy. The second parameter is what we want the new file to be named. 

The second `ls` command was used to verify that the file was indeed copied.

Notice how the copied file now appears in the file structure on in the top-left of the Cloud9 window. You just created this using the terminal

### Guided practice ("We do")

Let's take some time to complete the file directory you created in the Do Now. What we would like to do is turn the original file structure on the left and turn it into the file structure on the right. The only catch is you cannot use a mouse.
**This activity can be found on slide 7 of the [Presentation Slides](https://docs.google.com/presentation/d/1B1waYai67ysg7eqhc9Mm1O6fG7XO_WIPkCZxOiwyhj4/edit?usp=sharing)** 

![Imgur](http://i.imgur.com/3o2ThUY.png)

### Independent practice ("You do")

![Imgur](http://i.imgur.com/y88cMJC.png)

This information can also be found in slide 8 of the [Presentation Slides](https://docs.google.com/presentation/d/1B1waYai67ysg7eqhc9Mm1O6fG7XO_WIPkCZxOiwyhj4/edit?usp=sharing). 


#### Exit ticket

Give [exit-ticket](assessments/exit_ticket.md) quiz.

### Closing

Today you learned about the command line. This is important because the command line lets us talk to the computer in a defined and quick way. Also the command line has not changed in decades and shows no signs of changing in the future.


###How to Submit
This project is not required to be submitted as projects in the past have been. Students may save this workspace in their Cloud9 account

#### Homework

There is no homework for this lesson. However, it is at the discretion of the teacher to assign the [next lesson](../2-terminus/README.md) for homework if they would like.


## After class

* Grade exit-tickets. 
* Prepare for next lesson / hand off to next volunteer in rotation.
