Original App Design Project - README Template
===

# Rate My College

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description

One of the reasons I found this project appealing is that the college application process can often be complicated and finding a good fit college can be challenging. The app aims to help high school juniors and seniors easily find a good fit college. I aim to use CollegeAI API, Google Maps API, and databases such as JSON files. One of the core features of the project is the student to college matching process. This feature aims to minimize the number of hours students spend looking for a college that fits their personality and academic needs or aspirations.

Rate My College is a college review and matching app for students applying to colleges. The first time a user launches the app, they will be prompted to complete a short survey in which they will answer a couple of questions to find a college they might be interested in. Afterwards, the user will be taken to a page where they can see their top 5/10 recommended choices.

In the first week of the start of the project, I plan on implementing the sign up page/ login with Facebook page, the opening survey, and integration of the APIs and databases.

### App Evaluation
- **Category:** Socail/Communication
- **Mobile:** It is a mobile app that students can use to find a good fit college. They can use it to search, view details, and read about colleges.
- **Story:** The app is aimed at making the college search eaiser for students by narrowing down the list of colleges they have to look at. 
- **Market:** Students applying to college 
- **Habit:**  One time/Seasonal Use. The usual college application season is from August until the end of January. This is the time that the app expects a large number of users.
- **Scope:** It is aimed at students that are high school seniors that are applying to college. However, anyone applying to college can use the app.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
 * User can login using Facebook account
 * User can search for a college
 * User can like/save a college
 * User can comment under a specific college
 * User can comment about student athlete lifestyle in a sports section
 * User can view academic rigor on a scale of 1 - 10
 * User can see the ranks of colleges in top 10, top 20, etc
 * User can fill out survey of college preferences during registration
 
**Optional Nice-to-have Stories**

* Find links to different colleges’ websites
* User can see photos of college campuses
* User can add a college (if it does not exist)
* User can follow a specific college for news or any updates (News API)


### 2. Screen Archetypes

* Screen Archetypes
  * Login screen
  * User can login with their Facebook account
* Stream
  * User can view a feed of photos for a specific college
  * User can press the like button under a college name to like it
* Creation
   * User can make a comment 
* Search
   * Users can search for a college using a specific keyword or phrase


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home tab
* Search tab
* Favourites & likes tab 
* News tab 
* Profile tab

**Flow Navigation** (Screen to Screen)

* Home view
   * Details view
* Search view
  * Details view 
* Favourites and likes 
   * Details view 
* News view 
  * News details view 
* Profile view 
  * Settings 
  * About 

## Wireframes
![IMG_0020](https://user-images.githubusercontent.com/96321082/176711245-ef9920ea-266f-45b0-bc63-cff640cc7ee6.jpg)

![IMG_0022](https://user-images.githubusercontent.com/96321082/176711317-fd261023-f6e8-4144-a8ac-acce6737b299.jpg)

<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>



## Week 1: 
  * Sign up page that that include a field for a username, password, and phone number 
  * Implementing login page afterwards 
  * A 4 question survey to determine a college match 
  * After the survey, the user will be led to their profile which includes their top 5/10 matches 
* How I intend to use the APIs in the first week 
  * Filtering colleges depending on students’ answers in the initial survey 
  * Create a details page for the matched colleges 
  * Add a settings page for the user to adjust location, answers to their initial survey, and add their high school name.
## Week 2: 
* Create a home page with filters such as: 
  * Best in terms of athlete life 
  * Academic rigor 
  * Proximity to current location 
* Search for a college using a keyword
* Like a college 
* Rate academic rigor 
## Week 3: 
* Commenting under a specific college/Commenting about student athlete lifestyle 
* Accessing the ranks of colleges in top 10, top 20
* Find links to different colleges’ websites
* Seeing photos of college campuses through details page
* Submitting a review for a professor/class
## Week 4: 
* Adding a college (if it does not exist)
* User follow a specific college for news or any updates
* A tab/section for the user’s liked and following colleges 
* Polish app UI 
## Week 5: 
* Additional features such as change language
* Working on UI 
## Week 6: 
* Add more additional features 
## Week 7: 
* Presentations



## Schema 
*
### Models
|Property | Type | Description | 


### Networking
* Homescreen: 
 * (Read/Get) for all the colleges that match the users inputs 
 * (Read/Get) Like a college
 * (Create/Post) a comment about a college
* Search: 
 * (Read/Get) a college based on a key word
* News & updates: 
 * (Read/Get) see news about a liked college 
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as collegeAI API]
* Getting information for a specific college **endpoint** -  /v1/api/college/info
* Autocomplete for college search **endpoint** - /v1/api/autocomplete/colleges
* Parameter for getting information such as in state tuition, and student to faculty ratio.


