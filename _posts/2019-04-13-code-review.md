---
layout: post
title: "Refinement Plan and Code Review"
date: 2022-10-13
excerpt: "Code Review"
tags: [code review, milestone one, CS-499, SNHU, eportfolio]
comments: false
---
{% assign key_word = "eportfolio" %}
#### ePortfolio Selection and Refinement Plan

## Software Design/Engineering

For the software design and engineering portion of the project, I used skills developed from class CS-310. In this class, we worked on a Calculator app. This sparked my interest in creating an app that can showcase my ability to design and engineer something fun. Thus, I created a Tic Tac Toe app. I enjoyed showing this to my friends and playing a few games against them.

CS-310 taught me how to use GitHub, Git, and Bitbucket as well. Without this class, I would have had an extremely difficult time understanding how push/pull works. 

## Algorithms and Data Structures

For the algorithms and data structures portion of the project, I created an optimizer that can be applied to fantasy sports. This optimizer was fueled by class CS-260: Data Structures and Algorithms. I learned how to parse CSV's, binary tree algorithms, hashing algorithms, and encryption in the form of digital signatures. 

This showcases my ability in Python and understanding of how to apply algorithms and data structures.

## Databases

For the databases portion of the final project, I created a Discord bot. This bot pulls from a database I created to allow functionality. The class DAD-220 taught me how to create structured database environments that incorporate basic processing functionality and allow for data management, data manipulation, and data analysis.

This Discord Bot shows my ability to incorporate data mining, task automation, and server security.

## Code Review

<iframe width="640" height="360" src="https://www.youtube.com/embed/n0Ym-Iry_Tc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

This code review details the enhancements I made to the 3 artifacts.

### Project Links
<article>
	<ul>
    {% for post in site.tags[key_word] %}{% if post.title != null %}
        <li class="entry-title"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> - {{ post.date | date_to_string }} </li>
    {% endif %}{% endfor %}
	</ul>
