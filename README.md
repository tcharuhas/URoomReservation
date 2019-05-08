# URoomReservation
 
Currently there is no system in place to reserve classrooms, that a lot of people frequent, in a building called Alter Hall @ Xavier University

<h2><a href="https://www.loom.com/share/0d1fad5c4395491a981831c01n91f859d">Live Demo</a></h2> 
<br />
<h3>Live Demo Steps</h3><br />
1. Steps through Okta (See below) <br />
2. Steps through the reservation process <br />
3. Steps through the admin panel <br />

<h2>How to Run:</h2><br />
<h3>Frontend</h3><br />
1.Inside of the frontend/group2-frontend-latest folder, run:<br />
&nbsp;&nbsp;&nbsp;1.ng update<br />
&nbsp;&nbsp;&nbsp;2.npm install<br />
&nbsp;&nbsp;&nbsp;3.ng serve --proxy-config proxy.conf.json<br />

<h3>Backend</h3><br />
1.Inside of the backend/crud folder, run:<br />
&nbsp;&nbsp;&nbsp;1.mvn clean install<br />
&nbsp;&nbsp;&nbsp;2../mvnw spring-boot:run<br />
&nbsp;&nbsp;&nbsp;3.Populate the database<br />

<h2>Okta Security</h2><br />
In this project, a cloud authentication API was implemented to control our users and secure the website.  More can be read about Okta <a href = "https://www.okta.com/">here</a> <br />

<h2>To Do</h2><br />
-To either implement a MySQL database or populate the schema file with values <br />
-Make methods more efficient <br />
-Come up with more efficient database structure <br />
-Touch up design
