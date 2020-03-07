---
layout: posts
author: Emil
categories: [DevOps]
tags: [Linux, Kubernetes]
---
<h3>Dato: 07-03-2020</h3>

<h4>Emne: Installereing af Kubernetes (minikube) på Fedora Linux.</h4>

<h5>Beskrivelse:</h5>

I forbindelse med mit kursus om DevOps på Udemy har jeg forsøgt at installere Kubernetes på en Linux VM da mit windows ikke understøtter Hyper-V.

Det viser sig at det var lidt mere besværligt end jeg troede da kubernetes kræver at ens CPU understøtter Virtualisering, hvilket min gør, men da det var en VM og derfor var emulerede cpu'er virkede det ikke.

Jeg har nu skiftet mit Host OS ud med Fedora Linux og fået Kubernetes til at virke ved brug af Dockers driver.

Der er desuden også blevet lavet en guide som forhåbelig skulle gøre det muligt for andre at installere Kubernetes på en Fedora Linux pc.
