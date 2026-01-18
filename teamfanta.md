<a id="top"></a>
# SDLC Analysis - Group Analysis 
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
* **Justification**: Management expects us to use and slightly modify the existing tools to generate deliverables. This model is less expensive with resources due to the reuse of given technology from the company.  
* **Other Models Considered**: <ins>Incremental development</ins>, specifically <ins>agile methods</ins> were considered since it’s a live web application with changes needed constantly. We ultimately rejected this model due to system degradation with additional increments.
* **Key Aspects**: 
  * Reuse and customization of existing software

[Back to top](#top)

<a id="dental-office"></a>
## 2. Dental office site
> Your good friend, a dentist, asks you to develop a web site for their new clinic. The web site should include common information about the clinic like hours, location, dental staff, and downloadable forms. At some point in the future, they would like to include an ability to make online appointments, send automated reminders via text messages, and issue discounts. Your friend is flexible with the time when you will deliver software. They also wish to continually add capabilities to the website in order to draw more patients to their clinic.

* **Model**: Incremental development
* **Justification**: Flexibility on delivery time with certain requirements being prioritized for the first iteration, which sounds like prototyping.
* **Other Models Considered**: <ins>The waterfall model</ins> since the request has clearly outlined requirements. We ultimately rejected this model because the requirements can be further added to or developed in the process. 
* **Key Aspects**: 
  * Open to incremental updates with prioritized requirements
  * Flexibility with deliverables

[Back to top](#top)

<a id="nuclear"></a>
## 3. Nuclear Power Plant
> You have been assigned to oversee the development of software that will monitor the status of a new nuclear power plant. You have a group of scientists who can provide you with domain knowledge to help you design the software.
> 
> Because of news of previous power plant failures, e.g., Three Mile Island and the more recent Fukushima-1 event in Japan, you want to make sure that the software you are designing will be robust, is able to deal with hardware failure, and can fail safely. The software is expected to last for a long time (at least 10 years).
>
> The utility company who owns the power plant allows you to subcontract parts of the software development, but you are ultimately responsible for the overall operation of the software.

* **Model**: Waterfall - Formal Development variant - B method
* **Justification**: With previous power plant failures in mind, this is a critical system where there is an abundant need for safety and security. Also, we are requested to subcontract parts of software development which can be clearly defined in the longer specification stage associated with the waterfall model. We chose B method-based formal development processes to simplify the production with safety and security in mind.
* **Other Models Considered**: The <ins>spiral model</ins> was considered to reduce the risks of the waterfall model due to its rigidity, but ultimately this isn’t a project where multiple prototypes can be developed and must be finalized. Failure would be catastrophic 👀
* **Key Aspects**: 
  * Safety and critical reliability requirements must be met prior to deployment
  * Larger scale project 

[Back to top](#top)

<a id="dot"></a>
## 4. Department of Transportation
> Your company won the contract to develop a distributed application which stores data on the Cloud. This is in response to a thorough 100 page specifications from the Department of Transportation. The specifications is very detailed in what’s expected from the application.
> 
> Your company has developed similar solutions in the transportation domain on numerous previous occasions, and you have the appropriate experienced staff for the project. You bid on the project to be completed within 18 months based on a team of 10 software engineers.

* **Model**: Spiral
* **Justification**: Requirements for this project are very well specified. The project must be completed *within* 18 months, leaving room for the project to be finished early should any iteration of the prototype be deemed sufficient.
* **Other Models Considered**: 
  * <ins>Integration</ins> - similar solutions were developed by the company and can be integrated to save time and reduce repetitive work. However, with integration, specifications may not be prioritized.
  * <ins>Incremental</ins> - large framework decisions can be made earlier in development however this project requires emphasis on the specifications for the final deliverable 
  * <ins>Waterfall</ins> - project is a response to a long list of specifications, with a set number of engineers to distribute the work across. 
* **Key Aspects**: 
  * One final product with multiple functional prototypes 
  * Detailed requirements/specifications for deliverable 

[Back to top](#top)

<a id="traffic"></a>
## 5. Reducing Traffic
> An experienced technology company hires you to manage a new project that incorporates distributed computing and networking with car tracking equipment. The equipment will be used to monitor individual cars (via GPS tracking devices) and general traffic (via sensors and cameras) in both surface streets and freeways. Transportation officials should also be able to provide real-time traffic updates on digital billboards along the roads.
>
> Your team has mainly created proprietary hardware/software solutions in the past. The team has substantial skills in using object-oriented C++ to develop embedded systems.

* **Model**: Waterfall
* **Justification**: This project has to be well thought through to include different teams and incorporate with the broader traffic network. It also requires the implementation of embedded systems, which are usually inflexible due to the hardware.
* **Other Models Considered**: 
  * <ins>Incremental</ins> - it sounds like the team will need feedback throughout development to apply previous systems. However, due to the complexity of this project, it may be unrealistic to push out the project in versions.
  * <ins>Integration and configuration</ins> - utilization of previous equipment and technology, however, this project is not centered on customization of previous software for development. 
* **Key Aspects**: 
  * Large system with broader engineering systems involved
  * Critical to maintain safety for people in traffic
  * Embedded systems

[Back to top](#top)

<a id="educational-game"></a>
## 6. Educational Game
> You lead a small experienced team of 7 developers from a gaming company. Your team is responsible for quickly developing educational games based on preliminary and evolving set of requirements. You have internal and external customers who expect to use your games ASAP for their own testing efforts. You have a team member who participates on educational conferences as well as acts a marketing representative to your customers, the teachers and administrators at your local school district.

* **Model**: Incremental
* **Justification**: This project requires an immediate release of the product as well as a flexible developing environment, allowing for new requirements to be implemented. By using the incremental process, the marketing team will also have something to advertise to customers with each iteration of development.
* **Other Models Considered**: <ins>Waterfall</ins> was considered for the security aspect, but ultimately it was not a good fit because game requirements and features will change after playtesting.
* **Key Aspects**: 
  * Evolving set of requirements
  * Small team working closely 
  * Quick turnaround for deliverable 


[Back to top](#top)

<a id="global-health"></a>
## 7. Global Health
> You and your friends won a multi-million dollar grant from a foundation to develop software to address current global challenges. Your startup company is also eligible to receive further grants if it can demonstrate significant positive impact on the health of the people residing in developing countries.
> 
> Your whole company currently only has 5 people. You will need to hire team members as part of the development effort. Your starting team consists of 2-3 developers who you know very well from previous projects.

* **Model**: Incremental - Agile Methods using Scrum and Stand-Ups
* **Justification**: Upon successful development, there will be additional resources provided for further development, meaning more prototypes and early subsets to be released. Also, the familiarity with the team and the project means less need for formal communication and development, which is characteristic of scrum methodology, common in agile development. Stand-ups will be expected.
* **Other Models Considered**: <ins>Waterfall</ins> was considered due to the expense of the project and the consideration of stakeholders in terms of the health of people residing in the countries the project is being implemented in. However, this project has changing requirements and potential for more acquired resources. 
* **Key Aspects**: 
  * Expansion
  * Informal communication
  * Changing Requirements (possibility of additional resources)

[Back to top](#top)