TECHNOLOGY SWAP OUTS!

For this challenge, its all about working with an existing project and making technology changes. You will need to take the existing jQuery and replace it with Angular. jQuery needs to be completed remove. Nuke all the existing files, the code, and even npm uninstall! Then, bring in Angular! Note that are a couple obvious things we have not covered in Class. This was by design. One of the focuses here at the end of Tier 2 is to become dependent on documentation and research. We will not note what these points of research are, it is your responsibility to examine the project and discover all the points that need to be replaced, research the Angular implementation of the previous jQuery functionality,  and ensure that the functionality remains in tact. 

Existing Project: https://github.com/PrimeAcademy/prime_peer_db_pg_01

HARD MODE
Now that you have replaced jQuery for Angular, now replace SQL with MongoDB! You will obviously need a new database, no need to worry about data migration from SQL to MongoDB.

PRO MODE
Replace Express.js with Hapi.js (WAIT! What the heck is Hapi!? Something new, you will obviously need to do some research!)

# Prime Peer - Databases PG (SQL)

Hello everyone! Welcome to this 'challenge'.
In this one, you will not be writing any code (unless you want to), you will actually be learning from a build 
that already exists. You will be going through the code and the goal of this challenge, is to learn from the build.
Specifically, what I would like, is for you all to write down 'learnings' in bullet point format, of what you find
in this build that taught you something you did not no before. The objective is to tinker, understand, turn things
on and off, and whatever else you need to do to understand what the build is doing. Once again, the product of this
challenge should be a list of learned things.

Go ahead and copy this repo to your computer. Open it up in Webstorm.

Next, run 'npm install'.
Then, with postgres already running, run 'node server/database/database.js' in the command line. Take a close look
at what that file is doing, and see if you can make the connection of how this line is working.

Update:
Next, start up your server, open another terminal window.
Run this in that command line:
curl --data "text=test&complete=false" http://127.0.0.1:3000/api/todos

Fire up the app. Note that the app is not running on port 5000, find what port it is running on. Then play with the
application to get a sense of how its all working.

Write down what you and your pair learn from the activity.
