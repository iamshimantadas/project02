# project02
Open-source covid-19 management system

************************************************************************************************************************************************


Open-source covid-19 management system

project created and modified by , shimanta das.

Project features - 

1.visitors - 

a.visitors directly able to see the covid-19 report of india,states of india and all over world.
b.They able to raise request of admit to hospital/healthcare.

2.Patient’s - 

a.login/sign-up/logout themselves .
b.They able to upload daily free covid-19 test reports
c.Isolated patient’s able to upload their daily health condition report.

3.Admins - 

a.able to upload new covid report/status of india,india’s states and world.
b.He/She(doctor/nurse etc.) able to admit new bed for new patient if they may be covid positive or negative .
c.Admin able to upload free bed status(which was booked before) directly to server.
d.Admin able to view all admit patient’s bed status.
e.Admin able to see all type of “BOOKED” and “FREE” bed sttaus.
f.Admin able to see a perticular bed status - that ,who is currently on that bed right now , what’s the bed full condition. It’s will save a huge time for free-bed seekers.
g.Admin able to see all admit request’s which send by visitors .
h.Admin able to register new patient , find patient’s info by ID and also able to find patient’s full infomation using his/her primary-phone number and fullname(of patinet’s).
i.Admin also able to see daily free test’s reports and also sort report by date.
j.Also , able to see isolated patient’s reports - sort their report by their patient ID / Name or , even sort reports by date and along with able to view all isolation daily test reports .
k.all admited patient’s records will store into a separate table into the database.

* for secuiry perpose of admin-pannel , we have integrate login-logout system into admin pannel.

*************************************************************************************************************************************************
* Important files configuration - 

1. in every you will find a connection.php file , now there have 4 fields - host,user,pass,db ; now for local machine 
if you use windows or either linux or mac , 
the pass(denotes password of mysql/phpmyadmin) -> will be changed according to system configuration.
2. you will find 2nd file , covidreportDBconfig.php -> this file , configuration also need to done carefully ... ok :) 
3. admin pannel authentification - 
userid - admin
password - admin123

* setup & configure to our system - 
-> windows -  put all the files under C:\xampp\htdocs (xampp users only)
xampp : https://www.apachefriends.org/index.html
-> linux - /var/www/html -> put all the files .
or, xampp -> /opt/lampp/htdocs -> put all the files  [for xampp' users]
-> mac - find from youtube that how we can configure into mac as php coding files.

* for server-production deployment - 

paste all the file into /public_html directory and refresh the location in browser :) 


this code is lisenced under - GPL and GNU open-source lisence.
***********************************************************************************************************************************************
Thanks ,
Shimanta Das
