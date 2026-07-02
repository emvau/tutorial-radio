# tutorial-radio
Ein Makecode-Projekt
## @fullscreen
Sende eine Nachricht per Funk an andere micro:bits! Füge einen ``||input:wenn Knopf A geklickt||``-Block auf die Arbeitsfläche
## 
Füge in den ``||input:wenn Knopf A geklickt||``-Block einen ``||radio:sende Zahl||`` Block ein.
Ändere die Zahl auf 1.
## 
Jetzt brauchen wir einen Block, der auf eingehende Nachrichten wartet.
Füge einen ``||radio:wenn Zahl empfangen empfangeneZahl||`` Block auf die Arbeitsfläche.
## 
Füge in den ||radio:wenn Zahl empfangen|| Block einen ``||basic:zeige Symbol||`` Block ein.
Wähle ein Herz ❤️ als Symbol.
## 
Das Herz soll nur kurz erscheinen.
Füge nach dem ``||basic:zeige Symbol||`` Block einen ``||basic:pausiere (ms)||`` Block ein – stelle ihn auf 500 ms.
Danach füge einen ``||basic:lösche Bildschirm||`` Block ein.
## 
Alle micro:bits in der Nähe senden und empfangen auf der gleichen Funkgruppe. 
Füge am Anfang – in den ``||basic:beim Start||``-Block - einen ``||radio:setze Gruppe||`` Block ein.
Stelle die Gruppe auf 1.
## 
Fertig! 🎉
Lade das Programm auf zwei micro:bits herunter.
Drücke auf einem micro:bit Knopf A – der andere zeigt ein Herz!
