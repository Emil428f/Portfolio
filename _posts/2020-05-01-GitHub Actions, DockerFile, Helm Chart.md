---
layout: posts
author: Emil
categories: [DevOps]
tags: [Docker, Helm, GitHub]
---
<h3>Dato: 01-05-2020</h3>

<h4>Emne: Arbejdet med at lave en CI/CD pipeline ved brug af GitHub Actions.</h4>

<h5>Beskrivelse:</h5>

I dag har jeg forsøgt at prøve at lave en DockerFile for at kunne benytte mig af GitHub Actions til at gøre brug af Helm Charts.

Årsagen til dette er at Kubernetes benytter sig af Helm Charts til at lave og holde styr på containere. Det kunne være noget som hvor mange kopier af et image skal der være og hvilke porte skal hver container gøre brug af.

Alt dette kan styres ved brug af VALUES.yaml som indeholder alle variablerne Helm skal bruge.
