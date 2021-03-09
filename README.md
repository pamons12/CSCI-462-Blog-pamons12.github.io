## Introduction
Welcome to my blog.
<br/> I am a senior at the College of Charleston and am pursuing a BS in Computer Science.

## Reflections on FOSS
The Catherdral and the Bazaar
<br/><span style="margin-left:3em">The article "The Cathedral and the Bazaar" by Eric S. Raymond is about open source and uses Linux as an example of an open-source piece of software. A Cathedral typically consists of a single architect who designs the whole building from the bottle up. On the other hand, a Bazaar typically is a collection of many different markets or shops that are privately owned, but they individually still exist under the same roof. Interestingly enough, this article makes the connection between Linux and a Bazaar. Unlike a Cathedral, Raymond argues that Linux is like a Bazaar because there are many different contributors and versions, but in the end, they are all still under the Linux name. I thought this analogy was very clever, and I could see how this could be applied to almost any piece of open-source software. 
  
As of today, my group has been deciding which open-source software we would like to work on throughout this semester. We are meeting later today to make our final decision and to see if we can get this software up and running. Our three candidates are listed below:
1. Tanaguru Contrast Finder
<br/><span style="margin-left:3em">Tanaguru is a project dedicated to enhancing the quality and accessibility of web and digital products. The Tanaguru Contrast Finder is an application designed to run within Tanaguru and helps find contrasting colors that promote design quality and accessibility for visually impaired users. Contrast Finder is mostly coded in Java, which we are all familiar with.
2. Miradi
<br/><span style="margin-left:3em">Miradi is an open-source project management software designed to be used by conservation-based organizations. It helps teams to design, plan, implement, and monitor these organizations' projects. Miradi is also primarily written in Java, which we are all familiar with. 
3. Blockly
<br/><span style="margin-left:3em">Blockly is an open-source project that focuses on teaching kids K-12 computer programming. Rather than typing code out, it uses blocks that piece together like puzzle pieces. Blockly is written in  Javascript, which we have limited knowledge of but would be a good learning experience.
  
## Reflections on Open Source in Today's World
The first article I read was about the programming language D. I have personally never heard of the language D, but I found it quite intresting and could see some uses to it. D is usually known as a system programming language, but it can also be used as a scripting language. Although python is the industry leader in scripting languages, D is a good alternative for quick prototyping. After going through the short tutorial of writing and running a simple script, I could see how someone who is proficient in D could prototype a program much quicker than a python programmer could.  This is due to how much power one line of code could have in D; for example, it would only take three fairly short lines of code to read in a file and print each line of that file. Although D seems like a relatively simple language, I think it could have a lot of potential for many different fields. 

<br/>D programming article: https://opensource.com/article/21/1/d-scripting
<br/>Exploring binaries article: https://opensource.com/article/21/1/linux-radare2

## This bugs me
6.4. Exercise - Find the Oldest Bug
Find the oldest bug that's still open in your chosen project. Write a blog entry describing the problem, with a theory about why the bug hasn't been resolved yet. (Bonus points if you can actually resolve the bug.)

<br/><span style="margin-left:3em">The oldest bug that is still open that I could find for my chosen project, Blockly, is from  March 25, 2015. If I understand the bug correctly, it seems as if when a block is dragged off the screen in the Blockly environment, it will scroll the web page down rather than the Blockly environment itself. I attempted and failed to recreate this on different browsers such as Microsoft Edge, Google Chrome, and Firefox. From my understanding, it seems as if this bug is fixed. Although when I tried to drag the block off-screen, the Blockly window itself did not scroll either. 
  
## What's Happening? 
7.22 Run the diff command again, this time without the -u flag, and compare the output to the output when the -u flag is used.
<br/><span style="margin-left:3em">-Without the -u flag, the diff command displays less information about the two files' changes. It only shows the difference between the two files; it doesn't include the time it was changed or the line numbers where the difference occurred. 
<br/>Without the -u flag
```
8c8
<    printf("Hello, World.\n");
---
>    printf("Hello, World!\n");
```
With the -u flag
```
--- helloc.c.punct    2021-02-11 12:55:37.610201495 -0500
+++ hello.c    2021-02-11 12:55:58.562039387 -0500
@@ -5,6 +5,6 @@
 #include <stdio.h>
 int main(){
-       printf("Hello, World.\n");
+       printf("Hello, World!\n");
        return 0;
 }
```
7.8, 7.9
  
### Article from IEEE Software: "Serverless Computing-Where Are We Now, and Where Are We Heading?"
[Link To Article](https://www-computer-org.nuncio.cofc.edu/csdl/magazine/so/2021/01/09305905/1pNkvj0oEnK)

## Stupid or Solid?
[Link To Article](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)

I thought the Stupid or Solid article was very intresting and should be something all computer science students should read so they can write better code. Starting with STUPID, these are mistakes that programmers often make and should try their best to avoid.  
### 1. Singleton - avoid the use of singletons
<span style="margin-left:3em">i. What are singletons? A singleton is when a  class is restricted to one single instance 
<br/><span style="margin-left:2em">a. Using singletons make testing difficult, and programs that rely on singletons often hide their dependencies

### 2. Tight coupling - also known as strong coupling
<span style="margin-left:2em">a. Should reduce coupling between modules
<span style="margin-left:2em">b. Coupling is the degree to which each program module relies on another module
<span style="margin-left:2em">c. Using tight coupling doesn't allow further changes in  the code without causing a domino effect 

### Untestability - testing should not be hard 
<span style="margin-left:2em">a. Write code so that it can be easily tested
<span style="margin-left:2em">b. Usually caused by tight coupling

### Premature optimization - don't do it
<span style="margin-left:2em">a. It will only make code harder to read and follow
<span style="margin-left:2em">b. Most compilers already do this for you 

### Indescriptive Naming - Name classes, methods, attributes, and variables with good names
<span style="margin-left:2em">a. Do not abbreviate
  
### Duplication - Try to avoid duplicating code
<span style="margin-left:2em">a. Ex. If a sort needs to be done multiple times on a list, you might as well write a function to do that sort instead of having the sorting code pasted in 10 different spots

Next up, we have SOLID; these principles should be followed in order to write better code.

### Single Responsibility Principle
<span style="margin-left:2em">a. Every class should have a single responsibility
<span style="margin-left:2em">b. Never be more than one reason for a class to change
<span style="margin-left:2em">c. Split big classes into smaller ones
<span style="margin-left:2em">d. Write straight forward comments

### Open/Closed Principle
<span style="margin-left:2em">a. Software entities should be open for extension but closed for modification
<span style="margin-left:2em">b. Should make all member variables private by default
<span style="margin-left:2em">c. Write getters/setters when needed

### Liskov Substitution Principle
<span style="margin-left:2em">a. Objects in a program should be replaceable with instances of their subtypes without altering the correctness of the program
<span style="margin-left:2em">b. For example, let's say we have a rectangle and square class. We can say both of these classes have a width and height. A rectangle can have different widths and heights where a square has equal width and heights. A square can be a subclass of a rectangle since it shares the same properties of width and height, but on the contrary, a rectangle cannot be a square. This example would be a violation of the Liskov Substitution Principle

### Interface Segregation Principle
<span style="margin-left:2em">a. States that many client-specific interfaces are better than one general-purpose interface
<span style="margin-left:2em">b. In other words, you should not have to implement methods that you don't want to use
<span style="margin-left:2em">c. Enforcing ISP gives you low coupling and high cohesion
<span style="margin-left:3em">i. High cohesion means keeping similar and related things together
<span style="margin-left:2em">d. Keep your components focused and try to minimize the dependencies between them
<span style="margin-left:2em">e. Note this is similar to the Single Responsibility Principle

### Dependency Inversion Principle
<span style="margin-left:2em">a. Two key points
<span style="margin-left:3em">i. Abstractions should not depend upon details
<span style="margin-left:3em">ii. Details should depend upon abstractions
<span style="margin-left:2em">b. Could be rephrased as use the same level of abstraction at a given level; interfaces should depend on other interfaces, use interfaces in your class methods
<span style="margin-left:2em">c. Not the same as dependency injection
<span style="margin-left:3em">i. Dependency Injection is about how one object knows about another dependant object
Rather than working with classes that are tightly coupled, use interfaces, this is called programming to the interface
This reduces dependency on implementation specifics and makes code more reusable, also ensure that you can replace the implementation without violating the expectations of that interface, according to the Liskov Substitution Principle

The main takeaway of this article should be that when writing code, developers should try their best to avoid tight coupling as it will likely cause more headaches and trouble than good.
