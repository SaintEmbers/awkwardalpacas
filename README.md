![lunchcorgi](/client/assets/lunchcorgi.jpg)

# awkwardalpacas
 ## Stack ##
 > Mongo, Express, Angular, Node - 
 - NOTE -
 We are not actually using Mongoose, however there are some legacy methods in the project which do use Mongoose so the references and requires are still in there.
 
 ## DB ##
 > Stores Users, Events. Users have an id, name, password, eventids from events document. Events have an id, description, location, userid from users document, list of userids of people who have joined.
 
 To get started with the database, there must be at least one user and one event.  Start by using the "Sign Up" to add one user then create one or more events. 
 
 ## Views ##
 > Sign up, sign in, events view
