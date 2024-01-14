---
layout: post
title:  "SoundWrite Full-stack web application"
date:   2020-12-30
excerpt: "SoundWrite is an audiobook player that generates texts and allows annotation"
image: "/images/soundwrite.png"
---

## What is Soundwrite?
SoundWrite is a web application that was made to assist the user in taking notes on audiobooks. This project is being developed to address the issue of quality education which is part of the United Nations Sustainability Development Goals. Audiobooks are a vital educational tool for people with learning disabilities such as dyslexia. Although there are various audiobook providers out there, Soundwrite's main focus was on the educational side of things which created a strong emphasis around the note-taking element.
<br/>
Key features :
<ul>
  <li>Take notes as you are going through an audiobook.</li>
  <li>Able to skip to the part of an audio when you click on the note taken.</li>
  <li>Organise notes according to the audiobook you read!</li>
</ul>

## The technical stuff
### Back-end
<p><span class="image left"><img src="{{ "/images/spring.png" | absolute_url }}" alt="Spring Boot" /></span>For the back-end we utilize Java Spring boot coupled with Azure cloud services. We also use Spring security for the login flow using JWT authentication. Each time a user logs in, a new token is generated and stored in the user's cache. Once this token is stored, it is sent to the back end using a post request via Axios. This returned the user's data. How difficult was this? .... Very, considering it was my first big project (like most of my team), and having to create a complicated full-stack application from scratch was extremely challenging.
</p>



### Front-end
<p><span class="image right"><img src="{{ "/images/react.png" | absolute_url }}" alt="" /></span>For the front-end we used React. As we found out, using React and Spring Boot together isn't the most popular combination with online resources which made things extremely difficult as there wasn't much content out there to aid us. However, React as a front-end framework proved extremely versatile and we were able to have a sleek user-friendly UI.
</p>

## The end product

<div class="box">
<video width="840" height="680" controls>
  <source src="{{ "/images/soundwritevideo.mp4" | absolute_url }}" alt="" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
</div>
