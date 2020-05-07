# PHP-BASIC-TAAK-05
## Array variabele
## Uitleg
Tot nu toe heb je steeds een variabele gemaakt met 1 waarde.
>
Je kan ook meerdere waardes in een variabele kan opslaan. Dit is bijvoorbeeld handig als je een lijst met 20 films wil tonen. Je zou dan 20 aparte variabelen kunnen maken maar het is veel handiger om dit in een array variabele te zetten. _straks moeten we misschien wel 3000 films opslaan._
>
>_Een array is een speciale variabele waarin je meerdere waardes van een of meerdere datatype kan opslaan._
>
Er bestaan verschillende soorten arrays, De meest simpele is de nummerieke (of indexed) array.
>
**In PHP zijn dit de regels voor het opschrijven van een array:**
* Om PHP te vertellen dat je een variabele gaat maken moet je beginnen met een `$`.  
* Gevolgd door een logische naam - _anders onthoud jij niet meer waar de variabele voor is_ - De naam moet beginnen met een letter of een underscore (_) en is case sensitive.
* Daarna gebruik je een `=` teken.
* Daarna gebruik je het woord `array`
* De waardes van de array zet je tussen `()` gescheiden door een `,`
* En als laatste gebruik je een `;` _zo begrijpt PHP dat het het einde van de regel is_.
>
dit ziet er in code zo uit:
```php
    $myMovies = array("Spiderman", "Batman", "The Joker");
```
Nu moeten we nog leren hoe we de waardes op het scherm kunnen tonen
>
**In PHP zijn dit de regels voor het tonen van een array:**
* Je kan de waardes uit een array opvragen via de positie [index] van de waarde
* Een indexed array begint altijd te tellen bij 0
* Dus als je de eerste waarde uit de array wilt opvragen kun je dit zo doen:
```php
    $myMovies[0];
```
>
## Leerdoelen
>1. [ ] Ik weet wat een indexed array is
>2. [ ] Ik maak een indexed array aan in PHP 
>4. [ ] Ik volg de juiste regels voor het maken van een indexed array
>5. [ ] Ik kan de waarde(s) van een indexed array variabele op het scherm tonen

## Opdracht

>1. Schrijf je code in `index.php`
>2. Maak een indexed array variabele _myMovies_ aan met minimaal 3 films
>3. Toon de waardes van de array _myMovies_ in een unordered list op het scherm met `echo`

## Eindresultaat
Als je de opdracht goed uitvoert wordt de volgende tekst getoond in je browser: 
>* Spiderman
>* Batman
>* The Joker

## Bronnen
>[W3 Schools - arrays](https://www.w3schools.com/PHP/php_arrays.asp)