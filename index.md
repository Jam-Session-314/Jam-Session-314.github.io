[![jam-session-nextjs](https://github.com/Jam-Session-314/jam-session/actions/workflows/ci.yml/badge.svg)](https://github.com/Jam-Session-314/jam-session/actions/workflows/ci.yml)

# Jam Sesh-ion 🎶

## Table of Contents
- [Jam Sesh-ion 🎶](#jam-sesh-ion-)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
    - [The Solution](#the-solution)
  - [User Guide](#user-guide)
    - [Landing Page](#landing-page)
    - [Profile](#profile)
    - [Sign-in / Sign-up](#sign-in--sign-up)
    - [Creating an Account Page](#creating-an-account-page)
    - [Home Page](#home-page)
    - [Jam Session](#jam-session)
  - [Community Feedback](#community-feedback)
  - [Development History](#development-history)
    - [Milestone 1](#milestone-1)
    - [Milestone 2](#milestone-2)
    - [Milestone 3](#milestone-3)
  - [Deployment](#deployment)
  - [Example Enhancements](#example-enhancements)
  - [Team](#team)

---

Our [Team Contract](https://docs.google.com/document/d/1f1U1kpcvNE-tf4cDfWqKXqCFyr5-8HhCTtcAMeXk4z4/edit?tab=t.0#heading=h.ondungnqregq)

## Overview
Many University of Hawaiʻi students have incredible musical talent but lack a simple way to connect with others who share compatible musical skills and interests. This gap means they miss out on the joy of informal jam sessions that could grow into dynamic performing groups.

### The Solution
**Jam Sesh-ion** offers a creative platform where students can easily connect and collaborate musically. Users can log in or create profiles showcasing their musical tastes, skills, and goals—whether they’re into occasional jam sessions or looking to form a serious band. Each profile can include links to YouTube videos or SoundCloud tracks, allowing students to share examples of their musicianship and find others who align with their style and vision.

## User Guide
Upon viewing the application, the user is greeted with the landing page, which prompts them to log in to or create an account.


<img width="600px" class="rounded float-start pe-4" src="../img/landingPageGuide.png">

The user can create an account on the signup page.

<img width="600px" class="rounded float-start pe-4" src="../img/signupPage.png">

After logging in, the user is greeted with the home page.

<img width="600px" class="rounded float-start pe-4" src="../img/homePage.png">

Here, the user can view the currently posted Jam Sessions:

<img width="600px" class="rounded float-start pe-4" src="../img/viewSessions.png">

Post a new session:

<img width="600px" class="rounded float-start pe-4" src="../img/addSession.png">

View their own sessions:

<img width="600px" class="rounded float-start pe-4" src="../img/mySessions.png">

View their own profile:

<img width="600px" class="rounded float-start pe-4" src="../img/myProfile.png">

And edit their profile:

<img width="600px" class="rounded float-start pe-4" src="../img/editProfile.png">

## Community Feedback
After having five other students try out our application, they had a few suggestions on how to improve our app, and noted a few things that they liked.

* Users liked the presentation of the application, stating that it looks pretty and they like the nature-y asthethic, although they are unsure about how nature connects to a music app.
* They liked how easy it was to add and manage sessions.
* They liked the search function in the view sessions page.
* They didn't like that there wasn't a feature to show the current capacity of a session. They had no way of knowing if a session was filled up or not.
* Some users liked the profile aspect, but others didn't really know why they were needed.

## Developer Guide

To build the application, npm is required, which comes with Node.js. Go to the Node.js official website to install it.

In addition, postgreSQL is also required to store app information in a database. Visit the PostgreSQL page to install it as well.

Download or clone the repository to your computer, and run npm install in the root directory.

Set up a database for the app by running createdb jam-session in the command prompt.

Copy the sample.env file to a new file called .env, and edit the file, setting the DATABASE_URL to 

```
postgresql://username:password@localhost:5432/jam-session?schema=public
```
replacing username and password with your postgreSQL credentials.

Migrate the database by running npx prisma migrate dev, and seed it with npx prisma db seed.

Finally, run the app with npm run dev, checking localhost:3000 in your browser to view it.



## Development History

### Milestone 1

[Our M1 Project Page](https://github.com/orgs/Jam-Session-314/projects/6)

The issues that were completed for this milestone include:

- The creation and styling of the landing, sign in, and profile pages
- The addition of profile information into the prisma schema
- The addition of session information into the prisma schema
- The creation of the session view page and edit profile page
- The deployment of the app to Vercel

Current screenshots of our progress so far:

<img width="600px" class="rounded float-start pe-4" src="../img/M1LandingPage.png">

<img width="600px" class="rounded float-start pe-4" src="../img/M1LogIn.png">

<img width="600px" class="rounded float-start pe-4" src="../img/M1Profile.png">

<img width="600px" class="rounded float-start pe-4" src="../img/M1Sessions.png">



### Milestone 2

[Our M2 Project Page](https://github.com/orgs/Jam-Session-314/projects/7/)

This Milestone will be focused on both styling and functionality. By this Milestone, every page should be styled correctly, and these functionalities should be implemented:

- A page that allows the user to create sessions
- A session management page that allows the user to manage their own sessions
- Users can upload profile pictures to their profile
- A landing page that shows a featured session

Current Screenshots of what we comepleted for this milestone: 

<img width="600px" class="rounded float-start pe-4" src="../img/sessions.png">

<img width="600px" class="rounded float-start pe-4" src="../img/addsession.png">

<img width="600px" class="rounded float-start pe-4" src="../img/currentSession.png">


### Milestone 3

[Our M3 Project Page](https://github.com/orgs/Jam-Session-314/projects/9/views/1)

This Milestone will focus on finalizing the core features and improving the overall user experience. By this Milestone, the following functionalities should be completed:

- Allow users to see each other's profiles
- Allow users to sign up for jam sessions
- Change the color of the session depending on if it still needs signups or not
- Allow users to upload profile pictures to their profile
- Create a landing page that shows a featured session

Screenshots of what we have completed for this milestone: 

<img width="600px" class="rounded float-start pe-4" src="../img/newLandingNoLog.png">

<img width="600px" class="rounded float-start pe-4" src="../img/newLanding.png">

<img width="600px" class="rounded float-start pe-4" src="../img/adminPage.png">

---

## Deployment 

[Link](https://jam-session.vercel.app) to our deployment page

---

## Example Enhancements
[Examples of future enhancements will be listed here. Possible improvements may include group chat features, event scheduling tools, or expanded profile options.]

---

## Team
**Jam Sesh-ion** is proudly designed, implemented, and maintained by:
- [Cody Torres](https://codygt3.github.io)
- [Junle Yan](https://junleyan.github.io)
- [Lewen Lin](https://lewenlin.github.io/Lewen-Lin.github.io/)
- [Justine Afaga](https://jafaga.github.io)
