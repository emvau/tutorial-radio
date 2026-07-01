# tutorial-radio
Ein Makecode-Projekt
## @fullscreen
Sende eine Nachricht per Funk an andere micro:bits!
Füge einen ``||input:wenn Knopf A geklickt||``-Block auf die Arbeitsfläche
input.onButtonPressed(Button.A, function() {
})
## 
Füge in den ``||input:wenn Knopf A geklickt||``-Block
einen ''||radio:sende Zahl||`` Block ein.
Ändere die Zahl auf 1.
## 
Jetzt brauchen wir einen Block, der auf eingehende Nachrichten wartet.
Füge einen ``||radio:wenn Zahl empfangen receivedNumber||`` Block auf die Arbeitsfläche.
