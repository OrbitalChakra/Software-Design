 
The Gaming Room
CS 230 Project Software Design Template
Version 1.0
 
Table of Contents

CS 230 Project Software Design Template	1
Table of Contents	2
Document Revision History	2
Executive Summary	3
Design Constraints	3
System Architecture View	3
Domain Model	3
Evaluation	3
Recommendations	5

Document Revision History

Version	Date	Author	Comments
1.0	<mm/dd/yy>	<Your-Name>	<Brief description of changes in this revision>

Instructions 
Fill in all bracketed information on page one (the cover page), in the Document Revision History table, and below each header. Under each header, remove the bracketed prompt and write your own paragraph response covering the indicated information.  
Executive Summary

Client is looking for a gaming service to be implemented over the web. We are looking at a solution with the idea of design patterns being implemented to create the working service for the client. Implementation of patterns like the singleton and iterator will be used on certain data structures. We will be unable to produce and develop the game without your company’s versioning and collaboration.

Design Constraints

In the distributed space we are always concerned about the restructuring of data types and the duplication over the same space. We must be weary of the constraints of server capacity and networking allocation over the company’s different distributions of this game.

System Architecture View

Please note: There is nothing required here for these projects, but this section serves as a reminder that describing the system and subsystem architecture present in the application, including physical components or tiers, may be required for other projects. A logical topology of the communication and storage aspects is also necessary to understand the overall architecture and should be provided.

Domain Model

This model has an abstract class called entity that is implemented by three other subclasses: Game, Team, and Player. We also have a class that is constructed to be a singleton and will be responsible for the creation of the relationships of new game initiatives. The game class will be responsible for the initialization of the Team objects and the Team objects will be responsible for the Player objects. The main program will be in the ProgramDriver class.

 

Evaluation

Using your experience to evaluate the characteristics, advantages, and weaknesses of each operating platform (Linux, Mac, and Windows) as well as a mobile device, consider the requirements outlined below and articulate your findings for each. As you complete the table, keep in mind your client’s requirements and look at the situation holistically, as it all has to work together. 

In each cell, remove the bracketed prompt and write your own paragraph response covering the indicated information. 

Development Requirements	Mac	Linux	Windows	Mobile Devices
Server Side	Mac is very proprietary. The use of certain vendors will be limited in the software stack. Although Mac can be used to virtualize many machines. The requirements of running a mac on the server side will be very costly and will not be customizable. 	A server-side Linux app will be easy to create and is supported by an enormous breadth of developers. The strength of Linux here is that it will be easy to set up on any hardware you choose.	Windows development on the stack can be hard. It will call for a hardy developer who knows the proprietary knowledge of things like the database and software development kits in windows. 	You will only be able to make a request to the server and post/get. You cannot set up gateways or host different points.
Client Side	Developing on a Mac is very productive. The system is well optimized and uses an industry-standard compiler for many languages. Client-side development is also supported by many very powerful applications, but you can’t find many mac developers. 	The client for Linux is very cheap compared to other systems. The distributed system we look to create here is supported by other types of technologies stacks that are industry-proven.	Windows development on the client will be pretty straightforward. You can find the technology you need and will not be faced with much pushback from your stack. 	The distribution of a mobile client would be easy as you could put it through many mobile stores if it gets approved. Otherwise, you are going to be distributing binaries on the internet without any backing from big names like Google or Apple.
Development Tools	With XCode and swift, you can build a very strong application. The application will be native to the mac space and can be used only on macs. 	Linux has IDEs like geany and can run most compilers so you can choose almost any open source language. The problem with the IDE is that it is very hard to work with as it does not have many features or a community constantly working on pushing new things into the application. 
You can use docker and Kubernetes 	Things in the Windows space that you can use for this project are VS Code and Docker. Also if you need to push a server-side application you can use the Windows subsystem for Linux. 	You can make phone calls to the customer with a mobile device. You could also access your git so you could share with someone new or review a recent push or fork. 

 
Recommendations

Analyze the characteristics of and techniques specific to various systems architectures and make a recommendation to The Gaming Room. Specifically, address the following:

1.	Operating Platform: We would like to recommend a Linux system for this application you are trying to produce. Linux is good at distributing many instances of an application and has support of system tools like docker and Kubernetes. 

2.	Operating Systems Architectures: The operating system we are choosing has a good support in distributing systems so you can scale easily and effectively at a low price. We are also picking this system because the stack is changing so we can stay on top of issues with bugs. Linux will have the ability to use distributed virtual machines so that the instances of our application will be easy to manage. 

3.	Storage Management: A storage management platform will be a cloud-based system using relational databases to store user data. We will not need to worry about scaling as that will be managed off-site, we will have to budget for more use of IT services down the road.

4.	Memory Management: Linux uses paging so we can know that we can optimize calls to the stack. The use of memory for computation will be dependent on the cloud provider. Our client will be managed by users, so the user will have to meet minimum requirements on their system to enjoy Draw it or Lose it. 

5.	Distributed Systems and Networks: The network can produce many different instances of the games you would like to have. As long as we keep a single service, we can know that the games will have however many teams and players playing you want. We could produce a system that gets as large as you want if we are building out to meet the demand. The use of a single service will allow us to keep track of stores of user data such as scores and ids.

6.	Security: To protect data we must be sure our instances are being called only when we need them to be called. This will help keep data under the hood. With this, we can protect what we use to create the game. The data we transfer will be unencrypted so that over the network, people can see what is being transferred.

