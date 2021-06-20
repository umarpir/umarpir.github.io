---
layout: post
title:  "SoundWrite Full-stack web application"
date:   2020-12-30
excerpt: "SoundWrite is an audiobook player that generates texts and allows annotation"
image: "/images/soundwrite.png"
---

## What is Soundwrite?
SoundWrite is a web application which was made to assist the user to take notes on audiobooks. This project is being developed to address the issue of quality education which is part of the United Nations Sustainablity Development Goals. Audiobooks are a vital educational tool for people with learning disabilities such as dyslexia. Although there are various audiobook providers out there, Soundwrites main focus was on the educational side of things which created a strong emphasis around the note taking element.
<br/>
Key features :
<ul>
  <li>Take notes as you are going through an audiobook.</li>
  <li>Able to skip to the part of an audio when you click on the note taken.</li>
  <li>Organise notes according to the audiobook you read!</li>

</ul>

## The technical stuff!
### Back-end
For the back-end we used Java Spring boot couple with Azure cloud services. We also used Spring security for the log in flow using JWT authentication tokens. Each time a user logged in, a new token was generated adn stored in the users cache. Once this token was stored, it was sent to the back-end using a post request via axios like so..
```
axios:
    .post(token)
```
This returned the users data. How difficult was this? .... very, considering it was my first big project (like most of my team) and having to create a complicated full stack application from scratch was extremely challanging.



### Formspring integration
The contact form below each page on the footer actually collects information! Just change your email address in the ```_config.yml``` file!

## <blockquote> woah <blockquote/>

<p><span class="image left"><img src="{{ "/images/pic02.jpg" | absolute_url }}" alt="" /></span>In both layman and nerd-speak, this is a paragraph. This is a paragraph that goes on the right side of an image. This is the text that goes under the heading and the subtitle. Paragraphs vary in length but in school we're taught to make them at least 7 sentences or else we risk getting a C. Since the paragraph didn't have a thesis or a closing argument, it's probably a C grade paragraph.</p>
