# introsde-2017-assignment-2-client
University of Trento

Introduction of Service Design Engineering 

2017 Fall

#### Name: Julia Hermann
#### Email: julia.hermann@studenti.unitn.it
#### Server code: https://github.com/julcsii/introsde-2017-assignment-2-server
#### Server base URL on Heroku: https://sde-assignment-2.herokuapp.com/

#### Task
The client sends HTTP requests to a RESTful server and logs the response to the standard output. The request that are implemented are listed here under Part 3: https://sites.google.com/a/unitn.it/introsde_2017-18/lab-sessions/assignments/assignment-2 

#### Code execution with Eclipse
1. Clone repository
2. Create new Java project referring the location where you put the source code
3. Add Ivy Library
4. Run execute.evaluation with Ant (this will run the ClientImplementationJSON.java and ClientImplementationXML.java classes and log the output to client-server-json.log and client-server-xml.log respectively.)

#### Notes
To fill the database of the server, the client has to run GET {base_url}/database_init (Request#0).