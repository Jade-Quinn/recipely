![Responsive demo](/static/images/responsive.jpg)

# Recipely

[View the live project here](https://recipely-project.herokuapp.com/index)

Inspired by modern nutritionist values, Recipely aims to be a resource for meals made with simple ingredients that are easy to prepare and big on flavor. Recipely is sure to be the key ingredient to change your approach to the kitchen!

## Table of Contents:

- [The Strategy Plane](#the-strategy-plane)
- [The Scope Plane](#the-scope-plane)
- [The Structure Plane](#the-structure-plane)
- [The Skeleton Plane](#the-skeleton-plane)
- [The Surface Plane](#the-surface-plane)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## UX

### The Strategy Plane

**Why are we so special?**

Recipely is designed with anyone who lives a fast paced life in mind. The site promotes fuss-free, flavour-packed meals by allowing users to search or share recipes.

**What are the tech and design considerations?**

Users are likely view recipes while cooking or in the grocery store which suggests it will be accessed primary on mobile, with this in mind, there should be a mobile first approach to design and functionality. The target user is short on time so navigation should be intuitive and layout should quickly and clearly communicate recipie steps and ingredients.
This product is for general consumers. As this is a B2C product, it should focus heavily on branding and emotive product images.

**Project roadmap**

To determine the business objectives and user needs for this release I have created the table below. 
Each opportunity/problem is rated on a scale of 1 - 5 in two dimensions; Importance and Feasibility.

Opportunity/Problem | Importance | Feasibility
------------ | ------------- | -------------
Create form(s) to allow users to add new recipes to the site, edit them and delete them | 5 | 3
Create form(s) to allow users to sign up / sign in | 5 | 3
Include fields such as ingredients, preparation steps, required tools, cuisine, etc | 5 | 3
Allow users to search recipes in specific categories | 1 | 1
Include a section to recomend cook books | 1 | 3
Increase social media followers | 1 | 5

#### User Stories

**Goals of first time visitors and returning visitors**

- As a first time user, I want to sign up and browse through recipes for inspiration on what to cook.
- As a first time user, I want to search by category.
- As a first time user, I want to quickly read through a list of ingredients.
- As a returning user, I want to quickly find a recipie I have used before.
- As a returning user, I want to login in as a user to the site to add my own recipie.
- As a returning user, I want to update/delete a recipe I have added.
- As a returning user, I want to know that my changes have been saved successfully.

**Goals of site owner**

- As a site owner, I want to build a community around simple, nutritious meals.
- As a site owner, I want to recommend cook books.

### The Scope Plane

#### Feature Scope

To establish the feature scope for this project I am using the agile methodology, I have made a list of all possible features and given each one a difficulty rating between 1 and 3.
Each release will allow for a maximum of 12 points. The table below will be used to determine which features to prioritise and which to schedule for a later release.

Feature | Rating
------------ | -------------
Logo that links to the home page so users can orientate themselves easily | 1
Clear, consistent navigation on each page | 1
Showcase recipes on login | 2

Given limited resources, the features that offer the most value at this stage are:
- Logo that links to the home page
- Clear, consistent navigation on each page
- Informative landing page to explain to the user what th site is about
- User login and sign up
- Allow user to add a recipe
- Allow user to delete or edit a recipe
- Prevent a user from being able to edit another users recipe

### The Structure Plane

As the site will not have a lot of content to begin with a linear narrative will work best

### The Skeleton Plane

The wireframes were created using Balsamiq. They can be viewed at the following links

[Homepage](https://github.com/Jade-Quinn/lulu-loves/blob/master/documentation/home-page-wire-frame.png)

### The Surface Plane

**Colour Scheme**

The main colours used are lilac #c7aacd, yellow #f5e336, blue #a7c6ea and orange #ef7a4e
The colour pallet is bright and playful but used sparingly across the site to keep it looking clean.


**Typography**

The font used on the site is DM Sans
It is a clean and bold font but it is also slightly informal and welcoming to tie in with the overall brand aesthetic.

**Imagery**

Imagery is bright and inviting.


## Features
 
### Existing Features

- Announcement bar - highlight to users relevant information e.g. newsletter promotion or sale. This appears on the homepage only so as not to annoy the user with repetitive information.
- Image carousel - communicates to the user what the site is about
- Logo link to home page - allows users to orientate themselves quickly
- Linear navigation - allows users to easily navigate all pages
- Product page - showcase to the user products on offer
- Custom compnay value icons - highlight to users the values of the brand (e.g cruelty-free products)
- Self Care Club blog - encourages users to return to the site
- Advertise gift box product release - generate anticipation with site users
- Newsletter sign-up - encourages users to return to the site
- Custom icons and cursor - to surprise users and make the site more memorable
- Social icons in footer - allows users to further engage witht he brand and builds trust
- Contact form - allows users to easily get in contact by filling out the form

### Features Left to Implement
- In the future the site will implement a shop to allow users to purchase products

## Technologies Used

### Languages

- HTML5, CSS3, JavaScript, Python

### Planning site

- [Balsamiq](https://balsamiq.com/) was used to create Wireframes.
- [Responsive Design Checker](https://responsivedesignchecker.com/) was used to check the site design and responsiveness on different devices.

### Libraries

- [Materialize CSS and JavaScript](https://materializecss.com/getting-started.html) is used for the frontend framework to build the site's base template. Materialize JS and CSS tools were applied to speed up development. Most icons on the site are Materialize icons. I used the [Parallax template](https://materializecss.com/templates/parallax-template/preview.html)

- [FontAwesome 5.15.4](https://fontawesome.com/) is used for social links and the rating stars.

- [Google Fonts](https://fonts.google.com/) is used for teh font on the site.

- [jQuery](https://jquery.com/) to easily manipulate the DOM and update Materialize tools that require initialization.

- [Werkzeug](https://werkzeug.palletsprojects.com/en/2.0.x/#) is used to securely store passwords, salt the passwords in MongoDB, and authenticate users.

- [PyMongo](https://pymongo.readthedocs.io/en/stable/) is used to connect/communicated between Python and MongoDB.

- [Flask](https://flask.palletsprojects.com/en/2.0.x/) is used to reduce development time when building a site with Python by constructing and rending pages.

- [Jinja](https://jinja.palletsprojects.com/en/3.0.x/) template language is used with Flask to create custom templates and easily pull content from MongoDB using Python.

### Deploying project 

- [Git](https://git-scm.com/) is used to track changes made to the repository and for version control.
- [GitHub](https://github.com/) is used to store the project and to share the project.
- [GitPod](https://www.gitpod.io/) is used with the CI base template as an IDE (integrated development environment) to develop, commit, and push files to GitHub.
- [MongoDB](https://www.mongodb.com/) is the noSQL database I used to store, manipulate, and retrieve data.
- [Heroku](https://www.heroku.com/) is used to connect with my GitHub repository, manage the project, and deploy the live application.


## Testing

### Feature testing

Log in

- If Registered, click on the Login button on the navbar
- Shows login form?
- Form is validated
- Display correct profile after login

Sign up
- Click on Register link in the navbar
- Shows register form
- Fill out all details
- Click on the Register button
- Brings user to profile page
- Flash message confirms registration succeeded
- Form validated

###CRUD Testing

Create

- Click on the Add Recipe shows input form
- Empty form displays error
- Excepts validated form
- Flash message confimrs recipe has been added

Read
Navigate to all recipies

Scroll down to where that recipe is and click on Cook
Does the Recipe page render correctly?
Does the image uploaded as url render correctly?
Click on the Share button underneath the Created By, does the modal with social networks pop up?
Cancel out of the modal, does it work?
Editing a Recipe (applicable to a Session User)
[U in CRUD (Updating)]

Method 1:
Go to the Recipes section
Choose a recipe that was created by Session User
Click on the Edit button
Does the Edit Recipe form renders correctly?
Change anything about the recipe and click on save
Does the information entered updates correctly on the Recipe card?
Method 2
Go to Session User Profile section
Scroll down to the second accordion
Open recipe for editing
Click "Cook"
You are now in the Recipe page, scroll down to the buttons
Click on Edit button
Enter details
Click Save
Deleting a Recipe (applicable to a Session User)
[D in CRUD (Deleting)]

Method 1:
Go to the Recipes section
Choose a recipe that was created by Session User
Click on the Delete button
Does the modal pop up to ask if you are sure?
Click on Cancel button to exit the process
Click on Delete button to proceed with deletion
Method 2
Go to Session User Profile section
Scroll down to the second accordion
Open recipe for editing
Click "Cook"
You are now in the Recipe page, scroll down to the buttons
Click on the Delete button
Does the modal pop up to ask if you are sure?
Click on Cancel button to exit the process
Click on Delete button to proceed with deletion
- I used lighthouse in chrome developer tools to test perfromance and accessability. Screen shots of testing can be found in the testing folder within documentation


## Deployment

### Required technology

-   **Python3**: write the code and run the application
-   **PIP**: install packages
-   **Git**: version control
-   **GitPod:** IDE used to create this project.
-   **MongoDB**:  as the database to create content, add new content, and manage data
-   **Heroku**: to deploy the project and manage the app

### Project Creation

-   Use the CI [Gitpod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template).
-   From the template on GitHub click **Use this template** and enter a short and memorable name for the new repository. Select **Create repository from template**.
-   From this repository, click on green **Gitpod** button to open your new workspace.

### Deployment to Heroku
To deploy this project on the Heroku cloud platform:

#### Set up the workspace for Heroku

-   In your IDE terminal (GitPod in this case), create a requirements.txt file. This file contains all applications and dependencies required to run the app. Type this into the terminal to create the file:

        pip3 freeze --local . requirements.txt

-   Next, so that Heroku knows which Python file runs the app, create a Procfile (with a capital P) by typing this command into the terminal:

        echo web: python app.py > Procfile



#### Create the application in Heroku

-   Go to the [Heroku](https://www.heroku.com/home) website and login or create an account.
-   From your Heroku account dashboard click the **New** button and select **Create New App**
-   Create a memorable name for your new app and select the region closest to your location (Europe).


#### Connect your app to the GitHub repository:

-   Inside the dashboard for your new app, click the Deploy tab.
-   Select GitHub as your **Deplyment method**.
-   When prompted, select your Github repository and click the **Connect** button.
-   Go to the **Settings** tab of your app dashboard and select **Config Vars** > **Reveal Config Vars**.
- Add the following information:

    DEBUG:  FALSE

    IP: 0.0.0.0

    MONGO_URI:  (retrieved from MongDB)

    PORT:  5000

    SECRET_KEY: <your_secret_key>`

- From the app dashboard, return to the Deploy tab and make sure tha Main branch is selected. 
- Click  **Enable Automatic Deployment** and **Deploy Branch**.
- Your app is now successfully deployed.

### Clone and run locally

- Go to the Github repository for Horror House Reviews and click the Code dropdown
- Click Download Zip, unzip the files, and upload the files to the IDE of your choice. 
- Upload these files to your IDE
- In the terminal, install the requirements.txt file using:

        pip3 install -r requirements.txt

- Navigate to MongoDB > Create New Cluster > Create Database and create your database with collections following this [database schema](#database-structure). 

- Then, create an env.py file in your IDE with this command:

        touch env.py 

- Add this information to the env.py file:

    DEBUG:  FALSE

    IP: 0.0.0.0

    MONGO_URI:  (retrieved from MongDB)

    PORT:  5000

    SECRET_KEY: <your_secret_key>

- Store the env.py file in your .gitignore file so that this sensitive information is hidden on your GitHub repository. 

- You can now run the app on your IDE by running this command in your terminal: 

        python3 app.py

## Credits

### Media
- The photos on the homepage are from Pexels.com
- [Photo of food 1](https://www.pexels.com/photo/flat-lay-photography-of-vegetable-salad-on-plate-1640777/)
- [Photo of food 2](https://www.pexels.com/photo/assorted-sliced-fruits-in-white-ceramic-bowl-1092730/)
- [Photo of food 3](https://www.pexels.com/photo/pancake-with-honey-on-plate-357573/)
- [Photo of food 4](https://www.pexels.com/photo/baking-cheese-cooking-crust-315755/)

### Acknowledgements

- Thank you to the CI student support team for support through out this project.
