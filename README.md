# Blog-Website

This website helps you to prepare your daily blogs easily having simple and easy to use interface. You can  create a new blog by adding */compose* in url and now you fill Title and content of the new blog that you want to post on the website.you can even delete the posted blogs on the website if you want. The new blog will also be added on the home page but in only 100 characters and it has a link **Readmore** on clicking it you go to that particular blog only using specific **ID** of all the blogs created. The blogs are stored in a database using mongodb. So,whatever you add will be inserted in the database and remain there unless you delete it manually or pressing the delete it! button.After deleting that blog post will be removed from the database. This website is also hosted on world wide web using the **Heroku** app. So, anyone from any part of the world can access this website. And the database is also hosted on**mongoDB-Atlas**. So, 24*7 database of this website is hosted on world wide web. And anyone can easily write blogs anytime or anywhere.

---

### My website Link : i.e using Heroku app

[Blog-Website](https://shielded-island-25501.herokuapp.com/ "Visit website")

---

### Major Features Used
* EJS Templates
  * EJS(Embedded JavaScript) Templates are used.As EJS templates contains a basic code that we want in every web pages.And file which contains an extension *.ejs* will be a base template for creating all other html files.

* Layouts are used. Which are added to all pages easily.Example : *header.ejs* & *footer.ejs*.

* Express routing parameters are used.With the help of this we can tap to different webpages on the go easily instead of making get request for all pages.


* mongodb(NoSql) database is used.
  * Mongoose is one of the package of the mongodb.It allows node.js to be able to connect and talk with the mongodb database.Main objective of this mongoose is to simply writing of validation codes , shorter and easier to work with.

* Heroku is used.

   * we hosted our website on heroku and with the help of this now anyone around the world can access it. Heroku host our node.js server to keep our website live on the internet 24*7.

* mongoDB-Atlas is used

  * It hosts our mongodb database and serve up the data all time i.e 24*7 whenever needed.

  * So, node.js app on heroku will be able to make necessary request to our database(that is hosted on mongodbAtlas) and can be able to perform all **CRUD** operations.

---


### Running The Project


* you can use fork to get my repository directly on your github account.

* you can clone it to your local repository as well and then upload on it github.

*after doing this*

1. software requirements
  ```
  mongodb
  Ejs
 ```


2. open your command prompt/Terminal.

3. Go to directory in which project files are present.

4.Run command .
 ```bash
 npm install 
 or
 npm i
 ```
this will install all the project dependencies required in your pc.

5. After completion of installation , Run command:

```bash
nodemon app.js
or
node app.js
```

6. cmd or terminal should display 

```bash
server started on port 3000 
```
means everything is running good and project has been sucsefully built and running.

7. open web browser and visit :

```bash
localhost:3000
```

8. On running the project once a database **blogDB** database is created in the mongodb database and inside this db a collection **posts** is also created. you can manually using mongodb queries can perform **CRUD** operation on the data stored in a collection called posts. You can delete a specific blog or many more things.
 

9. In your command prompt/ Terminal. Type:
```bash
mongo
```
This will create a mongo shell where you can write all mongodb queries.

10. To view all databases lists


```bash
show dbs
```

11. To use the databas

```bash
use database_name
```

12. To view all collections in a particular database.

```bash
show collections
```

13. Now you can perform all CRUD operations on a particular collection you want.

---

### Thank you

