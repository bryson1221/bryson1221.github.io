---
layout: post
title: "Refinement Plan and Code Review"
date: 2019-04-14
excerpt: "Code Review"
tags: [code review, milestone one, CS-499, SNHU, eportfolio]
comments: false
---
{% assign key_word = "eportfolio" %}
#### ePortfolio Selection and Refinement Plan

## Software Design/Engineering

For this portion of the project, I would like to apply what I learned in IT-390 working with HTML and CSS.  In the class, we used these skills for a mobile application, but for my final project I would like to apply them to my GitHub pages ePortfolio.  Rather than using one of the premade themes that is available through GitHub pages using MarkDown, I would like to create my own custom theme utilizing my skills in HTML and CSS.

To accomplish this, I plan to take the skills that I learned in IT-390, and also to research applying HTML and CSS to GitHub pages.  This portion will demonstrate my skills in software design and engineering by expanding the complexity of my GitHub pages portfolio.  It will also demonstrate my skills in HTML and CSS and my ability to apply them in a platform that is unfamiliar to me.


## Algorithms and Data Structures

For this portion of the project, I would like to improve the efficiency and complexity of a survey that I created some months ago.  The old survey will serve as the artifact, and I will apply skills that I learned in CS-340 to make the project more advanced.

I plan to go through the project and find ways to use algorithms and data structures to make it more efficient and complex.  This will demonstrate my skills with algorithms and data structures, as well as my ability to effectively use Python.


## Databases

For this portion of the final project, I plan to apply what I learned in CS-340 and create a mongoDB based database that will interface with JavaScript.  I will incorporate this into a (currently) simple chat bot I created some time ago.  

I plan to incorporate what I learned about mongoDB and also do research about interfacing mongoDB with a discord chat bot in order to add in some functionality to quickly access information about Path of Exile, a game that I play with my friends.  This will demonstrate my skills with databases, and also my ability to use JavaScript.

## Code Review

<iframe width="640" height="360" src="https://www.youtube.com/embed/n0Ym-Iry_Tc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

In this code review I detail my planned enhancements in the three areas of this project.




<article>
	<ul>
    {% for post in site.tags[key_word] %}{% if post.title != null %}
        <li class="entry-title"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> - {{ post.date | date_to_string }} </li>
    {% endif %}{% endfor %}
	</ul>