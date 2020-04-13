---
layout: posts
author: Emil
categories: [DevOps]
tags: [Jenkins X, Kubernetes]
---
<h3>Dato: 13-04-2020</h3>

<h4>Emne: Funktionel CI/CD pipeline med Google Kubernetes Engine.</h4>

<h5>Beskrivelse:</h5>

Det er lykkedes mig at lave samt benytte mig af min Jenkins-X pipeline på Google Kubernetes Engine.

Det er nemt at sætte op da Jenkins-X gør det meste, så jeg skal derfor gå i dybden med hvordan den bygger pipelinen samt hvilke dele der indgår i den.

Indtil videre ved jeg at den gør brug af webhooks som kobler mit cluster sammen med mit Git Repository ved brug af https post.

Jeg mangler at sætte mig ind i hvordan den bygger apps og hvordan den gør brug af "staging" og "production" miljøer.
