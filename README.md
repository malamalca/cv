# CV #

V dokumentu navajam IT projekte, ki sem jih v glavnem sproduciral sam. Pri nekaterih je šlo za sodelovanje z drugim podjetjem, tam je to izrecno navedeno.
Projekti so navedeni v približnem vrstnem redu, od najbolj svežega do najstarejšega.
  
  
  
## PAMETNI DOMOFON ##
![alt Flutter](icons/flutter.png) ![alt MQTT](icons/mqtt.png) ![alt Arduino](icons/arduino.png) ![alt RPI](icons/raspberry.png) ![alt WEBRTC](icons/webrtc.png)

Projekt je nastal zaradi potrebe po domačem domofonu. Trg ponuja sorazmerno slabo izbiro, kar pa približno ustreza zahtevam pa ima sorazmerno visoko ceno (npr. Doorbird ca 700€). Zaradi tega je nastal kompleten produkt, ki zelo dobro opravlja svojo funkcijo. 
Osnovni HW je na bazi RPI in UV4L video in audio streaminga ter motion-a za prepoznavo gibanja. Client side je za pametne telefone napisan v Flutter-ju.
 
![alt Doorbell](doorbell.jpg) ![alt Flutter App](doorbell2.png) ![alt Flutter App](doorbell3.png)



## REGISTRACIJA DELOVNEGA ČASA EVIDENTIK ##
![alt PHP](icons/php.png) ![alt RPI](icons/raspberry.png) ![alt WEBRTC](icons/lazarus.png)

Projekt je izveden po naročilu stranke. Gre za celotno okolje za beleženje delovnega časa.  
Registratorji so fizične konzole na osnovi RaspberryPi, ki pošiljajo podatke na strežnik, kjer PHP aplikacija upravlja z izračuni, prikazi, izpisi, obračuni za plače.  
Aplikacija na RPI je bila narejena v Lazarusu oz. FreePascalu, z možnost cross-platform compiliranja tudi na Windows, Android,...  

![alt EvidentikConsole](evidentik1.jpg) ![alt EvidentikWeb](evidentik2.png)
  
  
  
## ARHINT INTRANET SISTEM ##
![alt PHP](icons/php.png) ![alt WEBRTC](icons/lazarus.png) ![alt Exchange](icons/exchange.png) ![alt IdToken](icons/idtoken.png)

Intranet sistem za CRM, izdane račune, potne naloge, opravila, dokumentni sistem in finančno poslovanje podjetja.  
Portal vključuje MS Exchange server sinhronizacijo na osnovi projekta Sinchroton, ki skrbi za sinhronizacijo kontaktov in opravil s pametnimi telefoni.  
Z vidika finančnega poslovanja vključuje PHP davčno potrjevanje, ESLOG elektronsko podpisovanje, izvoz ESLOG 1.6 in 2.0 in izvoz SEPA XML.  
Posebnost poslovanja z računi je, da je vključeno podpisovanje računov s client certifikatom v brskalniku s komponento idTokenSigning.  
Dokumentno poslovanje vključuje skeniranje prejete pošte neposredno iz spletne strani preko Websocketov in lokalne aplikacije za skeniranje (websocket server) napisane v Lazarus.  

![alt Arhint1](arhint2.png) ![alt Arhint2](arhint4.png)
  
  
  
## PAMETNE ŽALUZIJE BLINDSBOARDv3 ##
![alt Arduino](icons/arduino.png) ![alt Raspberry](icons/raspberry.png) ![alt Raspberry](icons/homekit.png)

Sistem za upravljanje domačih žaluzij je narejen na osnovi Arduino kontrolerja in lastne PCB plošče ter pameti za upravljanje.   
Arduino preko serijskega vmesnika komunicira z RPI, kjer je postavljen Homebridge, ki služi za posrednika med Apple Homekit tehnologijo in HW.  
S tem lahko uporabnik upravlja želuzje preko aplikacije "Home" v Apple okolju

![alt Arhint1](blindsboard1.jpg) ![alt Arhint2](blindsboard2.png)
  
  
  
## HOBY :: HOTELSKI SISTEM eHotelDesk ##
![alt PHP](icons/php.png)
Kopletni sistem za rezervacije gostov. Opensource na naslovu https://github.com/malamalca/ehoteldesk

<img src="https://github.com/malamalca/ehoteldesk/raw/master/resources/screenshot.png" alt="eHotelDesk" height="240">
  
  
  
## HOBY :: DRUŽINSKO DREVO FAMIREE ##
![alt PHP](icons/php.png)

Projekt je nastal z željo, da se podatki iz družinskega drevesa prenesejo iz oblaka (Geni) v lokalno aplikacijo. Projekt je Opensource dosegljiv na https://github.com/malamalca/famiree

<img src="https://github.com/malamalca/famiree/raw/master/example.png" alt="Famiree" height="240">
