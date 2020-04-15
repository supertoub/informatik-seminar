# How to hack a drone
## Management Summary
## Wie funktioniert eine Drohne
## Rechtliche Grundlagen in der Schweiz
### Rechtliche Grundlagen zu Drohnen
https://www.bazl.admin.ch/bazl/de/home/gutzuwissen/drohnen-und-flugmodelle/Europaeische_Drohnenregulierung_uebernommen.html
https://www.easa.europa.eu/easa-and-you/civil-drones-rpas
https://forum.drohnenverband.ch/c/public/easa-rules/16
### Rechtliche Grundlagen zur Privatsphäre, Kameras an Drohnen

## Angrifsszenarien
### Angriff auf GPS
Mittels eines GPS Jammers kann der Drohne die Verbundung zu GPS Satelliten erschwert werden. Diese Geräte sind in der Schweiz offiziel verboten, sind aber trotzdem natürlich im Internet bestellbar (https://www.jammer-shop.com/de/gps-stoesender.html). Fliegt die Drohne automatische Wegpunkte ab, ist es für Sie unmöglich den nächsten Wegpunkt zu finden, zudem kann sie auch den Homepunkt nicht mehr finden. Je nach Modell bleibt sie darum in der Luft stehen oder versucht an Ort und Stelle zu landen. Der Pilot kann allerdings jeder Zeit die ^Steuerung übernehmen. Er wird feststellen, dass die Drohne, besonders bei starkem Wind, viel leichter abdriftet. Da Sie nun einzig auf den Beschleunigungssensnor für die Stabilisierung angewiesen ist. Dieser nimmt leichte Abdrifts allerdings nur schwer wahr. Allerdings ist ein guter Pilot auf eine solche Situation vorbereitet und kann die Drohne auch ohne GPS manöfrieren und hat dies auch schon geübt. Hierzu kann das GPS auch manuell bei der Drohne ausgeschalten werden. Besonders bei Indoor Flügen wird dies oft gemacht, da der GPS Empfang drinnen oft schlecht oder gestört sein kann. Mittels GPS Jamming kann eine Drohne also nicht vom Himmel geholt werden, es kann höchstens das automatische abfliegen von Wegpunkten unterbunden werden, dem Piloten das fliegen erschwert werden und gewisse Sicherheitsautomatismen unterbunden werden wie z.B. die Coming Home Funktion bei Signalverlust. 

### Angriff auf Kompass
Um sich in der Z-Achse zu orientieren besitzen viele Drohnen einen Magnetsensor, welcher das Erdmagnetfeld misst. Dieser Kompass hat zwei Grundlegende Aufgaben. Einerseits sorgt er dafür, dass sich die Drohne nicht anfängt zu drehen, anderererseits wird er benötigt beim abfliegen von Wegpunkten. Hier hilft der Kompass die Richtung in welcher der nächste Wegpunkt liegt zu ermitteln.
Aus meiner eigenen Erfahrung ist dieser Magnetsensor sehr anfällig, ein Stallarmierter Untergrund reicht bereits aus um diesen zu verwirren. Mit einem starken Magnetfeld könnte nun der Drohne ein falscher Magnetischer Norden vorgegaukelt werden und sie würde im Wegpunktmodus in die falsche Richtung fliegen. Dies gillt allerdings nur für den automatischen Modus, Im normalen Freiflugmodus könnte dieser Angriff im besten Falle zu einer leichten drehung der Drohne führen, da sie sich in der Z-Achste nicht mehr otientieren kann. Allerdings nimmt hier der Beschleunigungssensor immer noch eine relative Änderung war. 

//TODO Beschreiben automatischer Modus/ Wegpunktmodus

### Angriff auf Verbindung
### Angriff auf Remote controller
### Angriff auf Steuerungs controller
### Physische Abwehr
#### Adler
https://www.nzz.ch/panorama/niederlaendische-polizei-entlaesst-ihre-anti-drohnen-greifvoegel-ld.1339000
https://www.tagesanzeiger.ch/sonntagszeitung/in-genf-gehen-adler-auf-drohnenjagd/story/27631914
#### Fangnetze
https://www.koller.engineering/net-gun/
https://www.stern.de/panorama/weltgeschehen/jagd-auf-drohnen--japans-polizei-will-unbemannte-flugobjekte-mit-netzen-fangen-6603656.html

