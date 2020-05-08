# PHP-BASIC-TAAK-02
## Conditional statement - If
## Uitleg
Je hebt geleerd wat comparison operators zijn en dat je met `var_dump();` op het scherm kan tonen of een vergelijking tussen twee variabelen true (waar) of false (onwaar) is.
>
Behalve om te checken wat een waarde is heb je aan `var_dump();` niet zoveel als je een applicatie maakt, je maakt namelijk een vergelijking om daarna te bepalen welke code er uitgevoerd moet worden
>
Stel je maakt een spel en je moet bepalen of de speler het juiste antwoord heeft gegeven. Dan gaat dat als volgt:  
* Heeft de gebruiker het juiste antwoord gegeven dan komt er 1 bij zijn score.
* Heeft de gebruiker niet het juiste antwoord gegeven dan gebeurt er niks.
>
>_In PHP gebruik je conditional statements om waardes te vergelijken_  
>
In PHP heb je twee verschillende soorten conditional statements namelijk:
* `if, else, elseif`  
  * Gebruik je om een of meerdere waardes te vergelijken 
  * De uitkomst van de vergelijking (true, false) bepaalt welk stuk code er uitgevoerd moet worden
* `switch`  
  * Gebruik je om een waarde te vergelijken tegenover meerdere mogelijke overeenkomsten

We beginnen simpel met een `if` statement:  
>We gaan vergelijken of `$variabele1` gelijk (==) is aan `$variabele2` als de vergelijking waar (true) is tonen we de volgende tekst op het scherm _`de vergelijking is waar!`_.
* Eerst moeten we de variabelen aanmaken:
```php
    $variabele1 = 10;
    $variabele2 = 10;
```  

**In PHP zijn dit de regels voor het opschrijven van een if statement:**  

* Schrijf voor de vergelijking eerst `if()` op -> _PHP begrijpt nu dat je een vergelijking wil maken_
* Schrijf tussen de `()` de vergelijking die je wilt maken op:  
`$variabele1 == $variabele2` -> _PHP verwacht de vergelijking tussen de `()` na de if, anders snapt hij het niet!_  
>
Dit is hoe de code er dan uit komt te zien:
```php
if($variabele1 == $variabele2)
```
* PHP zal als de vergelijking true (waar) is doorgaan en verwacht een `{`
* Op de regel daarna verwacht PHP de code die hij moet uitvoeren:  
`echo "de vergelijking is waar!";`
* Om aan PHP te vertellen dat we aan het einde gekomen zijn van de code die hij moet uitvoeren ald de vergelijking waar is sluiten we af met een `}`  
>
> De syntax van een if statement:  
```php
if (condition) {
  code to be executed if condition is true;
} 
```

if (condition) {
  code to be executed if condition is true;
} 
>
Dit is hoe de gehele code er uit moet zien:
```php
$variabele1 = 10;
$variabele2 = 10;

if($variabele1 == $variabele2) {
    echo "de vergelijking is waar!";
}
```



## Leerdoelen
>1. [ ] Ik weet wat de verschillende comparison operators zijn
>2. [ ] Ik toon een vergelijking op het scherm met var_dump()
>3. [ ] Ik volg de juiste regels voor het vergelijken van variabelen

## Opdracht

>1. Schrijf je code in `index.php`
>2. Maak 10 variabelen aan met diverse waardes
>3. Maak een vergelijking met elk van de 8 genoemde comparison operators hierboven
>4. Toon de waarde (true/false) van de vergelijking op het scherm met `var_dump();` 

## Eindresultaat
Als je de opdracht goed uitvoert, wordt de volgende tekst getoond in je browser: 
>Een is gelijk aan vergelijking  
>Een is identiek aan vergelijking  
>Een is ongelijk aan vergelijking  
>Een is groter dan vergelijking  
>Een is kleiner dan vergelijking  
>Een is groter of gelijk aan vergelijking
>Een is kleiner of gelijk aan vergelijking

## Bronnen
>[Jaap vd Veen - statements](https://phpbasis.jaapvdveen.nl/basiscursus-php/les-2-inleiding-statements/)  
>[W3 Schools - operators](https://www.w3schools.com/php/php_operators.asp)  
>[W3 Schools - var_dump](https://www.w3schools.com/php/func_var_var_dump.asp)
