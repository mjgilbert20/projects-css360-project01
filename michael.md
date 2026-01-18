<a id="top"></a>
# SDLC Analysis - Michael
For each of the following project proposals, a software development lifecycle (SDLC) model must be chosen with justification for this decision:
1. [New e-Commerce site](#e-commerce)
2. [Dental office site](#dental-office)
3. [Nuclear Power Plant](#nuclear)
4. [Department of Transportation](#dot)
5. [Reducing Traffic](#traffic)
6. [Educational Game](#educational-game)
7. [Global Health](#global-health)

<a id="e-commerce"></a>
## 1. New e-Commerce site
> PerfectApparel wants to launch a new e-Commerce site to sell clothes, shoes, and accessories. The company wants to provide an online shopping experience that will attract customers to come back to the site. For example, customers may select their own colors, create their customized design, and quickly find matching outfits.
>
> Today, PerfectApparel mainly uses in-house templates with its own custom scripting and extensions to create web sites. An interpreter written in Java reads the templates and scripting and generates the appropriate web page based on a customer’s request. Your management expects you to use same tools with minor modifications to generate HTML5 pages and extensions needed for the new features.
>
> Your team consists of a combination of developers from your previous projects, new hires, and interns. You will need to define requirements for any template or scripting extensions that you want and schedule their development with a separate group that develops the Java interpreter and related software.

* **Model**: Integration and configuration
* **Justification**: The project uses previously existing in-house templates. Management expects us to use these with customized modifications to complete the project. 

[Back to top](#top)

<a id="dental-office"></a>
## 2. Dental office site
> Your good friend, a dentist, asks you to develop a web site for their new clinic. The web site should include common information about the clinic like hours, location, dental staff, and downloadable forms. At some point in the future, they would like to include an ability to make online appointments, send automated reminders via text messages, and issue discounts. Your friend is flexible with the time when you will deliver software. They also wish to continually add capabilities to the website in order to draw more patients to their clinic.

* **Model**: Incremental
* **Justification**: The flexible delivery date of this project lends itself to be ideal for incremental development. The requirements are expected to change after the initial specifications are successfully implemented, and delivery is expected in stages, or prototypes. (Spiral may be a better option, not sure if that would be the correct categorization)

[Back to top](#top)

<a id="nuclear"></a>
## 3. Nuclear Power Plant
> You have been assigned to oversee the development of software that will monitor the status of a new nuclear power plant. You have a group of scientists who can provide you with domain knowledge to help you design the software.
> 
> Because of news of previous power plant failures, e.g., Three Mile Island and the more recent Fukushima-1 event in Japan, you want to make sure that the software you are designing will be robust, is able to deal with hardware failure, and can fail safely. The software is expected to last for a long time (at least 10 years).
>
> The utility company who owns the power plant allows you to subcontract parts of the software development, but you are ultimately responsible for the overall operation of the software.

* **Model**: Waterfall
* **Justification**: This project has a strict set of requirements for the system that is meant to last for a long time. The project is also safety critical and leaves little to no room for error. There is a group of scientists designated for designing the software, which leads me to believe that is the phase where a lot of time/resources will be spent.

[Back to top](#top)

<a id="dot"></a>
## 4. Department of Transportation
> Your company won the contract to develop a distributed application which stores data on the Cloud. This is in response to a thorough 100 page specifications from the Department of Transportation. The specifications is very detailed in what’s expected from the application.
> 
> Your company has developed similar solutions in the transportation domain on numerous previous occasions, and you have the appropriate experienced staff for the project. You bid on the project to be completed within 18 months based on a team of 10 software engineers.

* **Model**: Incremental
* **Justification**: This is a distributed application with data stored on the cloud - updates are meant to be made rapidly for live deployment. The delivery is expected a relatively constrained timeframe with a specific set of engineers, so speed and efficiency of development will be important.

[Back to top](#top)

<a id="traffic"></a>
## 5. Reducing Traffic
> An experienced technology company hires you to manage a new project that incorporates distributed computing and networking with car tracking equipment. The equipment will be used to monitor individual cars (via GPS tracking devices) and general traffic (via sensors and cameras) in both surface streets and freeways. Transportation officials should also be able to provide real-time traffic updates on digital billboards along the roads.
>
> Your team has mainly created proprietary hardware/software solutions in the past. The team has substantially skills in using object-oriented C++ to develop embedded systems.

* **Model**: Waterfall
* **Justification**: The project works with embedded devices that will be difficult to update once deployed. This is also safety critical as it will directly affect the conditions for drivers in traffic and their safety on the road.

[Back to top](#top)

<a id="educational-game"></a>
## 6. Educational Game
> You lead a small experienced team of 7 developers from a gaming company. Your team is responsible for quickly developing educational games based on preliminary and evolving set of requirements. You have internal and external customers who expect to use your games ASAP for their own testing efforts. You have a team member who participates on educational conferences as well as acts a marketing representative to your customers, the teachers and administrators at your local school district.

* **Model**: Incremental
* **Justification**: Development for this project must be quick, with customers expecting to use the final project ASAP for testing. Deployment will most likely need to be online for near-instant availability. Having a team member who interacts directly with stakeholders makes me think there will be scrum meetings/standups where the group is, to some degree, informed of each developer's progress.

[Back to top](#top)

<a id="global-health"></a>
## 7. Global Health
> You and your friends won a multi-million dollar grant from a foundation to develop software to address current global challenges. Your startup company is also eligible to receive further grants if it can demonstrate significant positive impact on the health of the people residing in developing countries.
> 
> Your whole company currently only has 5 people. You will need to hire team members as part of the development effort. Your starting team consists of 2-3 developers who you know very well from previous projects.

* **Model**: Incremental
* **Justification**: Since we know the starting team very well and will need to hire more team members, we should incorporate an informal meeting cadence, like standups, to get everyone comfortable with working together and on the same page. Our company has the potential for further funding, and thus further requirements/updates, should we successfully meet the impact goals laid out by the foundation.

[Back to top](#top)
