---
draft:  false
layout: project
type: project
image: images/jhosp.png
title: Java Hospital
permalink: projects/javahospital
# All dates must be YYYY-MM-DD format!
date: 2019-11-13
labels:
  - Computer Science
  - Graphical User Interface
  - JFrame
  - Java
summary:
---
Java Hospital is a Graphical User Interface that serves as a form of Hospital manage system which enables the user to carry out 6 different functionalites.

<img class="ui image" src="../images/h1.png">

>  1. Add a patient to the hospital.
>  2. Delete a patient from the hospital.
>  3. Find a patient by name and display their information onto the screen.
>  4. List all the patients.
>  5. List all the patients without insurance (0% coverage).
>  6. List all the patients that owe more than a given amount.

A **patient object** is only created when it meets the following parameters:
>  1. Patient name must be at least 5 non-blank characters long.
>  2. The level of triage must be an integer between 1-5; 1 being extremely urgent and 5 a normal vist.
>  3. The coverage value is on a percentage scale and must be between 0-100.

If any of the parameters are not met an **exception will be thrown** and may look like the following images below.

<div class="ui large right rounded images">
  <img class="ui image" src="../images/e1.png">
  <img class="ui image" src="../images/e2.png">
  <img class="ui image" src="../images/e3.png">
</div>

**Valid parameters** result in the following images provided below.

<div class="ui large right rounded images">
  <img class="ui image" src="../images/h3.png">
  <img class="ui image" src="../images/h4.png">
</div>

