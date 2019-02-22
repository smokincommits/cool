1.) The purpose of this app is to display API information/rendering some data to the browser, the secondary purpose of this application is just to entertain a little bit with help from my friends at giphy.

2.) Do not embed API keys directly in code: API keys that are embedded in code can be accidentally exposed to the public, basically do not store API key files in your app's source tree.

3.) SELECT `properties`.`prop_id`, `adresses`.`adress`, ( SELECT * FROM `adresses` WHERE `prop_id` = `properties`.`prop_id` ) AS `adress` FROM `properties`



4.) Some highlights of (i use docker) containerization: Cloud based deployment, docker-based containerization for micro-services, Micro-serv architecture and design, Container Orchestration.