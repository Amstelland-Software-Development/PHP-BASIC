# PHP-BASIC-TAAK-02
## Datatypes
## Uitleg
In een variabele kun je verschillende soorten waarden opslaan zoals een stukje tekst zoals bijvoorbeeld je naam, een heel getal zoals bijvoorbeeld je leeftijd, een decimaal getal zoals bijvoorbeeld de kosten van je telefoon abonnement. Naast tekst en cijfers heb je ook nog datatype welke handig zijn om mee te programmeren zoals true/false, null, array en objects.
>
>_Het soort waarde dat je opslaat (tekst, getal, decimaal, etc.) noemen we een datatype._
>
In PHP heb je verschillende soorten datatypes namelijk:
* strings - _een rij karakters -> Hallo wereld._
* integer - _een heel getal zonder decimalen -> 1_
* float - _een decimaal getal -> 0.1_
* boolean - _een waarde die of true (1) of false (0) is_
* null - _geen waarde_
* array - _meerdere waardes van verschillende types_

## In deze taak gaan we het hebben over het datatype string

**In PHP zijn dit de regels voor het opschrijven van een string:**
* Een **STRING** moet je altijd schrijven tussen dubbele (") of enkele (') quotes. 
* Een string kan bestaan uit een combinatie van letters en cijfers.
* Gevolgd door een logische naam - _anders onthoud jij niet meer waar de variabele voor is_ - De naam moet beginnen met een letter of een underscore (_) en is case sensitive.
* Daarna gebruik je een `=` teken.
* Daarna zet je de waarde neer die je wilt onthouden.
* En als laatste gebruik je een `;` _zo begrijpt PHP dat het het einde van de regel is_.
>_Voorbeeld:_  
>Stel je bouwt in php een spel. In dit spel moet de score van de speler worden bijgehouden. De enige manier om dit te doen is door een variabele aan te maken met een logische naam zoals bijvoorbeeld $score. 
>
>* Als je een spel begint is de score altijd 0
>* Als je het volgens de regels hierboven opschrijft ziet de code er zo uit: `$score = 0;`
>* Vergeet niet dat PHP code tussen `<?php //de code ?>` tags staat
>* Om php op het scherm te tonen gebruik je het commando `echo`  gevolgd door een spatie en de waarde die je wilt tonen dus `<?php echo waarde ?>`

## Leerdoelen
>1. [ ] Ik weet wat een variabele is
>2. [ ] Ik maak een variabele aan in PHP
>3. [ ] Ik volg de juiste regels voor het maken van een variabele
>4. [ ] Ik kan de waarde van een variabele op het scherm tonen

## Opdracht

>1. Schrijf je code in `index.php`
>2. Maak een variabele score aan met de waarde 0
>3. Toon de waarde van je variabele score op het scherm met `echo`

## Eindresultaat
Als je de opdracht goed uitvoert wordt de volgende tekst getoond in je browser: 
>0  

## Bronnen
>[W3 Schools - php](https://www.w3schools.com/PHP/default.asp)  
>[Sitemasters - variabelen/echo](http://www.sitemasters.be/tutorials/1/1/3/PHP/Variabelen_in_PHP#wat)  
>[W3 Schools - variabelen](https://www.w3schools.com/php/php_variables.asp)  
>[W3 Schools - echo](https://www.w3schools.com/php/php_echo_print.asp)  