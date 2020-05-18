# "Hugs" Market Place

Link to the deployed app: TBA  
Link to github repo: https://github.com/evey-pea/hugs.git 

## Documentation

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

<!-- #TODO Doc: Describe usage of S3 Bucket -->

###### Geocoding Services: Google Maps API usage with Geocoder Rails Gem

<!-- #TODO Doc: Describe usage of Google Maps API using Geocoder gem-->

##### 3.1. Identify the problem you’re trying to solve by building this particular marketplace App

The purpose of the hugs marketplace is to enable people who would like a hug to find other people in their area to hug them.

##### 3.2 Why is the problem identified a problem that needs solving?

Whilst there are a large quantity of online marketplaces for human contact, these are mostly based around contact of a sexual nature. There are few online options for those seeking a consensual yet non-sexually motivated hug.

As the project is being prepared during various quarantine levels due to COVID-19 crisis, there  currently is a large number of people who will be somewhat starved of human physical contact.

The constraints to this problem are largely localisation based profile matching, as prior to meeting for a hug, the persons need to be suitable for each other and within a reasonable proximity to each other.

This is a problem that will provide a unique marketplace opportunity for this to be addressed with a web application.

##### 4. Describe your project’s models in terms of the relationships (active record associations) they have with each other

<!-- #TODO Doc: Complete discussion of the project’s models with an understanding of how its active record associations function -->


##### 5. Discuss the database relations to be implemented

<!-- #TODO Doc: ERD DB Relationship table -->
![This is an image of your ERD](This is the relative path to it)

<!-- #TODO Doc: ERD Explanation -->
* Provides coherent discussion of the database relations, with reference to the ERD


##### 6. Provide your database schema design

<!-- #TODO Doc: DB Schema design -->
* Flawless, complex, complete, and well thought through ERDs provided

##### 7. Provide User stories for your App

<!-- #TODO Doc: 5 User Stories -->
![This is an image of your user stories](This is the relative path to it)

* You also just use normal markdown to describe them
* User stories are well thought out, relevant, and comprehensively cover the needs of the app

##### 8. Provide Wireframes for your App

<!-- #TODO -Doc: 5 (min) Wireframes -->
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  
![This is an image of your wire frames](This is the relative path to it)  

* More than five detailed and well designed wireframes provided, for several different screen sizes (as required for the app)

##### 9. Describe the way tasks are planned and tracked in your project

Tasks were planned and managed using a checklist in this README.md file and by code tagging with the source files. A regular review of incomplete items was carried out with a VS Code extension called [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree&ssr=false#overview)

The advantage to using this extension is that it provides a quick way to access parts of the file that are flagged using the code tagging method. A count of the remaining flagged items is also provided to right of each filename contating the tags.

![Todo-Tree extension menu containing files and their code tag counts](/docs/todo-tree-03.png)  

In each of the two examples below, the selected item in the extension's list is also highlighted in the content of the file. Each code tag item also is highlighted in an inverted color for quick syntax reference.

![Overall task list planning in the Toto-Tree extension navigation pane](/docs/todo-tree-01.png)  
***Todo-Tree showing general tasks listed in the README.md file (implemented using hidden code tagging***


![Incomplete checkbox items in the Toto-Tree extension navigation pane](/docs/todo-tree-02.png)  
***Todo-Tree extension showing unchecked items from the README.md file***

![This is an image of your task planning](This is the relative path to it)  

* Shows significant planning for how tasks are planned and tracked, including a full description of the process and of the tools used

##### 10. ERD provided represents a normalised database model

<!-- #TODO Doc: ERD DB Model with no duplication and ideal definition of entities-->
![This is an image of your ERD](This is the relative path to it)