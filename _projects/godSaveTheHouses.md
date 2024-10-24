---
layout: "pageProject"
title:  "God Save The Houses"
gh_user: Pierrhum
gh_repo: GodSaveTheHouse
img: images/godsavethehouse.jpeg
photodir: "./godhouses/"
excerpt: "Alt-Ctrl mini game for a class about IOT and disabilities"
keyVal: 2023.09
year: 09/2023
school: EICNAM - CNAM ENJMIN
itch: https://nikujaga.itch.io/god-save-the-houses
display: true
format: Video game
technologies: Arduino, C++, C#, Unity, Ardity
role: "Developer, Electronics engineer"
type: 2
---
<p>This a project for a workshop about connected objects and handicap. In this game, you play as god, and you must extinguish the burning houses with your sponge, seen by human as a cloud</p>
<p>My job was to do the Alternative controller and connect it to the unity project.</p>
<p>The arduino program is getting 3 inputs from different sensors, and forwarding it to the unity project, who then interpret them.</p>
<ul>
<li>The pressure sensor : linked to a balloon placed in a sponge, to detect the hand grip pressure from the user</li>
<li>The ultrasonic distance sensor : to detect the position of the hand holding the sponge, to determine above which house is the hand</li>
<li>A button : put upside down and attach to a plate, to detect when the hand of the user is resting on it, to mimic a lake and refill the sponge.</li>
</ul>

<div class="project-gallery">
    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="{{page.photodir}}DSC_0731_resize.jpg" itemprop="contentUrl" data-size="4496x3000">
          <img class="project-image" src="{{page.photodir}}DSC_0731_resize-thumb.jpg" itemprop="thumbnail" alt="Schematics of the circuit" />
        </a>
        <figcaption itemprop="caption description">Picture of the game being played</figcaption>
    </figure>
    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="{{page.photodir}}DSC_0732_resize.jpg" itemprop="contentUrl" data-size="4496x3000">
          <img class="project-image" src="{{page.photodir}}DSC_0732_resize-thumb.jpg" itemprop="thumbnail" alt="Schematics of the circuit" />
        </a>
        <figcaption itemprop="caption description">Picture of a level finished</figcaption>
    </figure>
    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="{{page.photodir}}DSC_0736_resize.jpg" itemprop="contentUrl" data-size="4496x3000">
          <img class="project-image" src="{{page.photodir}}DSC_0736_resize-thumb.jpg" itemprop="thumbnail" alt="Schematics of the circuit" />
        </a>
        <figcaption itemprop="caption description">Picture of a sound designer working</figcaption>
    </figure>
    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="{{page.photodir}}DSC_0738_resize.jpg" itemprop="contentUrl" data-size="4496x3000">
          <img class="project-image" src="{{page.photodir}}DSC_0738_resize-thumb.jpg" itemprop="thumbnail" alt="Schematics of the circuit" />
        </a>
        <figcaption itemprop="caption description">Picture of the game being played</figcaption>
    </figure>
</div>