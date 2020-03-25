---
layout: posts
author: Emil
categories: [IT-Sikkerhed]
tags: [Kali Linux, SSL]
---
<h3>Dato: 25-03-2020</h3>

<h4>Emne: Prøver at lave SSL stripping på min Linux pc.</h4>

<h5>Beskrivelse:</h5>

I forbindelse med en sektion fra mit IT-sikkerheds kursus har jeg prøvet at opsætte en SSL stripper på Kali Linux.

Efter noget tid med "command not found" fik jeg det endelig op at køre på Kali.

Problemet derefter var bare at jeg ikke havde nogen anden pc på samme netværk på grund af at det var en virtual maskine.

Heldigvis havde jeg en Fedora Linux VM sat op i forvejen som, fordi det også var en VM, var sat på samme netværk som Kali.

Det lykkedes mig at reroute HTTPS til HTTP men desværre kunne jeg ikke få Microsoft Edge på Fedora Linux, som er den eneste browser som er modtagelig overfor SSL stripping.

Jeg endte derfor ud med en log fyldt med krypteret information, men i det mindste formod jeg at lytte med på forbindelsen fra Fedora til internettet.
