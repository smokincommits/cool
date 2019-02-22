Didn't know if I should go all out with this since you guys said simple in the instructs. 

Utilize the refresh button to make more calls to the random user API.  

1.) The purpose of this app is to display API information/rendering some data to the browser, the secondary purpose of this application is just to build social familiarity with random people with our friends at randomUser. 

2.) Do not embed API keys directly in code: API keys that are embedded in code can be accidentally exposed to the public, basically do not store API key files in your app's source tree.

3.) SELECT `properties`.`prop_id`, ( SELECT `address` FROM `addresses` WHERE `prop_id` = `properties`.`prop_id` ) AS `address` FROM `properties`;



4.) Some highlights of (i use docker) containerization: Cloud based deployment, docker-based containerization for micro-services, Micro-serv architecture and design, Container Orchestration.