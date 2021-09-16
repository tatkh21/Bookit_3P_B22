#Three Point Verification

* We are creating our Cucumber framework from scratch

##For Cuumber Framework
* pom.xml: Cucumber-java, cucumber-junit
* Creating classes: CukesRunner (features, glue)

###Utilities: Driver, Conf.Reader
* In oder for them to work we needed selenium-java and bonigarcia webdriver manager dependencies

##UI Part
###Connection: 
- selenium, webdrivermanager
- create configuration.properties
  Create our scenario and get the info from UI
  we added HOOKs, it is for before and after methods (maximize, close, screenshot)

##API part
* test it manually, we looked at our swagger document; in order to do any API request
we need bearer token, first request is always for token, then get user info
automation:add dependency; restassured library
* https://cybertek-reservation-api-qa3.herokuapp.com   api url
* Go to swegger document to understand the API
* https://cybertek-reservation-api-docs.herokuapp.com/#introduction

##DataBase
* Manually test: SQL developer, write query to see the data
* automation: pom.xml--- type of database
* DBUtils: it provides connection and also useful methods
* in conf.properties: we need to provide database url and user info
* Hooks class you need to put "@db"

#BootCamp for B22 Full Review Notes
https://motley-walkover-208.notion.site/SQL-JDBC-API-B22-Boot-Camp-ed22709e0984412d815fc06f6122fa4e