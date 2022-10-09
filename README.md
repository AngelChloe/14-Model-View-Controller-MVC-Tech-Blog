# 14 Model-View-Controller (MVC): Tech Blog


## Table of Contents

1. [Task](#task)
2. [User Story](#uaser-story)
3. [Acceptance Criteria](#acceptance-criteria)
4. [Heroku Link](heroku-link)
5. [Screen Shots](#screen-shots)
6. [Resources](#resources)
7. [Usage](#usage)
8. [Authors and Acknowledgements](#authors-and-acknowledgements)

## Task

The ask is to build a CMS-style blog site similar to a Wordpress site that follows MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication - all from scratch & deployed in Heroku. The Blog site’s where developers can publish their blog posts and comment on other developers' posts as well


## User Story

As a developer who writes about tech, I want a CMS-style blog site so that I can publish articles, blog posts, and my thoughts and opinions


## Acceptance Criteria

- Given a CMS-style blog site
- I visit the site for the first time
- I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
- I click on the homepage option, I am taken to the homepage
- I click on any other links in the navigation
- I am prompted to either sign up or sign in
- I choose to sign up
- I am prompted to create a username and password
- I click on the sign-up button
- Then my user credentials are saved and I am logged into the site
- When I revisit the site at a later time and choose to sign in
- I am prompted to enter my username and password
- I am signed in to the site
- I see navigation links for the homepage, the dashboard, and the option to log out
- I click on the homepage option in the navigation
- I am taken to the homepage and presented with existing blog posts that include the post title and the date created
- I click on an existing blog post and I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
- I enter a comment and click on the submit button while signed in
- The comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
- I click on the dashboard option in the navigation
- I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
- I click on the button to add a new blog post
- I am prompted to enter both a title and contents for my blog post
- I click on the button to create a new blog post
- The title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
- I click on one of my existing posts in the dashboard
- I am able to delete or update my post and taken back to an updated dashboard
- I click on the logout option in the navigation
- I am signed out of the site
- When I am idle on the site for more than a set time, I am able to view comments but I am prompted to log in again before I can add, update, or delete comments


## Screen Shots

- MySql Start Up
![MySql start up](https://user-images.githubusercontent.com/105569378/194733472-be8c2a70-7808-42bf-975b-d091baa60e8d.png)

- Tech Blog Home Page
![TechBlogStartUp](https://user-images.githubusercontent.com/105569378/194733477-191358cb-8a08-45b7-b435-2088e49339f7.png)

- Login or Sign Up
![LoginSignUp](https://user-images.githubusercontent.com/105569378/194733483-8753ee98-bcfc-41d4-a060-dfaa7352fe6b.png)

- Creating  Post
![CreatingA Post](https://user-images.githubusercontent.com/105569378/194733494-b6c8f130-b427-4ab0-9896-18fd6f47b584.png)

- New Post Added
![NewPostAdded](https://user-images.githubusercontent.com/105569378/194733506-4c1aabbf-6271-46bf-8431-183bc5635c65.png)


## Resources

- [Heroku Link](https://git.heroku.com/polar-brook-38055.git)

- [Repository](https://github.com/Cinderbeast/14-Model-View-Controller-MVC-Tech-Blog)


## Usage

- install npm init -y to create a new .json file
- npm install
- npm install inquirer
- npm install mysql
- mysql -u root -p
- source db/schema.sql
- exit
- npm start
- make sure server.js is connected to SQL before continuing
- In a new browser open local port 3001


## Authors and Acknowledgements:

Code created by University of Utah Bootcamp, edited by Cindy Chynoweth and with the help of other fabulous developers out there!

