---
layout: "pageProject"
# Title of page
title:  "Project Sample"
# what do robots need to do with the page (noindex, nofollow)
robots: noindex
# thumb of the page
img: images/bk1.jpg
# Directory path to pictures
photodir : "../images/"
# video path
# video: /videos/transept.mp4
# Excerpt of project,  used to be diffused on socials if you link project page + used on card
excerpt : A project Sample
keyVal: 2022.12 #put date of project, in this way, working as a float
year: 12/2022 #put date of project as a real date
# If project was made during school uncomment below line
# school: "University of something"
# If project was made during employment uncomment below lines
#enterprise: "Company name"
# If project was made for specific client, uncomment line
#client: "Some Client"

# Format of what you've done, video game, music
format: Example
# Label of techs used
tech-label: "Techs :"
# Technologies you worked with (uses labels from config)
techs:
  - csharp
  - cpp
# Your role in this project
role: "Mastermind"
# If the project is shipped
shipped: true
# Type of project, based on collection projectTypes in config file
type: 1

# Outside links to the project, displayed in order, icon is from font awesome
links:
  - label: "Test it"
    icon: "fas fa-link"
    url: ""

# If the card should be shown on the website (or hidden)
display: true
---
this is an exemple page of project

With some picture example of photoswipe

<div class="project-gallery">
    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="{{page.photodir}}bk1.jpg" itemprop="contentUrl" data-size="4013x2158">
          <img class="project-image" src="{{page.photodir}}thumb-bk1.jpg" itemprop="thumbnail" alt="Sunset on sea from a port taken in Taipei, Taiwan" />
        </a>
        <figcaption itemprop="caption description">Sunset on sea from a port taken in Taipei, Taiwan</figcaption>
    </figure>
</div>