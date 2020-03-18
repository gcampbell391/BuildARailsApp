# BuildARailsApp
First Rails Project for SE Immersive Students, 2020


## First Rails Project

### Overview
For this project you will be working in pairs to build your very first Rails project. No tests will be involved so you will be able to be creative with your ideas so long as you meet the requirements below. Get your ideas approved by an instructor before you start coding.


### Requirements
Create a repo to be shared with your partner(s). Have your partner(s) fork and clone your repo to submit code in order to finish this project. You'll be asked to submit the link to your completed project to your 1:1 coach.

#### Database
Make sure that you are using SQLite for this project, and that your schema reflects the tables needed to execute on deliverables.

#### Models & Relationships
Your project must have at least three models that are all associated. You must have a `has_many` - `belongs_to` relationship, and a `has_many`, `through` relationship. 

Here are some examples you can choose from: 
- An Artist has many Songs, and a Song belongs to an Artist. An Artist has many Genres, through Songs.
- An Owner has many Pets, and a Pet belongs to an Owner. An Owner has many Species, through Pets.
- A Painter has many Paintings, and a Painting belongs to a Painter. A Painter has many Museums, through Paintings.
- A Vendor has many Products, and a Product belongs to a Vendor. A Vendor has many Stores, through Products.
- A Writer has many Articles, and an Article belongs to a Writer. A Writer has many Publications, through Articles. 

#### CRUD/Routing
Your application should follow RESTful conventions, in that, your models should be able to be Created, Updated, Read, and Deleted. New objects should be posted to the create actions, and updating objects should be put to the update action, etc.

#### Forms
Your project must include forms that follow the user experience and use `collection_select`. Your forms can include a nested form for your `has_many`, `belongs_to` relationship. 

For example: If I am creating a Song in a form, I should be able to select from a list of Genres that exist already, or create a new one at the same time.

#### Recap of Requirements
1 . SQLite
2 . Three models
3 . Has Many - Belongs To relationship
4 . Has Many, Through relationship
5 . CRUD actions for your models
6 . Form with `collection_select`

BONUS: Nested form for your Has_many, belongs to relationship, adding validations where appropriate for models.


### Deadline and 1:1 Requirement
Your mission is to complete as many of the requirements as possible before 1:1 time, ~ 4pm today. Submit your (public) repo link to your coach during 1:1 and come with answers to the following questions: 

- What challenges did you face in building this app? 
- What successes did you have when building this app? 
- What are (3) things you've identified through work on this app as concepts to strengthen?
- What are (3) concepts you understand really well, as evidenced when working on this app? 
