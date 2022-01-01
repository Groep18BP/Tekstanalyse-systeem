# Tekstanalyse-systeem

## Beschrijving

In dit project worden boekverslagen geanalyseerd op basis van scholingsniveau. 
Het programma is zo gemaakt dat een gebruiker zelf kan bepalen welke niveaus hij wilt analyseren.
Om een bestand 'analyseerbaar' te maken wordt er van de gebruiker geacht om een bepaald benamingsstandaard te gebruiken. 
Deze is verderop in dit bestand te vinden.

## Vereisten
Alle code is geschreven in Jupyter Notebook 6.3.0 met Python 3.8.8. 
Benodigde modules:
- GLOB
- OS
- NLTK versie 3.6.5, vereist Python 3.6, 3.7, 3.8 of 3.9
- NUMPY versie 1.21.4
- matplotlib 3.3.3, vereist Python 3.8

## Inhoud
Dit pakket bestaat uit een Jupyter Notebook en een datamap. De gebruiker kan de datamap zelf vullen met te analyseren bestanden.

## Gebruik van deze code voor andere projecten
Om dit pakket te gebruiken moet de gebruiker de te analyseren bestanden in de 'Data' folder plaatsen.
Daarna kan de gebruiker met een Jupyter Notebook de functies uitvoeren. Ook is het mogelijk om de notebook te exporteren naar een .py bestand. 
Deze is dan uit te voeren via een Command Line Interface.

## Format bestandsnaam voor te analyseren bestanden
Om een bestand toe te voegen aan de analyse wordt het volgende format geaccepteerd:

  "niveau scholing" + "id".txt
  
  voorbeelden: vmbo1.txt, vwo5.txt, vmbo3.txt
