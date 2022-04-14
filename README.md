# Covid-19 management system


************************************************************************************************************************************************

Project features -
1. Visitors -

a. visitors directly able to see the covid-19 report of india,states of india and all over world.

b. They able to raise request of admit to hospital/healthcare.

2. Patient’s -

a. They able to register themselves .

b. login /logout themselves.

d. They can upload daily covid free test’s reports and isolation reports.

e. They can find their full information, reset password quickly , delete their their account . 

3. Admin -

a. Admin able to upload new covid report/status of india,india’s states and world.

b Admin able to upload free bed status(which was booked before) and also generate patient’s 
total bill .

c. Admin able to view all admit patient’s bed status and able to see all type of “BOOKED” and 
“FREE” bed status .

d. Admin able to see a particular bed status - that ,who is currently on that bed right now , 
what’s the bed full condition. It’s will save a huge time for free-bed seekers.

e. Admin able to see all admit request’s which send by visitors .

f. Admin also able to see daily free test’s reports and also sort report by date.

g. Also , able to see isolated patient’s reports - sort their report by their patient ID / Name or , 
even sort reports by date and along with able to view all isolation daily test reports .

h. admin able to update cost of current using this project healthcare/hospital(ex. Per day livingcost,iccu or other ward cost separately).

i. admin also add new admins and logout itself.

* For security purpose of admin-panel, we have integrated login-logout system into admin 
panel.

* All admitted patient’s records will store into a separate table into the database.

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
