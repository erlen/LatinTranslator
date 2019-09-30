Latin Translator v1.0
Copyright [2019] [Ir. Erik Mols / epmols@gmail.com]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

Samenvatting
De Latin Translator is een applicatie welke Latijns/laat-middeleeuwse teksten vertaalt naar modern Nederlands,
zonder de oorspronkelijke structuur van een document aan te passen. De translator gebruikt als input een txt bestand.
De translator genereert als output een txt bestand met daarin de oorspronkelijke tekst. Alle vertalingen zijn tussen
[ ]  geplaatst. 

Vereisten
De Latin Translator maakt gebruik van Python 3.7 en PyQT5, beide dienen op uw systeem geinstalleerd te zijn. 
De applicatie is platform onafhankelijk en draait in principe op ieder besturingssysteem, waar Python en PyQT5 op
geinstalleerd zijn. De applicatie is getest op Windows 10.

Installeren
plaats de directory op een voor u geschikte plaats. Verdere handelingen, behalve de installatie van Python 3.7 en
PyQT5 zijn niet nodig. 
Na de installatie van Python kunt u PyQT5 eenvoudig installeren in een terminal met het commando:
pip install PyQT5 

Starten
Op Windows kunt u de applicatie starten door lt.bat te dubbel klikken.
Op ieder ander systeem (ook Windows) kan de applicatie gestart worden door in de directory het commando: python LatinTranslatorMain.py te geven.

Opmerkingen
Het betreft de alpha release van de applicatie. Wanneer u problemen ondervind, ontvang ik graag de volledige foutmelding.
De applicatie is getest op Windows 10 met het bestand train.txt. Dit geeft als output het bestand demo.txt . Bij erg grote 
bestanden kan de applicatie vastlopen. Het is dus niet de bedoeling volledige boeken in 1 keer te vertalen.

Bibliografie
Dumont, Andre; "Genealogisch Woordenboek", 4-3-2008, http://www.genealogieonline.nl/woordenboek/

Dank woord
De applicatie is samen ontwikkeld met de studenten DataScience van ItVitae (www.itvitae.nl). 
Met name dank aan Ivar, Jaimy en Wouter.

Ir. Erik Mols 30-9-2019
epmols@gmail.com


