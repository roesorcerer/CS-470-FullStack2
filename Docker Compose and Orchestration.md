**2-3 Assignment: Docker Compose and Orchestration**<br>
*Rowan Stratton*<br>
*Southern New Hampshire University*<br>
*CS-470-R1926 Full Stack Development II 23EW1*<br>
*Professor Nizar Dajani*<br>
*September 16, 2023*<br><br>

**Screenshots:**<br><br>
Network create – trying to solve port issues as port 27017 was in use already. <br><br>
 ![Screenshot 1](screenshots/networkCreate.png)<br><br>
Changed file to look for additional port if 27017 is in use. <br>
 ![Screenshot 1](screenshots/port.png)<br><br>
Next issue I had was with the naming of the database. Mine was called mongo, not my-mongo. It took me a long time to figure out how to reflect these changes but I changed my config.json and datasources.json file:<br> 
 ![Screenshot 1](screenshots/issue.png)<br>
 ![Screenshot 1](screenshots/hostName.png)<br><br>
Finally I had to make these changes to my docker-compose.yml file: <br>
 ![Screenshot 1](screenshots/ymlFile.png)<br>
 ![Screenshot 1](screenshots/dockerCompose.png)<br>
 ![Screenshot 1](screenshots/dataSources.png)<br><br>
Docker Containers: <br>
 ![Screenshot 1](screenshots/dockerContainers.png)<br>
 ![Screenshot 1](screenshots/lafs-db.png)<br><br>
Testing containers:<br>
![Screenshot 1](screenshots/containerTest.png)<br><br>
 
http://localhost:3000/explorer<br><br>
 ![Screenshot 1](screenshots/apiLoopbackExplorer.png)<br>
Testing REST API: <br>
 ![Screenshot 1](screenshots/testingRESTAPI.png)<br>
 ![Screenshot 1](screenshots/lafs-dbtest.png)<br>
 ![Screenshot 1](screenshots/dockerComposeUP.png)<br>
 ![Screenshot 1](screenshots/localHost.png)<br>
 ![Screenshot 1](screenshots/dbConnected.png)<br>
 ![Screenshot 1](screenshots/dockerps.png)<br>
 
 
 
 
 

