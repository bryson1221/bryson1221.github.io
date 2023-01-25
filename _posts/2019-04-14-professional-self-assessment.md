---
layout: post
title: "Professional Self-Assessment and Project Introduction"
date: 2023-1-24
excerpt: "Self Assessment"
tags: [self-assessment, final, CS-499, SNHU, eportfolio]
comments: false
---
{% assign key_word = "eportfolio" %}
# Professional Self-Assessment

This Professional Self-Assessment showcases my abilities learned throughout the Computer Science program at SNHU. 

## My Educational Journey

I began attending SNHU during the Winter of 2018. I was living in Everett, MA at the time and decided I wanted to earn a B.S. in Computer Science. I was working in the restaurant industry and knew it wasn't for me. Completing my bachelor's degree was a goal I always wanted to achieve because of the commitment it required, so I took the leap. 

After a few semesters at SNHU, I was certain this was the path I wanted to take. I had no previous coding experience, but the urge to learn more was always there. I struggled balancing work, life, and school numerous times throughout my journey but continued to stay persistent. I have learned my biggest weakness is procrastination and is something I am working on still.

Attending SNHU is one of the best decisions of my life, without knowing what future possibilities may hold!

## Program Reflection

I have learned a lot of new skills while attending SNHU, including Software project panning, Portfolio creation and management, Agile software methodologies, Full-stack development, and a Security mindset.

One of the classes I enjoyed the most was CS-310: Collaboration and Team Project. This class focused on applying appropriate change control and versioning practices and why these are important. It was also my first experience with documenting a Changelog. Our Calculator Application tutorial exposed us to push/pull methods between our local drive and GitHub/Bitbucket.

Understanding change control and versioning practices enables us to track and manage every individual change to software code. With poor practices, code can easily be over-written, lost, or forgotten. 

Workflow is controlled through good version control and can help keep the team or individual operating smoothly. A project is stored in a centralized location and team members can access the latest version. When a new feature is developed, a new branch is created to implement such feature. This keeps the team on the same page and could prevent missed deadlines, etc.

Another favorite class of mine was CS-360: Mobile Architecture and Programming. In this class we focused on user components, interface, data, and exploring our creativity. This was my first exposure to Android Studio and helped me better understand what is necessary to create a mobile application. 

I never expected the amount of preparation and research that is required to create a mobile application. I learned about the benefits of conducting surveys to better understand the user needs, which can help improve design and functionality. 

This class helped me tap into my creative side. In specific, I re-designed the Grub Hub app to a more simplistic style. Nothing too fancy, but creating buttons, menus, and log-in requirements brought my critical thinking skills to the forefront. I also enjoyed expanding on my JAVA coding skills and seeing what it takes to be an app developer.

The Computer Science program at SNHU taught me more than I ever expected to learn. I have a strong foundation for multiple coding languages, an understanding of the Software Development Life Cycle (SDLC), UI/UX design skills, software testing strategies and practices, data mining proficiency, and much more.

## Final Portfolio Summary

My final project consists of 3 artifacts. These artifacts are meaningful to me and can be applied to my daily life. I love the idea of continuing to update and utilize these artifacts after my time at SNHU.

For the software design and engineering portion of the project, I used skills developed from class CS-310. In this class, we worked on a Calculator app. This sparked my interest in creating an app that can showcase my ability to design and engineer something fun. Thus, I created a Tic Tac Toe app. I enjoyed showing this to my friends and playing a few games against them.

CS-310 taught me how to use GitHub, Git, and Bitbucket as well. Without this class, I would have had an extremely difficult time understanding how push/pull works. 

For the algorithms and data structures portion of the project, I am expanding the complexity of a Quiz Game I created when I first began taking classes at SNHU. The game is very basic and does not contain much substance. I will be dramatically improving the complexity of this game by adding a timer, difficulty level selection, scoring system, graphics, leaderboard, and categories to select from. 

This showcases my ability in Python and understanding of how to apply algorithms and data structures.

For the databases portion of the final project, I am performing CRUD operations within my SQLite Database. This database consists of statistics from the PGA for the 2022 season. I will be creating a new golfer and inserting stats, reading into stats to determine which are the most influential to a golfers' success, updating the database with additional stats, deleting data that proves to be less relevant, and cleaning up the database to make it readable.

I will also be adding a security feature that will protect this data.


### Project Links
<article>
	<ul>
    {% for post in site.tags[key_word] %}{% if post.title != null %}
        <li class="entry-title"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> - {{ post.date | date_to_string }} </li>
    {% endif %}{% endfor %}
	</ul>
