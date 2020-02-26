oe-reeksen-arrays-collections-scores
Op basis van een enum met scoreomschrijvingen feedback geven over de gekozen score

# Scores beheren met enums
## Declaratie van een enum Scores
Declareer een enum met de volgende elementen: 
Ondermaats, Zwak, Goed, Sterk, Uitstekend.

**'Ondermaats'** komt overeen met een score van 1. Deze klimt op naar 5 voor **'Uitstekend'**
## Opstarten
Bij het opstarten wordt 
- lstScores gevuld met de elementen uit de enum.
- cmbScore wordt gevuld met de getallen van 1 t.e.m. 5.
## ToonFeedBack
Deze methode toont een feedback in tbkFeedback
Deze luidt: 'Gekozen score: ', gevolgd door de naam van de score.
## Keuze van een score in de list- of combobox
Op basis van de gekozen score wordt er via **ToonFeedback** feedback gegeven in tbkFeedback
