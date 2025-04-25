<img src="images/vercel.png">

## Team Contract

You can access our team agreed team contract here:

[https://docs.google.com/document/d/1dpHfMn3FyFn8EcrtqpR5pqBB7FA7-DTHXISeKFNhwgE/edit?usp=sharing](https://docs.google.com/document/d/1dpHfMn3FyFn8EcrtqpR5pqBB7FA7-DTHXISeKFNhwgE/edit?usp=sharing)


## Deployment with Vercel

To make Campus Resource Scheduler easily accessible to the UH Mānoa community, we’ve deployed our application using Vercel, a powerful platform for frontend frameworks and static sites. Vercel streamlines the deployment process, offering continuous integration with GitHub and automatic updates every time changes are pushed to the main branch.

With Vercel, our team is able to:
- Deploy new features quickly with minimal setup
- Preview changes via deployment previews
- Scale efficiently to accommodate traffic from students and administrators

## Live Website

You can access the deployed Campus Resource Scheduler here:
[https://campus-resource-scheduler-project.vercel.app/](https://campus-resource-scheduler-project.vercel.app/)

Feel free to explore the features we’ve implemented, from equipment and room scheduling to AI-powered recommendations. This platform aims to improve how UH Mānoa students discover and access the campus resources they need.

## Project Overview 

As a fellow student attending the University of Hawaiʻi at Mānoa, I have often wished for a piece of equipment I needed for one of my classes, a private room for a study group, or another student that could benefit from my old material used in past computer science classes. Glancing at the ideas proposed in the final project brainstorm outline, my group and I knew we could add a new fundamental website project designed to help UH Mānoa students obtain common campus resources. Therefore, we propose **Campus Resource Scheduler** as our final ICS 314 project.

### The Problem

As students attend their everyday classes at UH Mānoa, they may forget to bring an important piece of equipment once or twice, such as a mouse, earbuds, pencil, or even a laptop to a specific place. Students may also want specialized technology for a few important occasions such as a significant meeting, challenging recitation, or crucial exam, but do not know where to go to obtain them. Additionally, students may want a specialized room or lab to study, conduct work, or work on projects, but they cannot find such a place easily.

### The Solution

As a web project centered around the UH Mānoa community, the **Campus Resource Scheduler** seeks to solve these problems by providing a central hub where common campus resources, rooms, and labs can be lent out to those in need of these resources. Students can choose between what kind of resource they would like to receive for a set duration of time, regulated by the usage of accounts for authentication. Students will be able to see what resources and rooms are available or not as they access the website and return resources for community use.

## Special Sauce

As users decide what item to request or what room to schedule to fit their needs, an AI-powered algorithm can be added to recommend specific resources that are available to students. The user can also give the AI custom message requests and receive recommendations from that request. Using natural language processing and machine learning, the AI can process the user's custom message request and generate a response and recommendation based on that specific request. AI will also be able to gather information from the student's profile from profile creation, classify the user based on their profile, and generate a custom dashboard that displays available items/rooms for scheduling. The AI will only choose available resources, and also gives advice on how to use specific resources to users who may be considering scheduling the resources.

## Mockup Page Ideas

This project will be structured similarly to a renting/borrowing website with a central authority that manages what items can be borrowed and who can borrow them. 

**Roles:** 
Users will be able to log into the website, browse the directory for resources that are relevant to them through a specialized search function, and reserve items or rooms for later pick up and use. 
Site Admins will be able to monitor the users that log into the website, see what resources they have used and borrowed, manage who can borrow what item, and add additional functionality to the website itself.

**Components:**
There will be 2 main categories for equipment and physical spaces. These 2 main categories will also have their own subcategories based on types such as electronics for equipment or labs for physical spaces. Users will be able to choose what specific resource they would like to schedule for a set amount of time and filter various resources based on relevance and availability. The users can receive confirmation messages and update them via their school email. Photos will be provided of all the resources for a friendlier user experience. Website administrators will be able to modify all of these components to fit the needs of the community, as well as make modifications based on real-life updates at UH Mānoa.

**Possible Mockup Pages:**
- Landing Page
- User Home Page
- User Profile Page
- Website Introduction Page
- Equipment Page
- Borrow Equipment Page
- Return Equipment Page
- Rooms/Labs Page
- Rent Rooms/Labs Page
- Return Rooms/Labs Page
- Admin Home Page
- Configure Resources Page

## Use Case Ideas

An end-to-end scenario of using the system:
- New user enters the landing page, sign up, log into the system, and set up their profile.
- New user learns how to use the site through a introductory page they encounter before scheduling resources.
- User searches for specific items/rooms based on their needs.
- User schedules item/room successfully and receives a confirmation message and instructions for pickup.
- Admin enters landing page, logs into the system, and monitors website activity.
- Admin modifies the availability of specific items/rooms based on current events.

## Page Mockups

The following 5 page mockups will display the main functionality of the application.

### Home Page:

![](images/home-page.png)

**Campus Resource Scheduler** will have a home page displaying the main functions of the website: browsing available rooms, browsing available equipment, looking over the equipment a user has already borrowed, or conversing with the ResourceAI to find recommendations for helpful items for specific users. 

### Profile Page:

![](images/profile-page.png)

The profile page for each user can be customized to show their contact information, biography, home campus, class standing, resource reviews, and things they have borrowed. 

### Available Equipment Page:

![](images/equipment-page.png)

The equipment page of the application is the central hub for all physical resources of the application. Here, users can browse what specific items they may need and also sort items based on relevance, campus, and rating.

### Available Rooms Page:

![](images/rooms-page.png)

Like the equipment page, the rooms page is the central hub for all locational resources of the application, Here, users can browse what specific rooms they may need for their occasion and also sort rooms based on location, campus, and rating.

### Your Equipment Page:

![](images/your-equipment-page.png)

This page is the informational panel for users who are currently borrowing physical equipment or in-person spaces at any particular campus. Here, users can see what resources they are borrowing, its type, and its return deadline. 

# Overview

Welcome to the documentation of the Campus Resource Scheduler application! As a part of the UH community, this project team wanted to solve a problem common to all students attending school on a UH campus - where to borrow a resource that they will need for some time? The Campus Resource Scheduler or CRS application aims to solve this problem by providing a central hub of both physical resources and locational resources to any UH community member who may need it for a set time. This system stores an online database of available resources that users can choose from, pick up at a specified location, and return to the same location. 

Many applications of the CRS apply to the everyday lives of UH community members. Individuals who forgot to bring an important piece of equipment such as a writing utensil can use the CRS to quickly and easily borrow that piece of equipment for use and return it later. Additionally, individuals who may be going to a special or important event such as an exam can also use the CRS to retrieve an essential resource that they need for that event. Furthermore, physical spaces such as study rooms and labs are also covered by the CRS, so that UH community members who are looking for a space to complete a particular task can effortlessly rent the space for a set period of time. The CRS at its core aims to serve the UH community through providing an easy-to-use interface for borrowing all sorts of items related to academic life.

Users who engage with the CRS application will be able to customize their profile, quickly search for relevant resources to borrow, and see all the relevant details that are attributed to each resource, such as category, location, campus, appearance, and the date that it was made available. The user will also be able to filter through all of these classifications and find the resource that they most need. Additionally, there is a helper AI chatbot that will direct the user towards relevant resources to borrow based on their profile and what the user needs at that time. On the whole, the Campus Resource Scheduler will be able to suit the needs of any UH community member who is looking for a specific campus resource.

# User Guide

This section provides a detailed walkthrough of the Campus Resource Scheduler user interface, its pages, and its functionalities.

### Landing Page

![](images/landing.png)

The landing page is presented to everyone who visits the top-level URL to the website. Here the website displays some of its features to those who have not signed in yet.

### Sign Up and Sign In Pages

If a new user is accessing the website, they have the option to register as a new user by clicking the "Login" button in the upper right corner of the page, clicking "Sign Up", registering their email address, and deciding on a password. 

If an existing user is accessing the website, they can sign in to the website by clicking the "Login" button in the upper right corner of the page, clicking "Sign In", entering their email address, and inputting their password. 

### Home Page

Once the user logs in, they will have more options presented to them. They will be able to choose between borrowing equipment, borrowing rooms, looking at what resources they have borrowed, or using the AI chatbot focused on helping them find the right resource. The home page contains a short tutorial on all of the functionality of the website as well as feature a few resources that were recently made available on the website.

### Equipment Page

If the user wants to borrow a physical resource, clicking on the "Equipment" tab in the navbar will bring them to a page containing all available physical equipment. Each physical resource contains important information such as category, posted date, campus, and room. The user will also be able to filter the available physical equipment by campus and by category. To borrow a physical resource, the user can click the borrow button the bottom of a resource box.

### Rooms Page

If the user wants to borrow a locational resource, clicking on the "Rooms" tab in the navbar will bring them to a page containing all available locational equipment. Each locational resource contains important information such as category, posted date, campus, and room. The user will also be able to filter the available locational equipment by campus and by category. To borrow a locational resource, the user can click the borrow button the bottom of a resource box.

### Your Resources Page

If the user wants to check what resources they have currently borrowed, clicking on the "Your Resources" tab in the navbar will bring them to a page containing all resources that they have borrowed, whether physical or locational. Each resource listed contains important information such as category, posted date, campus, room, and return deadline. The user will be able to return their specific resource by clicking the return deadline button on the bottom of a resource box.

### LoanLink Page

If the user wants to receive suggestions on what available resource best suits their needs, clicking on the "LoanLink" tab in the navbar will bring them to a page that allows them to send a text prompt to a AI chatbot. The chatbot will then respond with its own message directing the user to a available resource that fits the occasion based on the prompt and the user's profile.

### Profile Page 

If the user wants to customize their profile, clicking on the box containing their email in the upper right corner of the page and then clicking "Profile" will bring them to their profile page. Here, the user can edit their profile and change their name, profile picture, occupation, bio, major, class standing, campus, and phone number. This information will be private to that user only, and exists to help the LoanLink chatbot to generate a more relevant answer to any requests the user may have.

### Sign Out and Change Password Pages

If the user wants to sign our of the website, clicking on the box containing their email in the upper right corner of the page and then clicking "Sign Out" will bring them to a page that will allow them to sign out.

If the user wants to change their account password, clicking on the box containing their email in the upper right corner of the page and then clicking "Change Password" will bring them to a page that will allow them to change their password by inputting the user's old password and putting in a new password.

### Admin Home Page

If the user has admin permissions, their home page will contain a list of all resources in the database along with each resource's relevant information such as owner, type, category, location, campus, and posted date.

### Configure Resources Page 

If the user hs admin permissions, clicking on the "Configure Resources" tab in the navbar will bring them to a page containing all the resources in the database. The user will then have an option to edit or delete each resource, as well as add new resources through a form. The changes will then be updated for every user in the system.

# Developer Guide



# Community Feedback
**TBA**

## Milestone 1 

You can access our Milestone 1 Dashboard here:

[https://github.com/orgs/campus-resource-scheduler-project/projects/1](https://github.com/orgs/campus-resource-scheduler-project/projects/1)

## Milestone 2

You can access our Milestone 2 Dashboard here:

[https://github.com/orgs/campus-resource-scheduler-project/projects/2](https://github.com/orgs/campus-resource-scheduler-project/projects/2)

## Milestone 3

You can access our Milestone 3 Dashboard here:

[https://github.com/orgs/campus-resource-scheduler-project/projects/4](https://github.com/orgs/campus-resource-scheduler-project/projects/4)

## The Group Behind the Project

This is the group that developed the **Campus Resource Scheduler**.
- Arthur Acenas ([https://acenasa.github.io/](https://acenasa.github.io/))
- Eric Chae ([https://ericc808.github.io/](https://ericc808.github.io/))
- Sungwon Han ([https://hanswhan.github.io/](https://hanswhan.github.io/))
- Ralph Uy ([https://ralph-uy-aes.github.io/](https://ralph-uy-aes.github.io/))
- Zeyao Zhou ([https://zeyaoz.github.io/](https://zeyaoz.github.io/))
