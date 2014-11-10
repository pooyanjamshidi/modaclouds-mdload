modaclouds-mdload
=================
MDload is a model-driven workload generation tool that automatically generates requests to a web application by simulating a set of users. 
MDload is a general-purpose tool as it can be configured to generate traffic for specific applications. 
This is achieved by implementing a set of routines that generate and submit the application requests, 
but allowing the user to define the specific requests to submit and their order. 
This therefore simplifies the testing of web application, since it is only necessary to define how the user interacts with the application. 

Once the user behavior has been specified, MDload emulates a set of users by relying 
on Selenium (http://docs.seleniumhq.org/) to automate a Firefox web browser that sequentially submits requests to the application server. MDload is able to generate bursty traffic, dynamically changing the traffic mix, that is, the proportion of requests types generated by the users. This behavior better represents the actual workload faced by the application. 

**Installation instructions** and **user guide** can be downloaded [here](https://github.com/imperial-modaclouds/modaclouds-mdload/blob/master/doc/MDload_doc.pdf?raw=true). 
If this link does not work, go to https://github.com/imperial-modaclouds/modaclouds-mdload/tree/master/doc, 
click on MDload_doc.pdf, and then on View Raw. 

*Support*
This tool has been developed and tested on equipment supported by the MODAClouds project, 
by an ESPRC small grant, and by an Amazon AWS research grant. 
