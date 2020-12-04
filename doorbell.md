# Pametni domofon #

Izhodišča so bila naslednja:
* video klic in odpiranje vrat na telefonu
* audio preko telefona iz kjerkoli (tudi izven lokalne mreže)
* motion detection, v naslednji fazi tudi AI prepoznava
* vsi podatki (slike) so dostopne lokalno, brez oblaka
* fizični gumb na domofonu zunaj
* zvonec v hiši in fizični gumb za odpiranje vrat (kjerkoli)


| Tehnologija | Opis
------------ | -------------
![alt text](icons/raspberry.png) | RPi | Osrednja enota v zunanjem ohišju, kot video server in MQTT client (pošiljanje signala, da nekdo zvoni)
![alt text](icons/flutter.png) | Flutter | Flutter aplikacija za pametni telefon za enosmerno video in dvosmerno audio komunikacijo ter odpiranje vrat
![alt text](icons/webrtc.png) | WebRTC | Za predvajanje vido in audio strema. UV4L server na RPi
![alt text](icons/mqtt.png) | MQTT | Za dogodke - zvonenje in odpiranje vrat
![alt text](icons/arduino.png) | ESP8266|Arduino | Za notranji zvonec (chime) kot MQTT Subscriber
