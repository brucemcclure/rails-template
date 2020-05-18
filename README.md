# "Hugs" Market Place

Link to the deployed app: www.myapp.com  
Link to github repo: https://github.com/evey-pea/hugs.git 

## Section 1: Requirement checklist 

Each time you have completed a requirement check it off the list. This way it will be easy for the educators as well as yourselves to track your progress.

- [x] 1. Create your app using Ruby on Rails.
- [x] 2. Use Postgresql database in development and production.
- [x] 3. My app has authentication (eg. Devise).
- [ ] 4. My app has authorisation (i.e. users have restrictions on what they can see and edit).
- [ ] 5. My app has some type of file (eg. images) uploading capability.
- [ ] 6. My app is deployed to Heroku (recommended) or AWS.
- [ ] 7. I have identified the problem I am trying to solve by building this particular marketplace app.
- [ ] 8. I have explained why is it a problem that needs solving.
- [ ] 9. I have provided a link (URL) to my deployed app (i.e. website)
- [ ] 10. I have provided a link to my GitHub repository (repo). I have ensured the repo is accessible by my Educators.
- [ ] 11. I have a complete description of my marketplace app (website), including:  
        - 11.1 Purpose  
        - 11.2 Functionality / features  
        - 11.3 Sitemap  
        - 11.4 Screenshots  
        - 11.5 Target audience  
        - 11.6 Tech stack (e.g. html, css, deployment platform, etc)  

- [ ] 12. I have provided user stories for my app
- [ ] 13. I have provided Wire-Frames for my app 
- [ ] 14. I have provided an ERD for my app
- [ ] 15. I have explained the different high-level components (abstractions) in my app
- [ ] 16. I have listed and described any third party services that your app will use
- [ ] 17. I have described my projects models in terms of the relationships (active record associations) they have with each other.
- [ ] 18. I have discussed the database relations to be implemented in my application
- [ ] 19. I have provided my database schema design
- [ ] 20. I have described the way tasks are allocated and tracked in my project

NB Slide/Presentation specific requirements

- [ ] 21. An outline of the problem I solved by building this particular marketplace app, and why it’s a problem that needs solving.
- [ ] 22. A well planned walkthrough of my app
- [ ] 23. I have practived my presentation at least once and it is 5-6 minutes long

### Rubric Criteria

## Section 2: Documentation

##### 1. Explain the different high-level components (abstractions) in your App

The high level components required for this app are:

- **User authentication and authorisation** to ensure that users control only their own information *as a user profile* in a reasonably secure manner
  - User Account management through the gem Devise
  - CRUD operations for user profile content  
      -  Data fields
      -  Visibility of profile to other users
      -  'Blocking' unwanted users
- **Storing an image component** for each user (profile pictures, user gallery)
- **Searching, sorting and/or filtering capability** based on user profile data and geocoding services. This will enable users find other suitable users within a given physical range
- **Internal messaging system** to allow users to interact with each other

##### 2. List and describe any 3rd party services

###### Image content storage: Amazon S3 Bucket

[TODO]

###### Geocoding Services: Google Maps API

[TODO]

##### 3.1. Identify the problem you’re trying to solve by building this particular marketplace App

The purpose of the hugs marketplace is to enable people who would like a hug to find other people in their area to hug them.

##### 3.2 Why is the problem identified a problem that needs solving?

Whilst there are a large quantity of online marketplaces for human contact, these are mostly based around contact of a sexual nature. There are few online options for those seeking a consensual yet non-sexually motivated hug.

As the project is being prepared during various quarantine levels due to COVID-19 crisis, there  currently is a large number of people who will be somewhat starved of human physical contact.

The constraints to this problem are largely localisation based profile matching, as prior to meeting for a hug, the persons need to be suitable for each other and within a reasonable proximity to each other.

This is a problem that will provide a unique marketplace opportunity for this to be addressed with a web application.

##### 4. Describe your project’s models in terms of the relationships (active record associations) they have with each other

* Complete discussion of the project’s models with an understanding of how its active record associations function

##### 5. Discuss the database relations to be implemented

![This is an image of your ERD](This is the relative path to it)

* Provides coherent discussion of the database relations, with reference to the ERD


##### 6. Provide your database schema design

* Flawless, complex, complete, and well thought through ERDs provided

##### 7. Provide User stories for your App

![This is an image of your user stories](This is the relative path to it)

* You also just use normal markdown to describe them
* User stories are well thought out, relevant, and comprehensively cover the needs of the app

##### 8. Provide Wireframes for your App

![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  

* More than five detailed and well designed wireframes provided, for several different screen sizes (as required for the app)

##### 9. Describe the way tasks are planned and tracked in your project

![This is an image of your task planning](This is the relative path to it)
![This is an image of your task planning](This is the relative path to it)
![This is an image of your task planning](This is the relative path to it)
![This is an image of your task planning](This is the relative path to it)

* Shows significant planning for how tasks are planned and tracked, including a full description of the process and of the tools used

##### 10. ERD provided represents a normalised database model

![This is an image of your ERD](This is the relative path to it)

* Meets D with no duplication and ideal definition of entities

## Section 3: Code specific assessment

This section can be deleted from the readme. I have only included it here to draw your attention to it

##### 11. Model implementation represents a normalised database model

* Meets D with no duplication and ideal model implementation

##### 12. Model implementation represents a normalised database model

* Meets D and represents a highly optimised solution

##### 13. Implemented controllers demonstrate correct use of commands to query the database infrastructure

* Meets D and does so elegantly (queries chosen are the most elegant to achieve the result)

##### 14. Queries implemented provide correct data for the given scenario

* Meets CR and demonstrates exceptional understanding of database queries

##### 15. Code comments demonstrate how the queries implemented correctly represent the database structure

* Meets D and all comments are exceptionally written

##### 16. Identify and use appropriate model methods

* Identifies and uses appropriate model methods for querying on self and its relationships, extends models scope where appropriate

##### 17. Minimising database calls needed to perform an action

* Minimise all database calls and implement eager loading where appropriate

##### 18. Sanitise and validates input to maintain data integrity

* Validates and sanitises all input


