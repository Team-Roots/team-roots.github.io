---
title: Voluntree
---
## Table of Contents
* [Important Links](#important-links)
* [Overview](#overview)
* [Badge](#badge)
* [User Guide](#user-guide)
* [Installation Guide](#installation-guide)
* [Developers](#developers)

## Important Links
* <a href = "https://github.com/team-roots">Github Organization</a>
* <a href = "https://docs.google.com/document/d/1SxHmUM0TabvZTdlGjk9RQn5Vs0THKnciOy4t1PnJ_zg/edit?usp=sharing">Team Contract</a>
* <a href = "https://github.com/orgs/team-roots/projects/1">M1 Project Board</a>
* <a href = "https://github.com/orgs/Team-Roots/projects/2">M2 Project Board</a>
* <a href = "https://github.com/orgs/Team-Roots/projects/4">M3 Project Board</a>

## Overview

Voluntree revolutionizes volunteer management by offering an intuitive platform that integrates essential features for organizations and volunteers alike. Its volunteer database allows for effective matching of volunteers with suitable opportunities, leveraging detailed profiles and preferences. Key communication tools like email ensure constant engagement, while features such as hours tracking and background screening uphold accountability and trust. The platform simplifies scheduling, supports group volunteering activities, and provides in-depth reporting capabilities. Voluntree empowers organizations to maximize the impact of their volunteer initiatives.

### Problem Statement

The problem is that there are many people who want to volunteer, but they face many challenges when it comes to finding opportunities and connecting with organizations that offer volunteer services.

### Our Solution

Our client, the Voluntree, aims to remove the friction between volunteers and organizations. They want to focus on creating a platform that easily allows volunteers to find opportunities to serve in their communities, and for organizations to share their service opportunities. It is an all-in-one application that aims to benefit the community.

### Goals

Our aim is to make it easier for volunteers to get connected with organizations.

Create a site that allows users to:
- Register and sign into their account
- Have personal profile pages
- Sign up for volunteer events
- Allow users to create volunteer events

Create a site that:

- Makes the volunteering process easier
- Looks attractive and modern
- Is easy to navigate and user-friendly

# Badge
[![ci-voluntree-meteor-react](https://github.com/Team-Roots/voluntree-meteor-react/actions/workflows/ci.yml/badge.svg)](https://github.com/Team-Roots/voluntree-meteor-react/actions/workflows/ci.yml)

# User Guide

This section provides a walkthrough of the current mockups of the application's user interface and its capabilities.

## Before Signed In Landing Page
The Landing Page sets the tone and theme for the rest of the website. On this page, we display some of the events that are available to participate in and the features Voluntree offers.
<img src="images/before-signed-in-landing.png">

## Landing Page / Dashboard
When first accessing the application, users will be greeted with the User Dashboard. This page displays the user's stats visually as a bar graph and a table. It also displays upcoming, subscribed, and recommended volunteering events.
<img src="images/after-sign-in-landing.png">

## Sign Up Page
If the user does not have an account with Voluntree, clicking on the Sign Up link in the NavBar will redirect them to the Sign Up page, where they will be prompted to complete a form.
<img src="images/sign-up-page.png">

## Log In Page
If the user has an account, then they may click on the Login link in the NavBar and they will be able to use their credentials to log in.
<img src="images/login-page.png">

## User Dashboard
After logging in, the user will be prompted to their dashboard. They will be able to see a graph and a summary of their volunteer stats, such as the number of hours they have served. It also displays upcoming, subscribed, and recommended volunteering events.
<img src="images/user-dash-1.png">
<img src="images/user-dash-2.png">

## Volunteer Event Opportunities Page
Users are able to explore events by clicking on the Events link in the NavBar. They are able to view cards of events listed on the application. To make the ease of viewing events easier, there are filtering options on the top that allows users to filter out events that fit their needs.
<img src="images/event-opportunities-page.png">

## Volunteer Event Registration Page
Users are able to click on the event card and be redirected to the volunteer event registration page. It helps users easily sign up to participate in activities. This page provides the organization's mission, location, activity details, and how the volunteer's contribution plays a role.
<img src="images/event-registration-page.png">

## Volunteer Registration Form
Users who would like to commit to help out with this event can click on the Commit button from the opportunities page or in the volunteer event registration page by clicking the I Want to Help button. Here, they can fill out the form and register for events.
<img src="images/M1/VolunteerRegistrationForm.png">

## Volunteer Add Event Page
The page allows users to create a event by defining the event name, date, descriptioin, etc.
<img src="images/M3/AddEventM3.PNG">

### Profile Page
The profile page allows users to view and edit their profile information. Similar to the dashboard, they will also be able to view their volunteer stats with Voluntree.
<img src="images/my-account.png">

### About Us
The About Us page tells the user the heart of why Voluntree exists. It connects to the heart of who we are and displays the immense impact Voluntree has had on the community
<img src="images/about-us-page.png">
<img src="images/about-us-page-2.png">

## Installation Guide
 
First, [install Meteor](https://www.meteor.com/install).

Second, visit the [Voluntree application github page](https://github.com/team-roots/voluntree-meteor-app), and click the "Use this template" button to create your own repository initialized with a copy of this application. 

Third, cd into the Voluntree /app directory and install libraries with:

```
$ meteor npm install
```

```
$ npm install cloudinary
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

## Developers

1. Truman Choy
2. Destiny Shishido
3. Kristine Orpilla
4. Juvy Ann Lucero
5. Liam Tapper
6. Yujie He
7. Yafei Wang
8. Josiah Kila

Team Roots is designed, implemented, and maintained by [Josiah Kila](https://josiahkila.github.io), [Truman Choy](https://github.com/choytr), [Destiny Shishido](https://github.com/destinyshishido), [Kristine Orpilla](https://github.com/kristineorpilla03), [Juvy Ann Lucero](https://github.com/juvyannl), [Liam Tapper](https://github.com/tliam1), [Yujie He](https://github.com/colas002), and [Yafei Wang](https://github.com/UHMyafeiwang).

_[Back to top](#important-links)_
