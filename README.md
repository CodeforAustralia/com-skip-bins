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

As the OCS felt that this delay in review was on them, (and because skip bin companies pay upon application) they were allowing skip bin companies to back-date permits to date of application. This however was not in alignment with Local Laws, and the officers who enforce them. This resulted in skip bin companies frequently being fined. It also resulted in arguments between all parties.

It became clear that the process of approval could be automated - and a wealth of other solutions became clear - so we created a roadmap of solutions, and broke it up into MVPs that could be rolled out.

### WHAT WE DID

The project started with a partnership with Cogent, to clarify what we should be doing. This entailed rapid research with stakeholders and users, then ideation and development of an MVP roadmap.

After we agreed on the roadmap, the Code for Australia team established an MVP that could be delivered first. This is what is included in this repository.  

### WHAT WE FOUND

We found many things! 

First, skip bin companies need permits immediately. Not in 3- 10 days. Now. This is because customers only request a skip bin at the time they realise they need one, whihc is that day, or the next. Even if they were willing to wait, many things can happen that mean the bin doesn't end up being placed where they'd originally agreed - or at all. This would require skip bin companies to request permit refunds frequently, which nobody wants.

This makes it imperative that permits can be processed immediately.

### THE RESULT

<strong> MVP version 1: </strong> Just apply. That's it. We manually upload skip bin information, and generate an account for each company and send the details to them. After that, they just log in, apply, and pay. No need for policy changes or anything else. If the company wants to change their information e.g. their public liability, they need to contact OCS.

![Image showing the design flow, from login, to application, to payment, and successful payment. It also includes the menu and how you review your business information and log out.](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/flow.jpg) 

<strong> MVP v2: </strong> Make it possible for skip bin companies to register and change their information themselves.

![alt text](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/Onboarding.PNG) 


#### The following came out teh clarification session we did with Cogent, and still needs further evolution:

<strong> MVP 3: </strong> Deliver the other useful aspects like how you manage your permits, and quickly re-apply

![alt text](https://github.com/CodeforAustralia/com-skip-bins/blob/master/imgs/Dashboard.PNG) 

### TECH

Aiming to develop as fast as we can under a open source license , we chose Ruby on Rails as a base technology/Framework but not using the traditional Active Record (M(Model) layer in a  MVC project). We found MongoId that is officially (Object Document Mapper) supported by MongoDB and allow the model layer to be more flexible and on the other hand enhance the capability to use a Non Relational database (one of our goals) .

