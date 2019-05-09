---
layout: project
type: project
image: images/AlohaStudy.png
title: AlohaStudy Website
permalink: projects/alohastudy
# All dates must be YYYY-MM-DD format!
date: 2019-05-08
labels:
  - HTML
  - CSS
  - JavaScript
  - Meteor
  - Semantic
  - React
  - GitHub
summary: My team created a circuit that could cycle through the word "ALOHA" or "PAU" based on the input from a switch.
---

<img class="ui image" src="{{ site.baseurl }}/images/AlohaStudy.png">

While I was a student at the University of Hawaii at Manoa, I worked in a group of three to create a practice website called AlohaStudy. The purpose of the site would be to display study spots for students to view and rate. It had functionality such as allowing students to add, edit and delete their own spots. Users could view a list of spots and filter them by outlets amounts, indoors or outdoors, noisiness and crowdedness. Users also have a profile page where they can describe themselves. This profile page also acts as a location for users to view all spots that a certain user has posted.

A user could be one of four roles, this would be either banned, user, verified or admin.

- Banned: Cannot view spots or add spots

- User: Can view and add spots. Added spots need to be verified by an admin to appear on the main page.

- Verified: Can view and add spots. Added spots are automatically verified and thus appear on the main page.

- Admin: Can view and add spots. Can verify/edit/delete spots. Can set a user's role to banned, user or verified. Can view a list of all users.

A description on the development process as well as the complete functionality of the site is located at <a href="https://alohastudy.github.io/">alohastudy.github.io/</a>.

I personally handled a lot of the backend capabilities of the website. This is because on my previous site (<a href="http://www.ksthawaii.com/index.html">www.ksthawaii.com</a>) I had effectively only used front-end development. On this project I was responsible for the following functionalities on the website.

- Hot Spots frame on the landing page: Dynamically displays the highest 3 rated spots

- List Spots Page: displays all verified spots, has a filter function as well as a primitive search funciton

- Spots Info Page: I added the backend support to show spot info except for the comments

- Profile Page: shows info on a person as well as a list of all the spots they posted

- Moderation: ability for admins to change user roles and edit/delete/verify spots

- General backend support for partners

The project uses Semantic UI React to design and maintain the site. HTML and CSS aspects are also utilized. 

I am personally very proud of this project as I find web design interesting.
<hr>

Source: <a href="https://github.com/alohastudy/alohastudy/">github.com/alohastudy/alohastudy/</a>


