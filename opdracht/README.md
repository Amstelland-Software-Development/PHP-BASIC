# PHP-BASIS-Eindtaak

## Een website met php
## Uitleg

Je hebt geleerd wat functies zijn. Maar hoe gebruik je deze nou het beste?  
Applicaties (zoals een php website) bestaan uit een verzameling van functies.  
Belangrijk is dat je niet alleen de programmeertaal leert maar ook dat je gaat leren hoe je nou een applicatie in elkaar zet.
>
>Voorbeeld:  
>_Als je gaat bedenken hoe je bijvoorbeeld een ei bakt en dat stap voor stap zou uitschrijven zie je dat er best wel wat nodig is om een ei te bakken Zoals: eieren, boter of olie, een pan, een fornuis, vuur. Daarnaast moet je ook nog enkele handelingen uitvoeren: spullen kopen als je ze niet hebt, het gasfornuis aansteken of stroom hebben als je een elektrisch fornuis hebt, de pan op het gasfornuis zetten, het ei breken, olie in de pan doen enz._
>
Het beste wat je kan doen is alles in kleine stukjes opdelen (in functies) en dit volgens een structuur uitvoeren. Je kan bijvoorbeeld geen ei bakken als je geen hittebron hebt. Op deze manier kan je goed overzicht houden wat er nodig is om je opdracht goed af te kunnen ronden.
>
>_Vooral als de hoeveelheid code toeneemt is het handig om goed na te denken hoe je de code kan scheiden zodat je niet telkens dezelfde code schrijft._
>  
## Leerdoelen
> 1. [ ] Ik kan de basis van PHP toepassen in een webapplicatie

## Opdracht
In deze opdracht moet je naast code schrijven ook logisch nadenken welke functies je nodig hebt en hoe je de applicatie opbouwt. **Lees onderstaande goed door!**
> 
>* Sommige delen van de code zijn al ingevuld omdat dit onderdelen zijn die we pas in PHP-Advanced behandelen. 
>* Kijk goed naar de functies die al in `functions.php` staan om te zien waar je deze voor moet gebruiken of om eventueel de code te kopieren naar je eigen functie.
>* Schrijf op papier (of in Word) je plan voor de applicatie op in pseudocode zodat je kan nalopen wat je nodig hebt.
>* Gebruik de files die in gitHub bij deze opdracht staan. _Een deel van de code is al voor je ingevuld, jij moet de ontbrekende code aanvullen!_ 
>* De pagina's zullen als eerste een foutmelding geven los die eerst op! 

### Wat moet je maken?
* Voor je start met programmeren moet je een plan (pseudocode) maken in Word of op papier
>
Voor deze opdracht moet je: 
* Een website maken met 2 pagina's een home en een productpagina. 
* Op beide pagina's moet een werkend menu staan en een footer welke via include geplaatst zijn (maak dus een `menu.php en footer.php`.
* De PHP functies in deze website zijn vereist en staan in een aparte pagina `functions.php`. Als deze pagina niet gevonden wordt dan moet er een _fatale foutmelding gegeven_ worden.
* Alle code moet volgens de juiste syntax zijn geschreven.
* De volgende elementen moeten terug komen in de code: _variabelen, datatype, string operators, indexed array, comparison operators, conditional statements, logical operators, include en require en functies_
* Op de homepagina (`index.php`) moet je het datatype van een ingevoerde waarde kunnen opvragen.  
_Een deel van de code is al voor je ingevuld, jij moet de ontbrekende code aanvullen_ 
* Op de producten (`producten.php`) moet je een lijst van 10 producten en hun prijs laten zien.
  * De producten moeten uit een array komen
  * De prijzen (in decimalen) moeten uit een array komen 
* Op de productenpagina kan de gebruiker het artikelnummer (#) invullen en het aantal dat hij wilt bestellen. Als de gebruiker op [bereken totaal] klikt moet hij de totaal prijs van de producten te zien krijgen.
* Om te kunnen bestellen moet de klant zijn leeftijd invullen.
  * Als de klant jonger is dan 16 is dan krijgt hij 1 euro korting op de totaalprijs.
  * Als de klant 19 is dan krijgt hij 19 cent korting
  * Als de klant 18 is dan krijgt hij 18 cent korting
  * Als de klant 17 is dan krijgt hij 17 cent korting
  * Als de klant 16 is dan krijgt hij 16 cent korting 
>
>_Als je dat wilt mag je de pagina's een mooie stijl geven!_

## Eindresultaat
Het eindresultaat is een volledig werkende applicatie die alle functionaliteiten bevat. Ook moet je voor de beoordeling je geschereven pseudocode of plan inleveren.

## Bronnen
>[W3 Schools - syntax](https://www.w3schools.com/PHP/php_syntax.asp)  
>[Sitemasters - variabelen/echo](http://www.sitemasters.be/tutorials/1/1/3/PHP/Variabelen_in_PHP#wat)  
>[W3 Schools - variabelen](https://www.w3schools.com/php/php_variables.asp)  
>[W3 Schools - echo](https://www.w3schools.com/php/php_echo_print.asp)  
>[W3 Schools - datatypes](https://www.w3schools.com/PHP/php_datatypes.asp)  
>[W3 Schools - gettype](https://www.w3schools.com/php/func_var_gettype.asp)  
>[W3 Schools - operators](https://www.w3schools.com/php/php_operators.asp)  
>[W3 Schools - var_dump](https://www.w3schools.com/php/func_var_var_dump.asp)  
>[W3 Schools - arrays](https://www.w3schools.com/PHP/php_arrays.asp)  
>[Jaap vd Veen - statements](https://phpbasis.jaapvdveen.nl/basiscursus-php/les-2-inleiding-statements/)    
>[W3 Schools - if else](https://www.w3schools.com/php/php_if_else.asp)  
>[W3 Schools - switch](https://www.w3schools.com/php/php_switch.asp)  
> [W3 Schools - functies](https://www.w3schools.com/php/php_functions.asp)  
> [Jaap vd Veen - functies](https://phpbasis.jaapvdveen.nl/basiscursus-php/les-3-inleiding-functies/)  
>[W3 Schools - includes](https://www.w3schools.com/php/php_includes.asp) 
