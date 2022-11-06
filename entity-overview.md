
# Table of Contents

-   [Fysiska entiteter](#orgef3b826)
    -   [Kund](#orgcb820c2)
        -   [inloggning](#orgac37128)
        -   [betalning](#org61093ea)
        -   [information](#orge8f145c)
        -   [övrigt](#orgb8514f8)
    -   [Admin](#org4f9a2ef)
        -   [inloggning](#org845f61c)
        -   [information](#orgb578f94)
        -   [övrigt](#org715ffd1)
    -   [Cykel](#org4769647)
        -   [inloggning](#orgbcdef86)
        -   [information](#orgc0f1644)
        -   [övrigt](#org5d8db8d)



<a id="orgef3b826"></a>

# Fysiska entiteter


<a id="orgcb820c2"></a>

## Kund


<a id="orgac37128"></a>

### inloggning

En kund måste vara inloggad för att få tillgång till cyklar.

-   OAuth med tex [github](https://docs.github.com/en/developers/apps/building-oauth-apps)


<a id="org61093ea"></a>

### betalning

En kund måste kunna betala för att hyra cykel.

-   med befintliga pengar på saldo?
    -   möjlighet att fylla på saldo
-   betala i efterhand?
    -   kort? swish? konto?
-   båda?


<a id="orge8f145c"></a>

### information

-   id
-   förnamn
-   efternamn
-   username ?
-   email
-   tele
-   adress ?
-   saldo ?
-   betalnings information ?
-   nuvarande lånestatus
    -   cykelid ?
    -   sträcka ?
    -   nuvarande kostnad ?
-   historik


<a id="orgb8514f8"></a>

### övrigt

-   kan en kund hyra flera cyklar samtidigt?


<a id="org4f9a2ef"></a>

## Admin


<a id="org845f61c"></a>

### inloggning

En administratör har (endast?) tillgång till admin gränssnitt.

-   OAuth ?
-   se alla städer
-   se och hantera kunder
-   se och hantera cyklar


<a id="orgb578f94"></a>

### information

-   ?


<a id="org715ffd1"></a>

### övrigt

-   En admingrupp eller flera?


<a id="org4769647"></a>

## Cykel


<a id="orgbcdef86"></a>

### inloggning

En cykel måste vara tillagd i systemet för att kunna hyras ut.

-   möjlighet att lägga till cykel
-   möjlighet att ta bort cykel
-   möjlighet att stoppa cykel


<a id="orgc0f1644"></a>

### information

-   id
-   status
    -   laddas
    -   ledig
    -   uthyrd
        -   kund id ?
    -   service
        -   status ?
-   batteristatus
-   position
-   hastighet
-   historik
-   total sträcka körd ?
-   sträcka sedan service ?
-   körtid sedan service ?
-   sträcka nuvarande uthyrning ?


<a id="org5d8db8d"></a>

### övrigt

-   räcker informationen för att uppfylla samtliga krav?
    -   [Administrativt webbgränssnitt](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.h9x6l2mn1h7)
    -   [Cykelns program](https://docs.google.com/document/d/1zWksQNmkXJgM7Q66k3-mgcxrexO6eF9xqd0Z632BwlU/edit#heading=h.yro5c9zb5bii)
-   vad behöver skickas till backend under uthyrning?
-   om backend flaskhalsar är det ett alternativ att flytta viss logik till cykeln?
    -   nuvarande kostnad ?
    -   dynamisk tid mellan uppdateringar ?
-   behöver alla fält sparas i DB?

\*

