# Môj projekt AB- finančná kalkulačka
Toto je môj historicky prvý readme file. 

## Cieľ: 
Napísať fungujúci skript na základnú finančnú (investičnú/ sporiacu) kalkulačku.  

## Obsah

## Popis funkcionality: 
Používateľ zadá vstupy prostredníctvom metódy Input, systém prostredníctvom funkcie vypočíta výstup - cieľovú sumu na konci sporenia. 

Nice to have: systém z dát vytvorí graf zobrazujúci vývoj investície v čase. 

Vstupy: 
-počiatočný vklad
-výška mesačnej platby
-dĺžka sporenia
-očakávaný výnos

Výstup: 
-vypočítaná cieľová suma

## 📊 Príklady a Ukážky
-Scenár 1: Jednoduché sporenie (Napr. Vklad $1000, 5\%$ úrok, 10 rokov).
Zadajte počiatočný vklad: 1000
Zadajte ročnú úrokovú sadzbu (%): 5
Zadajte počet rokov: 10

>>> Výsledok: Vaša budúca hodnota po 10 rokoch bude: 1628.89


-Scenár 2: Pravidelné sporenie (Napr. pravidelný mesačný vklad $50, 5\%$ úrok, 10 rokov).
Zadajte počiatočný vklad: 1000
Zadajte ročnú úrokovú sadzbu (%): 5
Zadajte počet rokov: 10

>>> Výsledok: Vaša budúca hodnota po 10 rokoch bude: ....xxx

## 💻 Štruktúra Projektu a Technické Detaily
-Použité moduly/knižnice:
-Matematické vzorce:
Vzorec pre počiatočný vklad: $FV = P(1+r)^n$
Vzorec pre mesačné vklady: FV=PMT⋅r(1+r)n−1​
-Kľúčové funkcie:
vypocetCS(jednorazovy_vklad,pravidelny_vklad, urokova_sadzba_rocne, pocet_rokov):
