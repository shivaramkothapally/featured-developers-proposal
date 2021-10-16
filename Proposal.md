# Featured-Developers-Proposal

## Statement of Purpose
  Main purpose of the project is to create an application where users can find information about developers in GDP class of 2021 in Northwest Missouri State University.  

## Functional Requirements
  This is a two page application, 
  1. Homepage will contain responsive block with information about featured developer of the day. The developer information on the homepage is going to change every day. 
  2. Users can view information about all the other developers in the second page in a list format. 
  3. In order to make changes to the developers information on the application users have to login to the application by clicking on the "Login" button on the homepage.

## Project Team
- Jaya Kumar Saga - Backend developer
- Shiva Ram Kothapally - UI Developer
## ER Diagram
![ER](https://raw.githubusercontent.com/shivaramkothapally/featured-developers-proposal/main/Images/ER.png)

## Entities 
Below are the expected entites
- Users
    - UserId - Integer
    - UserName - Character varying
    - Password - Character varying
    - CreatedOn - date
    - isDeleted - boolean
 - Developer
    - DeveloperId - Character varying
    - fullname - Character varying
    - emailaddress - Character varying
    - Skills - Character varying
    - Image - text
    - Goal - Character varying
    - LinkedInURL - Character varying
    - GithubURL - Character varying
    - CreatedOn - Date
    - lastShowed - Date
## Technology Stack
  - Backend Language - C#/.NET
  - Datahost - Heroku PostgreSQL
  - Front-end page plan - SPA (Vue)
  - Front-end responsive design - Bootstrap
  - Backend free app host - Heroku

## Performance Metrics
To check the performance of the app we will be using Lighthouse tool provided by Google. Lighthouse should show all categories like performance, Progressive web app, best practices, Accessibility and others in green.

## Link to Trello Story board

[Trello](https://trello.com/b/yRWaDdG1/featureddeveloper)

## Budget Details

![Budget details](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/BudgetInfo.PNG)

## MockUp Screens
- Below are the mockup screens at present. This can be updated based on the further discussions
### Home Page
![Home](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/Homepage.png)
### List Of Developers Page
![List](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/DevelopersList.PNG)

### Login Screen
 ![Login](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/LoginScreen.PNG)
 
## Mobile View Screens

![Home](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/HomeMobileView.PNG)

![ListView](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/DevelopersListMobileVIew.PNG)

![LoginScreen](https://github.com/shivaramkothapally/featured-developers-proposal/blob/main/Images/LoginMobileView.PNG)
 
 Note: In case any changes are required to make screen look better will discuss it with client and make appropriate changes  
  - Client approval comments are available in Issues tab
