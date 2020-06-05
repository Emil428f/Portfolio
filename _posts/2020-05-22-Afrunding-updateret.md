---
layout: posts
author: Emil
categories: [DevOps, IT-sikkerhed]
tags: []
---
<h3>Dato: 05-06-2020</h3>

<h4>Emne: forbedredning af præsentation til eksamen.</h4>

<h5>Beskrivelse:</h5>

<h4>DevOps</h4>

<h3>Hvad har jeg lavet?</h3>

Inden for DevOps har jeg arbejdet primært med den teknologiske aspekt, det vil sige brugen af CI/CD. Årsagen til dette skyldes at den virksomhedsmæssige aspekt er svær at simulere hvis ikke man har en virksomhed at arbejde med.

Vi har selvfølgelig arbejdet med Trendlog men de benytter sig allerede af nogle DevOps elementer som det at have forskellige miljøer til afprøvning af kode før det går ind i produktion.

Inden for det virksomhedsmæssige aspekt af DevOps har vi CAMS modellen, som står for 'culture, automation, measurement, sharing'. Hvilke er kerneværdier bag DevOps idéen. Pointen er at beholde en virksomheds kultur, aka dens identitet som er en kombination af dens historie, medarbejdere, produkter/services samt arbejdsmoral. Her ind kommer automatisering som forsøger at effektivisere ensformige processer i virksomhedens arbejdskæde for at reducere burnout af virksomhedens medarbejdere, men det skal forsøges at gøres uden at gå på kompromis med dens kultur. Måling sker i form af KPI for at se om de automatiserede arbejdsprocesser lever op til det at effektiviseringen, og til sidst har vi deling, som går ud på at lære fra sig til sine medkollegaer sådan at de forhåbeligt leder til bedre arbejde og bedre arbejdskultur.

Den teknologiske aspekt af DevOps handler primært om automatiseringen som sker via continuous integration og continuous delivery (CI/CD). 
DevOps er kombinationen af ordne 'development' og 'operations' og CI/CD er henholdsvis de tos kombineret arbejde. 
CI omhandler det at opbygge kode, få det bygget og testet og til sidst udgivet når noget kode bliver udgivet er det CDs job at få det udrullet så det kan bruges at slutbrugeren.
Dette sker ved at operatører benytter sig af Docker eller andre lignende container systemer til at få koden udrullet som en enkelt- eller nogen gange som flere, containere. Dette gøres, med eksempel i docker, ved at lave en dockerfile som indeholder den kode som skal ud i en container. Når dockerfilen er lavet kan den nemt bliver pakket ind i en container og ved brug af containerorchetrerings software kan man nemt holde øje med hver enkel container og sætte flere containere sammen. Det er her at man vil monitorere de forskellige containere og hvis der skulle ske noget kunne man nemt og hurtigt få en ny container op. Det vil sige at downtime for et produkt eller en service vil være meget højere end hvis man kørte det på en server da man så skulle hen og troubleshoot og genstarte services.

Der findes mange forskellige værktøjer til at udføre DevOps men jeg vil primært arbejde med Jenkins, Jenkins-X GitHub Actions, Kubernetes og GKE (som bare er cloud k8s hostet hos google).

<h4>IT-sikkerhed</h4>

<h3>Hvad har jeg lavet?</h3>

I mit emne om IT-sikkerhed har jeg primært arbejdet på HLD (High-level design) det vil sige at jeg har arbejdet mere med m odeller og analyser frem for penetration testing og andre hands-on sikkerhedsemner.

Jeg har primært fokuseret på virksomheds profilering og trusselsmodellering samt EPP (endpoint protection) og andre sikkerhedskontroller for forskellige operativ systemer (primært windows og linux).

Det omhandler i brund og grund om at analysere virksomhedens værdier både for dem selv men også for de produkter de tilbyder og deres kunder. Ud fra dette kan man danne sig et overblik over hvilke trusler der ville være mest relevant for den givne virksomhed, det skal dog ikke betyde at andre trusler ikke stadig er en trussel for dem men det at sikre et IT-system er meget om det at nogen trusler er bare mere skadelige end andre, med andre ord det hele omhandler 'cost-to-benefit'. Når værdierne hos en virksomhed er fundet kan man gå videre til hvor man brainstormer de forskellige trusler der kan skade disse værdier og udfra dette kan man finde de relevante sikkerhedskontroller og få dem sat op.

Men er dette nok? Nej. Det er det ikke, for de fleste tænker kun på at sikre sig fra udfrakommende trusler, og efterlader derfor deres lokale net ubeskyttet. Det er her at EPP kommer ind i billedet. Ligegyldigt hvor meget man prøver at sikre sig fra omverdenen vil der altid være den trussel som hedder 'mennesket', alt der skal til er et simpelt link og man har nu bragt hele ens infrastruktur i fare. 

Nutildags findes der mange forskellige EPP software virksomheder som hjælper på mange forskellige fronter men det er også muligt at gøre alt det de gør uden at skulle betale dyre domme for at få det. Igen kan man lave en analyse af forskellige trusler, men denne gang for det indre netværk og vælge de relevante sikkerhedskontroller for at beskytte en imod trusler. Det kunne være application whitelisting, som gør det umuligt at åbne apps som ikke er godkendt på netværket, eller virtualisering og compartmentalisering sådan at skulle en computere blive inficeret så fordi den inficeret computer er virtuel så kan den ikke skade resten af netværket fordi den er isoleret.

<h4>Andet</h4>

<h3>Hvad har jeg lavet?</h3>

Jeg har arbejdet med min powerpoint hvor jeg har taget alle mine læringsmål og kogt dem ned til få men mere fyldige læringsmål.
