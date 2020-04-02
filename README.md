Part 1:
1.	What folder contains the models? 
-	The models folder
2.	How many models are there?
-	There are 4 models
3.	 What are they named?
-	author, book, bookinstance, and genre.
4.	 Inspect them - how are they the same?
-	They all use a Schema
5.	 How are they different?
-	They each use different schema functions
6.	What folder contains the controllers? 
-	Controllers folder
7.	How many are there? 
-	There are 4 controllers
8.	What are they named?
-	authorController, bookController, bookinstanceController, and genreController
9.	 Inspect them - how are they the same?
-	Ability to create, get, and update, and delete items
10.	 How are they different?
-	They use different variables
11.	What folder contains the views?
-	Views folder
12.	 How many are there?
-	There are 19 files in the view folder
13.	 What are they named?
-	Author_delete, author_detail, author_form, author_list, book_delete, book_detail, book_form, book_list, bookinstance_delete, bookinstance_detail, bookinstance_form, bookinstance_list, error, genre_delete, genre_detail, genre_form, genre_list, index, and layout
14.	 Inspect them - how are they the same? 
-	They are have the pug extension. All but layout extends to the layout.pug
15.	How are they different?
-	They do CRUD and error functions on different parts 
16.	How many views for each model? 
-	There are 4 views for each model
Inspect the package.json file. 
17.	What free code libraries (dependencies) are used?
-	Async, compression, cookie-parser, debug, express, express-validator, helmet, http-errors, moment, mongoose, morgan, pug and nodemon
18.	 What is the version of each dependency? 
-	2.6.2, 1.7.3, 1.4.3, 2.6.9, 4.16.0, 5.3.1, 3.15.1, 1.6.2, 2.24.0, 5.4.13, 1.9.0, 2.0.0-beta11, 1.18.10
19.	There is one dependency that is only used during development - which one is it? 
-	Nodemon
20.	Look  up nodemon - what is it & why is it useful during development?
-	Nodemon is a utility that will monitor for any changes in the source code and with restart the server.
Look at the scripts in package.json.
21.	When we run 'npm start' what command is run?
-	Node ./bin/www
22.	 In what folder and file does execution begin? 
-	The code with start it a scripts object is given unless there is none then it will run node server.js
23.	When we run 'npm devstart' what command is run?
-	It starts the ./bin/www file but instead in node it starts in nodemon
24.	 In what folder and file does execution begin?
-	The code with start it a scripts object is given unless there is none then it will run node server.js
Find the app.js file in the project root folder. Open and inspect this file to see how we configure our Express app.
25.	What do the require statements do?
-	The require() statement is the entry point
26.	Can you find each of these dependencies in package.json? 
-	Yes
We use app.set() to set up key-value pairs for our app. 
27.	How many key-value pairs do we set?
-	Two key-value pairs
28.	 What are the lines of code where we call app.set()?
-	The app.use() files
We use app.use() to set up our middleware. Middleware allows us to perform common logic in a single place. 
29.	How many times do we call app.use()? 
-	12 times
30.	What are the associated line numbers?  
-	31-36, 38, 40-42, 45 and 50
31.	Can you guess/figure out/ look up what each of these app.use() methods is doing? 
-	They are logging, connecting, parsing, compressing, and directing. 
32.	Scroll down to see the ER diagram for the application. How many entities are there? 
-	There are 4 entities
33.	How do the names of these entities compare to the model names?
-	The names of these entities match the model names
34.	 How are the attributes reflected in the corresponding model file?
-	They are schema variables.
Part 2:
1.	What command does npm start run? (Hint: see package.json scripts).
-	DEBUG=express-locallibrary-tutorial:* npm run devstart
2.	Open a browser to localhost:PORT where PORT is the port you found in www. 
-	3000
3.	Did your app run successfully? What is the URL?  What did you see?
-	Yes. URL is localhost:3000. It says:  Express Welcome to Express.
4.	How big is node_modules? What's in it? When you run npm install, this is where the dependencies go. 
-	Node_modules is very big. There is everything from cookie parser, debugger, and doctypes. 
