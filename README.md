# CV #

V dokumentu navajam IT projekte, ki sem jih v glavnem sproduciral sam. Pri nekaterih je šlo za sodelovanje z drugim podjetjem, tam je to izrecno navedeno.
Projekti so navedeni v približnem vrstnem redu, od najbolj svežega do najstarejšega.

## Pametni domofon ##
Projekt je nastal zaradi potrebe po domačem domofonu. Trg ponuja sorazmerno slabo izbiro, kar pa približno ustreza zahtevam pa ima sorazmerno visoko ceno (npr. Doorbird ca 700€). Z
Izhodišča so bila naslednja:
* video klic in odpiranje vrat na telefonu
* audio preko telefona iz kjerkoli (tudi izven lokalne mreže)
* motion detection, v naslednji fazi tudi AI prepoznava
* vsi podatki (slike) so dostopne lokalno, brez oblaka
* fizični gumb na domofonu zunaj
* zvonec v hiši in fizični gumb za odpiranje vrat (kjerkoli)


| Tehnologija | Opis
------------ | -------------
| RPi | Osrednja enota v zunanjem ohišju, kot video server in MQTT client (pošiljanje signala, da nekdo zvoni)
| Flutter | Flutter aplikacija za pametni telefon za enosmerno video in dvosmerno audio komunikacijo ter odpiranje vrat
| WebRTC | Za predvajanje vido in audio strema. UV4L server na RPi
| MQTT | Za dogodke - zvonenje in odpiranje vrat
| ESP8266|Arduino | Za notranji zvonec (chime) kot MQTT Subscriber
