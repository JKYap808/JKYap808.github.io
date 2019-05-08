---
layout: project
type: project
image: images/uhire2.png
title: UHire App
permalink: projects/uhire
# All dates must be YYYY-MM-DD format!
date: 2019-05-07
labels:
  - Software Development
  - GitHub
  - Project Management
summary: We built a virtual career fair app.
---

<img class="ui image" src="../images/uhire.png" width="600" height="300">

## Project

UHire is the app my team designed for our final project for our Software Development class.  The purpose of the app was to be an alternative to job fairs for students and companies.  Students could find companies and available positions that match their interests, and Companies could find interested students.  The concept was similar to the failed local startup HotU. The project involved developing UI, managing collections, routing pages, handling different user roles, using the google map API, and developing a way to apply for positions. 

## Involvment

I worked on the major functionality of managing the collections and applying for positions.  Filtering positions by interests, applying for positions, sorting positions, student profile cards, and most schemas were what I spent my time coding.  I managed to work on the majority of the “meat” of the app. The hardest part for me was probably getting the applications to work properly because I didn’t realize that the email function was a server call, so I had to develop a method for the client to call, which is something we didn't do in our previous class work.

The best part of creating this app was gaining experience working on a team.  Learning how to effectively use GitHub to manage our project issues and merge our branches was good experience.  We did stumble a lot over each other. Sometimes multiple people ended up working on the same thing, and our edits would break other people’s code.  I feel like a good team leader would have provided a more coherent vision and focus to the project.  

The most annoying part of developing this app was deploying to galaxy. I learned changing schemas will work locally but when deploying to meteor you are much more likely to get errors with outdated databases or default collections.  We ended up having to present our page without applications working because we didn’t want to reload galaxy right before the presentation even though the bug with applications was fixed.



You can see my project <a href="https://uhire.github.io/">here</a>.
