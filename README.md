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
<br/>The second article I read was about an open-source tool named Radare2. Radare2 is used to analyze binary files on Linux. So what is a binary file? A binary file is like a text file, but its information is stored in binary format; this format can be easily read by computers but nearly impossible for humans to read without some sort of tool. Currently, there are a few different ways to analyze a binary file, but these ways often are more complicated, involving various tools to get a complete understanding of what the binary file contains. Radare2 is an all-in-one binary file analyzer with good support for external tools via plugins, making this tool a one-stop shop instead of using several others. Every semester I compete in a competition known as the National Cyber League. Sometimes, one of the challenges involves a binary file; in the past, this would usually have taken me a long time to understand what the flag was. Hopefully, Radare2 will help me complete these challenges faster and with more accuracy. 
<br/>[D programming article](https://opensource.com/article/21/1/d-scripting)
<br/>[Radare2 article](https://opensource.com/article/21/1/linux-radare2)

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
The article I choose to read from IEEE Software was: "Serverless Computing-Where Are We Now, and Where Are We Heading?" by Davide Taibi, Josef Spillner, and Konrad Wawruch. This article gives us an update about serverless computing, one of the types of cloud computing services. To better understand serverless computing, I looked into the different kinds of cloud computing services, them being Software as a Service (SaaS), Platform as a Service (PaaS), Infrastructure as a Service (IaaS), and lastly, Function as a Service (FaaS), also known as serverless computing. Software as a Service allows users to connect to and use cloud-based apps via the Internet. A popular example of this would be Google Workspace (Gmail, Google Drive, Google docs, etc). The vendor of the app/apps manages the computing resources, such as servers, storage, and networking. Platform as a Service is a development environment where developers can build and test web applications. Similar to Software as a Service, the cloud service provider provides the computing resources. Additionally, they also offer development tools and database management systems to help developers better. It is essentially an online OS that has tools to help developers build their applications. Infrastructure as a Service is a service that provides a virtual environment with computing resources that clients can use. Unlike the earlier two, IaaS allows clients to use these resources however they want, whether it be for data storage or even virtualization. The cloud service provider only provides the resources in a virtual environment; the client manages all other things such as applications. Lastly, we have Function as a Service, also called serverless computing. FaaS is very similar to SaaS and PaaS in that the provider manages all the infrastructure to run the service in the case of SaaS, or the development environment in the case of PaaS. The main difference is that the client only pays for the computing resources they use instead of a fixed amount every month or year. This allows developers to have full access to all the provider's computing resources if need be, instead of a fixed amount. This lowers the costs for both the developer and the provider. The developer only pays for what they use, so they aren't losing any money when they are not using computing resources. The provider can save money by allowing more clients to access computing resources since resources are allocated as needed. 
<br/>[Link To Article](https://www-computer-org.nuncio.cofc.edu/csdl/magazine/so/2021/01/09305905/1pNkvj0oEnK)

## Stupid or Solid?
[Link To Article](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)

I thought the Stupid or Solid article was very intresting and should be something all computer science students should read so they can write better code. Starting with STUPID, these are mistakes that programmers often make and should try their best to avoid.  
### 1. Singleton - avoid the use of singletons
<span style="margin-left:3em">i. What are singletons? A singleton is when a  class is restricted to one single instance 
<br/><span style="margin-left:2em">a. Using singletons make testing difficult, and programs that rely on singletons often hide their dependencies

### 2. Tight coupling - also known as strong coupling
<span style="margin-left:2em">a. Should reduce coupling between modules
<br/><span style="margin-left:2em">b. Coupling is the degree to which each program module relies on another module
<br/><span style="margin-left:2em">c. Using tight coupling doesn't allow further changes in  the code without causing a domino effect 

### 3. Untestability - testing should not be hard 
<span style="margin-left:2em">a. Write code so that it can be easily tested
<br/><span style="margin-left:2em">b. Usually caused by tight coupling

### 4. Premature optimization - don't do it
<span style="margin-left:2em">a. It will only make code harder to read and follow
<br/><span style="margin-left:2em">b. Most compilers already do this for you 

### 5. Indescriptive Naming - Name classes, methods, attributes, and variables with good names
<span style="margin-left:2em">a. Do not abbreviate
  
### 6. Duplication - Try to avoid duplicating code
<span style="margin-left:2em">a. Ex. If a sort needs to be done multiple times on a list, you might as well write a function to do that sort instead of having the sorting code pasted in 10 different spots

<br/>Next up, we have SOLID; these principles should be followed in order to write better code.

### 1. Single Responsibility Principle
<span style="margin-left:2em">a. Every class should have a single responsibility
<br/><span style="margin-left:2em">b. Never be more than one reason for a class to change
<br/><span style="margin-left:2em">c. Split big classes into smaller ones
<br/><span style="margin-left:2em">d. Write straight forward comments

### 2. Open/Closed Principle
<span style="margin-left:2em">a. Software entities should be open for extension but closed for modification
<br/><span style="margin-left:2em">b. Should make all member variables private by default
<br/><span style="margin-left:2em">c. Write getters/setters when needed

### 3. Liskov Substitution Principle
<span style="margin-left:2em">a. Objects in a program should be replaceable with instances of their subtypes without altering the correctness of the program
<br/><span style="margin-left:2em">b. For example, let's say we have a rectangle and square class. We can say both of these classes have a width and height. A rectangle can have different widths and heights where a square has equal width and heights. A square can be a subclass of a rectangle since it shares the same properties of width and height, but on the contrary, a rectangle cannot be a square. This example would be a violation of the Liskov Substitution Principle

### 4. Interface Segregation Principle
<span style="margin-left:2em">a. States that many client-specific interfaces are better than one general-purpose interface
<br/><span style="margin-left:2em">b. In other words, you should not have to implement methods that you don't want to use
<br/><span style="margin-left:2em">c. Enforcing ISP gives you low coupling and high cohesion
<br/><span style="margin-left:3em">i. High cohesion means keeping similar and related things together
<br/><span style="margin-left:2em">d. Keep your components focused and try to minimize the dependencies between them
<br/><span style="margin-left:2em">e. Note this is similar to the Single Responsibility Principle

### 5. Dependency Inversion Principle
<span style="margin-left:2em">a. Two key points
<br/><span style="margin-left:3em">i. Abstractions should not depend upon details
<br/><span style="margin-left:3em">ii. Details should depend upon abstractions
<br/><span style="margin-left:2em">b. Could be rephrased as use the same level of abstraction at a given level; interfaces should depend on other interfaces, use interfaces in your class methods
<br/><span style="margin-left:2em">c. Not the same as dependency injection
<br/><span style="margin-left:3em">i. Dependency Injection is about how one object knows about another dependant object
<br/><span style="margin-left:2em">d. Rather than working with classes that are tightly coupled, use interfaces, this is called programming to the interface
<br/><span style="margin-left:3em">i. This reduces dependency on implementation specifics and makes code more reusable, also ensure that you can replace the implementation without violating the expectations of that interface, according to the Liskov Substitution Principle

The main takeaway of this article should be that when writing code, developers should try their best to avoid tight coupling as it will likely cause more headaches and trouble than good.

## Release early and often
### TOS Chapter 8
Chapter 8 of TOS discusses the importance of documenting code and various techniques developers could use to write better documentation. Documenting code is essential because it helps others understand your code, and it saves time and money when trying to fix a bug. 
<br/>[TOS Chapter 8](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Explaining_the_Code.html)
### TOS Chapter 9
Chapter 9 of TOS discusses the development strategy of releasing early and often. This technique allows developers to receive more valuable feedback from testers before the project is completed. This feedback can be used to make changes before everything has finished. It is easier to make changes to code during the development process as opposed to after. This feedback can also help you figure out features that users don't like so you don't have to spend as much time on it or remove it altogether.
<br/>[TOS Chapter 9](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch09.html)

## Chapter 5
Chapter 5 from our textbook Client-Centered Software Development is all about domain class development. First off, what is a domain class? A domain class is essentially a class that can be reused and inherited to better suit a developer's needs. Domain classes help developers reuse code and maintain good readability. The book uses a prevalent example; let's say we have a Person class with a collection of variables that could be used to describe someone, such as first name, last name, date of birth, etc. This person class would be an example of a domain class. From here, many different developers could inherit the Person class to better suit their needs. For instance, if someone wants to create an employee class, they could inherit all the Person attributes but add on to the employee class to better suit their needs, such as employee id, what branch they work at, etc. A different developer could inherit the same Person class but use it to create a student class that contains information on courses being taken, student id, etc. The Person class can be used in many different contexts, which is why it is a domain class in this example. The rest of chapter 5 goes into detail on creating, adding functionality, and testing a domain class. 

## Chapter 6
Chapter 6 from our textbook Client-Centered Software Development is all about the CO-FOSS approach to Database Development. I found this chapter to be particularly intresting because I took a Database Concepts course at the beginning of my Junior year, and I found all that fascinating. The first part of this chapter deals with a basic overview of databases and covers some SQL basics. In section 6.2.3 the book covers the CRUD functions, which are functions that developers should be able to do to any table in the database. CRUD stands for Create (inserting rows into a table), Retrieve (retrieve rows from a table), Update (alter rows in a table), and Delete (remove rows from a table). It then talks about database security, followed by database integrity, and finally, database testing. 

## Chapter 9
Chapter 9 from our textbook Client-Centered Software Development talks about the final steps in developing CO-FOSS projects, specifically after the development process what needs to be done for you to deploy your software effectively. This process varies from project to project, and what you use for one project could not work as well for another. These final steps are often overlooked, but I think they are just as important as the code writing process. It's almost like selling an awesome product, but no one will buy it or use it if you do the marketing wrong. The same idea applies here; if you don't deploy your software effectively, it won't be used or work as intended. You, as a developer, have to decide which path you want to go down. 

## Meeting Charleston
For this Meeting Charleston blog post, I attended both the Alumni Symposium and a Charleston NodeJS meeting. I thought the Alumni Symposium was a valuable experience in that Alumni could share their experiences after they graduated and the discussion part of the meeting allowed students, faculty, and alumni to further talk about experiences or answer questions. I do think if this meeting were in person, it would have worked out a little better as, over zoom, it was kind of hard to discuss with everyone at once. As for the NodeJS meeting, I thought this was slightly less informative and felt more like a youtube tutorial than anything else, as there wasn't much discussion between participants. Instead, it was one person sharing a presentation of API integration testing. None of the less it was still very informative, but it wasn't like a typical meetup like I was expecting. 
<br/>[NodeJS Group Page](https://www.meetup.com/CharlestonJS/events/gfvdfsyccfbhc/)
