# O4 Homes for Interns

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
* O4 Homes for Interns is an app that allows intern's without cooprate housing find houses to rent fast and easy.
* This app allows user to interact with the admin and make enquires about a house they would like to rent.
* This app shows houses available for rent based on where they'll interning.
* I would also love to implement a share feature to allow users share a house with other individuals they wish to live with.


### App Evaluation
- **Category: Housing**
- **Mobile: Users will be able to see Todays house market and also be able to filter the market to meet their needs .**
- **Story: This app gives interns the opportunity to rent homes and talk to other interns.**
- **Market: All year round students get accepted to intern for companies and sometimes these companies do not provide housing and that becomes a responsibility for the intern to sort out..**
- **Habit: This app will be a must to have on every undergrad or Grad phone just because they find themselves in these situations often**
- **Scope: The app will include a filter tab that allows users to narrow down their options to what suits their needs, a map that shows the distance from the office to the accomodation as well as communte and a chat section to interact with other interns and house agent**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
* User can see custom launch screen
* User can register 
* User can login
* User can see app icon in home screen
* User can select from a list of houses or apartments
* User can see houses/apartments they've favorited
* User profile to view everything about a user
* User can search for an apartment
* User can filter 
    

**Optional Nice-to-have Stories**
* 1:1 Chat feature within the application
* Notifications for the chat 
* See when an intern is offline/online 
* User can see distance from home to the office 


### 2. Screen Archetypes

* Home 
   * User can see a list of Todays market,can double click to favorite a home and rent home
* Map Screen
   * This will allow users see distance from any home to select to the office
* Intern Hub Screen
   * This will allow interns chat with eachother interns and house agent 
* Users
   * This will allow interns search for other interns
* Profile Screen
   * This will allow users to see their profile details
 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Login
* Signup
* Home
* Map
* Intern Hub
* Users
* Profile

## Wireframes

![](https://i.imgur.com/qjqK13T.jpg)

## Screen Snapshots
<img src = "https://i.imgur.com/8L09nRn.png" width=200/>
<img src = "https://i.imgur.com/38vBMu1.png" width=200/>
<img src = "https://i.imgur.com/LFVdL9Z.png" width=200/>
<img src = "https://i.imgur.com/Y9Dp2QH.png" width=200/>
<img src = "https://i.imgur.com/l7AcFME.png" width=200/>
<img src = "https://i.imgur.com/YSXeFeE.png" width=200/>
<img src = "https://i.imgur.com/sAgNVjk.png" width=200/>

## App Features
* Chat: The application has a 1:1 chat implemented within the application. In this chat one can send a message to another user and recieve it in real time. This chat has read/delievered receipts as it is important that users see when their message has been seen.
* Search: The applicaion has a search bar to search for any apartment/ house
* Caching |Snaappy DB|: The application uses snappy Db to store data from the api to reduce the amount of api calls.
* Filter: The application has a filter button which allows users filter price and pet policy. The price filter allows you filter from minimum price to maximum price.
* Notifications:he application has a notification system implemented that works for  the chat whenever a user sends a message to another, the receiving user gets a notification that shows who sent the message and part of the message itself. 
* Online/Offline:The application shows when another user is offline/online.
* Upload profile pic:The application allows every user upload a profile picture to show who is behind the account.

## Challenges
* Two of my biggest challenges I had while creating this application was getting chat and notification to work I spent a week plus attempting to implement both within my code.
* This type of code cant be tested until you run the app , as you would only know when it was working once you received a notification. This was frustratinng as I tested the code multiple times and it wasn’t working as expected, and to make  matters worse I wasn’t receiving any error messages. I had to go back and read my code line to line, add log statements to test each loop, so that I could see what part of the code weren’t being tested. 






