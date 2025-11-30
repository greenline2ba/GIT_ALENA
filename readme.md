# Môj projekt AB- finančná kalkulačka
Toto je môj historicky prvý readme file. 

```markdown
---

## Cieľ: 
Napísať fungujúci skript na základnú finančnú (investičnú/ sporiacu) kalkulačku.  

## Obsah

## Popis funkcionality: 
Používateľ zadá vstupy prostredníctvom metódy Input, systém prostredníctvom funkcie vypočíta výstup - cieľovú sumu na konci sporenia. 

> **POZOR:** Tento skript neberie do úvahy infláciu ani dane. Všetky výpočty sú len odhady.

Nice to have: systém z dát vytvorí graf zobrazujúci vývoj investície v čase. 
## ⚙️ Vstupné Parametre

| Parameter | Popis | Typ Dát |
| :--- | :--- | :--- |
| `--počiatočný_vklad` | Počiatočná jednorázová suma investície. | Float |
| `--mesačný_vklad` | Mesačná pravidelná suma investície. | Float |
| `--počet_rokov` | Doba sporenia v celých rokoch. | Integer |
| `--uroková sadzba_ročne` | Ročná úroková sadzba v percentách (napr. 5.5). | Float |


## ⚙️ Výstup: 
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


Kódové bloky (```bash lshfkhfdhfdhf) 

a inline kód ( nazov_suboru ) pre príkazy a názvy tvojich skriptov.