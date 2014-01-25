# code simplicity

### intro notes: 

- difference bw good and bad programmer is understanding. 
- book will help with: 
	- understanding why software should be developed in a certain way.
	- communicating ideas effectively to other software engineers by helping me understand the fundamental principles on which good s/w engineers base their decisions.

## chapter 1: introduction 

- computers can do a lot of work really fast; creating societal change.
- computers break a lot. reasons:
	- bad programming is one of the only reasons for this (in the context of software)

###### complexity is the major reason. (eg: for context, ms word 2000 ~30 million LOC). the bigger the program gets, the more the complexity increases. 

- programming has to become the act of reducing complexity to simplicity. 
- eg: in the short term programmers want to make something "just work", and this often disregards that they may be writing code that may be incomprehensible to other programmers in the long run/to maintain. this next programmer might add to the complexity by adding his fixes, etc. 
- writing simple to understand programs != absence of lots of code or absence of advanced tecnniques/technologies. 


#### what is a program 
- sequence of instructions given to a computer.
- actions taken by computer as a result of being given instructions.

^ refer to writing and using a program respectively. 

random info: 
- quality of code is the largest problem faced by software projects today. 
- most of this book will focus on improving the structure and quality of the instructions that we give to the computer. 

## chapter 2: the missing science

- this book is about software design
- designing software == planning it out. things to plan:
	- structure of code
	- technologies to be used
	- other technical decisions to be made
- software design might be a written document or decisions that we're planning to adhere to 
- in the "design" and "no design" continuum there are infinite shades of grey such as a "partial design", "several conflicting designs in one piece of code", "almost complete design"

- proper software design decisions helps people decide:
	- what should the structure of the program code be
	- more important on fast program or program whose code is easy to read
	- which programming language to use
- doesn't cover stuff like:
	- structure of company
	- team meetings
	- working hours
	- performance measure of programmers

"Anything that involves the architecture of your software system or the tech- nical decisions you make while creating the system falls under the category of 'software design'."

- every programmer is a designer

......

lots of stuff about the history of stuff and why there aren't any set guidelines for writing software.

......

## chapter 3: driving forces of software design

- single purpose of all software: to help people. 

basic thought process: 

	- define speficic use cases for software
	- consider all the feature requests
		- how does this feature help solve the use case
		- ^ if it doesn't, srtike off the feature request
		- write out why the particular feature helps
	- ^ this helps resolve uncertainties about feature descriptions or how it should be implemented. 
	- ^ helps team come to an agreement about the value of a feature
	- ^ answering questions will help understand that some features are more important that others. 
	- ^ other stuff like looking at bugs and deciding how the particular bug hinder the purpose of the program. 


goal of software design

- write helpful software
- allow software to continue to be helpful
- design systems that can be created and maintained as easily as possible by their programmers - so that they continue to be helpful

## chapter 4: the future

##### equation of software design

D = V/E

where

	D = desirability of change / how much we want to do something
	V = value of change / how valuable is this change / how much does this help the users
	E = effort incolved in performing the change / how much work will the change require


...

...

value 

- how many users will this change be valuable to
- probability of value to user / how often will this feature be useful
- when it is valuable, how valuable will it be
- also consider "balance of harm": eg value of ads vs supporting yourself
- must release software for it to have value to users

effort

- every single piece of time connected with a change is part of effort cost

maintenance

- all changes require maintenance

...

...

- "In general, software systems are maintained for so long that the value now and the effort of implementation are guaranteed to become insignificant in almost all cases when compared to the long-term future value and effort of maintenance."

- "we want to avoid situations where, for a given change, the effort of maintenance will eventually outweigh the future value."

- "Any situation in which the effort of maintenance increases faster than the value is going to get you into trouble, even if it looks okay at first."

- "The ideal solution—and the only way to guarantee success—is to design your systems such that the effort of maintenance decreases over time, and eventually becomes zero (or as close to it as possible). As long as you can do that, it doesn’t matter how large or small the future value becomes; you don’t have to worry about it."

- **"It is more important to reduce the effort of maintenance than it is to reduce the effort of implementation."**

- **"The quality level of your design should be proportional to the length of future time in which your system will continue to help people."**

- **"You are safest if you don’t attempt to predict the future at all, and instead make all your design decisions based on immediately known present- time information."**

.......

.......

- come you your own conclusions about all the stuff the book talks about. 


## chapter 5: change

- the longer your program exists, the more probable it is that any piece of it will have to change. 
- you don't need to predict what will change, just know that things will change

... example of four programs and changes over time.

- don't write code until you actually need it, and remove any code that isn't being used. 


.....


##### incremental development and design

- designing and building a system piece by piece, in order



