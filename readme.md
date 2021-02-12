# Prerequisite Stuff
   
   -> NodeJs
   -> Npm
   -> MongoDb



# Installation
  
   $->   mkdir <-Your Project Name->
   $->   cd <-Your Project Name->
   $->   npm init

 We need to install necessary modules: express, mongoose, body-parser and cors.
 Run the command:  

   $->   npm install express --save
   $->   npm install mongoose --save
   $->   npm install body-parser --save
   $->   npm install cors --save

 All together $-> npm install express mongoose body-parser cors --save      




That's it !


# APis

Methods	Urls	                     Actions
GET	    api/tutorials	             get all Tutorials
GET	    api/tutorials/:id	         get Tutorial by id
POST	api/tutorials	             add new Tutorial
PUT	    api/tutorials/:id	         update Tutorial by id
DELETE	api/tutorials/:id	         remove Tutorial by id
DELETE	api/tutorials	             remove all Tutorials
GET	    api/tutorials/published	     find all published Tutorials
GET	    api/tutorials?title=[kw]	 find all Tutorials which title contains 'kw'

