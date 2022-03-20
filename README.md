# Home Assistant LCD Display für Temperaturanzeige
## Idee
Mein Ziel war es auf einem LCD Display Außen- und Innentemperatur anzeigen zu lassen um es schnell und auf einem Blick zu sehen.
![LCD Bild 2](https://github.com/FelixLenz-Code/HA-LCD-DIsplay-Temperatur/blob/main/Bilder/Snapshot_77.png?raw=true)
## Materialien

 - Wemos D1 mini
 - 16x2 LCD Display mit I2C Adapter
 - Kabel
 - DHT11 Temperatursensor
 - 3D gedruckter Halter
	 - Abstandsschrauben
 - Home Assistant Server mit ESPhome
 ## Umsetzung
 ### Hardware
 Als erstes verbinden wir das Display mit dem I2C Adapater (Löten). Dann verbinden wir die 4 Kabel des Adapters mit dem Wemos D1 mini plus auf plus, minus auf minus, Sda auf D2 und Scl auf D1. 

Dann noch den DHT 11 anschließen. Der Datenport geht bei mir auf den Pin D6 des Wemos D1 mini.
![LCD Bild 1](https://github.com/FelixLenz-Code/HA-LCD-DIsplay-Temperatur/blob/main/Bilder/Snapshot_76.png?raw=true)
Dann nur noch alles an den Halter anbringen. Ich habe mir diesen ausgedruckt. https://www.thingiverse.com/thing:4725030 Danke an den Ersteller dieses coolen Halters!
### Software
In diesem Projekt findet ihr die Yaml Datei um sie auf den Wemos D1 mini zu laden. Ihr müsst nur noch einige Sachen ausfüllen. Es steht alles in der Datei drin was geändert werden muss.

## Fazit
Ich hoffe ihr habt Spaß beim Nachbauen! Wenn ihr noch fragen habt schreibt mit gerne. Youtube Video folgt noch!
