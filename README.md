# SKIP BIN PERMIT APPLICATION REDESIGN

Welcome to the skip bin permit application redesign open source repository! Here you'll find:

* Useful information on the background of this project, the findings from research, and why the application was designed the way it has been.
* A flow diagram for the design
* [Sketch file](https://github.com/CodeforAustralia/com-skip-bins/blob/master/design/MVPV1-Permit-app-responsive-V1.4.sketch) 
* [The Mockup](https://github.com/CodeforAustralia/com-skip-bins/tree/master/docs)
* [The Code](https://github.com/CodeforAustralia/com-skip-bins/tree/master/code)
* [The Live Mockup](https://codeforaustralia.github.io/com-skip-bins/)

____


## USEFUL PROJECT INFORMATION

### INDEX

1. [Overview](#overview)
2. [What we did](#what-we-did)
3. [What we found](#what-we-found)
4. [Design flow](#design-flow)
4. [Tech](#Tech)

### OVERVIEW

Before this solution, skip bin companies had to fill out a lengthy online form in order to apply for a permit. they then had to wait 3-10 business days for their permit request to be reviewed, as the department, On-site Compliance Services (OCS), only had two permit officers who had other responsibilities. 

Upon review, it becamse clear that the process of approval could be automated, as all they really needed to check 

### WHAT WE DID

We did contextual inquiry, and user testing, as well as stakeholder interviews.

### WHAT WE FOUND

We found many things! 

First, skip bin companies need permits immediately. Not in 3- 10 days. Now. This is because customers only request a skip bin at the time they realise they need one, whihc is that day, or the next. Even if they were willing to wait, many things can happen that mean the bin doesn't end up being placed where they'd originally agreed - or at all. This would require skip bin companies to request permit refunds frequently, which nobody wants.

This makes it imperative that permits can be processed immediately.

### Design Flow
#### Application
![alt text](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/flow.jpg) 
#### OnBoarding 
![alt text](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/Onboarding.PNG) 
#### Dashboard
![alt text](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/Dashboard.PNG) 

### TECH

Aiming to develop as fast as we can under a open source license , we choosed Ruby on Rails as a base technology/Framework but not using the traditional Active Record (M(Model) layer in a  MVC project). We found MongoId that is officially (Object Document Mapper) supported by MongoDB and allow the model layer to be more flexible and on the other hand enhance the capability to use a Non Relational database (one of our goals) .

