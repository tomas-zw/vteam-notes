
# Table of Contents

1.  [Översikt](#org8f8235a)
    1.  [Webbaserad lösning för backend med koppling mot databas för att administrera](#org9212d20)
    2.  [REST API med möjlighet att koppla in anpassade applikationer.](#org6435441)
        1.  [Backenden kan utvecklas i godtyckligt relevant programmeringsspråk](#org36a10d8)
    3.  [Admin Webbgränssnitt där man kan administrera](#org28bb500)
    4.  [Kundens Webbgränssnitt så att den kan logga in och se](#orgb0e9c0d)
    5.  [Kundens App så att den kan logga in och se](#org0e08a64)
    6.  [Intelligensen i cykeln, program som styr och övervakar cykeln](#org678c98b)
2.  [Övrigt](#org27a3e33)
    1.  [Simulera drift i systemet](#org94e70ae)
    2.  [kodbas](#org1015d28)
    3.  [Test och Verifikation](#org3a47dae)
    4.  [Driftsättning](#org52bc177)
        1.  [optionellt](#org5498d13)



<a id="org8f8235a"></a>

# Översikt


<a id="org9212d20"></a>

## [Webbaserad](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.1d40lxinstsw) lösning för backend med koppling mot databas för att administrera

-   cyklar
-   laddstationer
-   parkeringszoner
-   tillåtna zoner att cykla i
-   utlåning/återlämning
-   hämtning av cykel


<a id="org6435441"></a>

## [REST API](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.gj0i27b1vsnw) med möjlighet att koppla in anpassade applikationer.

-   Väldokumenterat REST API
-   Hantera flera olika versioner, tex genom att använda v1/ som en del i URI:n.
-   Hantera autentisering


<a id="org36a10d8"></a>

### Backenden kan utvecklas i godtyckligt relevant programmeringsspråk

-   Python, PHP, JS
-   Hantera relevant data.


<a id="org28bb500"></a>

## [Admin Webbgränssnitt](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.h9x6l2mn1h7) där man kan administrera

-   Cyklar
-   Stationer
-   Kunder


<a id="orgb0e9c0d"></a>

## [Kundens Webbgränssnitt](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.l3doj0ee6ekb) så att den kan logga in och se

-   Konto
-   Historik


<a id="org0e08a64"></a>

## [Kundens App](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.9lb976xg99gm) så att den kan logga in och se

-   låna/lämna tillbaka cykeln
-   status på senaste resan
-   historik över gjorda resor.


<a id="org678c98b"></a>

## [Intelligensen](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.yro5c9zb5bii) i cykeln, program som styr och övervakar cykeln

-   på, av
-   hastighet, begränsa hastighet
-   position
-   behöver service/laddning


<a id="org27a3e33"></a>

# Övrigt


<a id="org94e70ae"></a>

## [Simulera drift](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.fzd271z9cau1) i systemet

-   starta via docker-compose
-   simulera n\*1000 cyklar och kunder.


<a id="org1015d28"></a>

## [kodbas](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.tsz0p919gz5x)

-   ett eller flera git repon
-   enkelt att sätta igång systemet
-   använda docker-compose
-   varje repo dokumenteras i sin egna README.md


<a id="org3a47dae"></a>

## [Test och Verifikation](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.oxraxdmxs9qc)

-   automatiserade tester
-   CI/CD flöde (github actions)
-   kodkvalitet (scrutinizer)
-   verktyg för att validera kodstandard mm skall vara del av tester


<a id="org52bc177"></a>

## [Driftsättning](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.1gcjrcfzfp07)

-   docker-compose
-   starta hela systemet med ett kommando


<a id="org5498d13"></a>

### optionellt

-   driftsätt externt

