# E Commerce

## Bootcamp: Challenge 13 - Create app to generate a database to view, add, modify categories, products and tags

The purpose of this assignment, is to create a working CLI app for a user to create an e-commerce database, with tables for products, categories and tags

- Motivation: Test what has been learned through practical application and testing of Mysql, Javascript, CLI, OOP, TDD, Node and Node modules including "inquirer", with an emphasis on using "sequelize" to build a database.

- Project: Create an app to create a Ecommerce database from CLI.  The user will be able to view and add categories, products and tags.

- Problem Solved: Once the app is started from the CLI, and the database initialized, in Insomnia, the user can select api/categories products or tags, and view, create, update or deleted this data from the database.

- Lessons Learned: Creating datbases notches up the level of complexity learned.  Correctly flowing the data from the databases, in conjunction with bringing in questions using inquirer has been challenging.  I've updated the app, and fixed the ability to POST and DELETE tags, products and categories.

## Folders and Files

- README.md:  Explains usage and functionality of this app

- /db: Contains info related to the database and tables definitions
 
- /models: Folder where tables are defined, and associations between the data in the databases are created
- gitignore: Contains files names that are not passed to Github for usage with the app

- /routes - Routes for categories, products and tags

- /seeds - Preformatted data that "seeds" the databases for testing

- package-lock.json: Package of Node modules, including "inquirer"

- package.json:  Node module file

- server.js: This is where the app begins.  It calls questionsStart.js, where he user decides which action to take.  The response is returned to app.js, where the response is handled using switch/case, to call the specific function related to the response from the queries.js file.


## How to use this app (it is suggested to have 2 separate command line windows, as well as run an app like Insomnia)

- Mysql - User needs to connect to the database in the "db/schema.sql" file, and select "ecommerce_db" as the database.  Then run the command "source db/schema.sql", then "use ecommerce_db".  This will activate the database

- Command Line - Run the command "npm run seed", which load the data base with data for testing.  
![npm run seed](https://github.com/RauchDavis13/fantastic_umbrella/blob/main/images/Challenge%2013%20-%20npm%20run%20seed.png)
The command line interface should show that the databases were loaded successfully. 

- ***Mysql*** - Run 'source db/sql.com' to activiate the tabe for the database

- ***Run App*** - Run the command "npm start", and this will initialize the routing connection from the database to the front end

## Screen Shots
***GET's***<br>
GET Category
![GET Category](/images/GET_categories.png)

GET Products
![GET Category](/images/GET_products.png)

GET Tags
![GET Tags](/images/GET_tags.png)

***POST's***<br>
POST Category
![POST Category](/images/POST_categories.png)
![POST Category full list](/images/POST_cagegories_with_new_category.png)

POST Product
![POST Product](/images/POST_product.png)
![POST Product full list](/images/POST_product_POST.png)

POST Tag
![POST Tag](/images/POST_tags.png)
![POST Tag full list](/images/POST_tags_showing_new_tag.png)

***DELETE's***<br>

DELETE Category
![DELETE Category](/images/DELETE_categories_PRE.png)
![DELETE Category post delete](/images/DELETE_categories_POST.png)

DELETE Product
![DELETE Product](/images/DELETE_products_PRE.png)
![DELETE Product post delete](/images/DELETE_product_POST.png)

DELETE Tag
![DELETE Tag](/images/DELETE_tag_PRE.png)
![DELETE Tag post delete](/images/DELETE_tag_POST1.png)

## GitHub repository...
https://github.com/RauchDavis13/fantastic_umbrella.git

## Videos
Initialize DATABASE
https://drive.google.com/file/d/1Vebgn8RbV9w3Z59k48eMFE33Xs-CbL99/view

Initialize SERVER
https://drive.google.com/file/d/11s412rRAZAGlKh25NO8sb4pcsrnmOtVg/view

GET Categories
https://drive.google.com/file/d/11s412rRAZAGlKh25NO8sb4pcsrnmOtVg/view

POST Categories
https://drive.google.com/file/d/16GQzEf3dDuZXIGjf_6zPQItFx8xsToyI/view

DELETE Categories
https://drive.google.com/file/d/1w82G2_mqMfpbVg7qg2eY_iuknZ2rqDsB/view

GET Products
https://drive.google.com/file/d/1SFnaBC_rvMmYO-gkIb0FraCp9Na_m3cG/view

POST Product
https://drive.google.com/file/d/1QT6Zb-qg8AOHugioJkYweagOybs6nEZh/view

DELETE Product
https://drive.google.com/file/d/18OQGVK4vmpYXpKaum1wOo_1SxZ_UbJbQ/view

GET Tag
https://drive.google.com/file/d/1fLtLDmhAGpPrdcEnZgMxRqJBNpYtWLni/view

POST Tag
https://drive.google.com/file/d/1cLbLRwnUtNfvhVU_DmLjHLGA8Zo57rQV/view

DELETE Tag
https://drive.google.com/file/d/1oatNcKSx5PymVdA3LcYUw8LH155miQCg/view







## Thank you's
Matthew Kim(Instructor)
Valeria Flores(TA)
Dustin Erwin (TA)
Kris Renaldi (TA)
Sandra Smith (Tutor)



