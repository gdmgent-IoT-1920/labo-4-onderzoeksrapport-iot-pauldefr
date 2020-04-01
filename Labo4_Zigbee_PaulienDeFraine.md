# ZigBee

## Definitie

ZigBee is open standaard draadloze communicatie technologie voor korte afstanden. Deze technologie is van het type  LPWAN(Low Power Wide Area Network). Het is een mesh-netwerk met lage kost en laag verbruik van elektriciteit. Deze technologie heeft maximum afstand van ongeveer 100 meters. ZigBee is hiermee goedkoper dan Bluetooth en Wi-Fi.

ZigBee kan “master tot master” en “master(Parent) tot slave(child)” communiceren. ZigBee kan ook connecteren met routers, waardoor er meer toestellen kunnen connecteert worden.
![Zigbee alliance](https://cdn.ttgtmedia.com/rms/onlineImages/zigbee_alliance_desktop.jpg)

Deze technologie is een aanvulling voor sommige toepassingen die gebruik maken van Wifi en bluetooth, maar waar we meer energie voor nodig hebben. Hoe minder we energie gebruiken, hoe minder het kosten zullen zijn.

## Werking

![Zigbee network](https://i.pinimg.com/originals/38/68/06/3868061062ace75c78c22e004f24ede6.jpg)

ZigBee netwerk bevat drie verschillende toestellen:

 - ZigBee coördinator  (ZC):
	 - Elk ZigBee netwerk moet minstens een ZigBee coördinator hebben, dit 
   toestel vormt  de  root/master  van  een  netwerk.  De component  
   is  verantwoordelijk  voor behandeling en opslag van data.
 - ZigBee Router  (ZR):
	 - ZigBee router is een tussenapparaat dat het mogelijk maakt om data over te dragen naar andere apparaten. Deze router wordt ook als coördinatie in het netwerk  gebruikt.
 - ZigBee End device  (ZED):
	 - Eindapparaten die data ontvangen en versturen op de netwerk laag.
Aantal  van  coördinators,  routers  en  eindapparaten  hangt  af aan  welk type netwerk topologie dat je voor  kiest.

ZigBee heeft twee manieren om data over te dragen:

 - Beacon  mode
	
	In beacon mode, zijn de coördinators en routers constant actief. Hierdoor verbruiken ze meer energie dan non-beacon mode. In deze mode, gaan routers en coördinators  niet in slaapstand.
	
 - Non-beacon  mode

	In deze mode, als er geen data stroomt vanaf eindapparaten, zullen de routers en coördinators naar slaapstand veranderen. De routers en coördinators worden pas wakker als er data doorstroomt.
	
## Topology
De meeste gebruikte netwerk topologieën van ZigBee zijn de ster-, mesh- en cluster-tree topologie.
![Topologie](https://www.assured-systems.com/uploads/media/news/zigbee%20network/zigbee-network-topologies.jpg)

### Ster(star)  topologie
Deze topologie bestaat uit een ZigBee coördinator met meerdere eindapparaten. Alle eindapparaten hebben directe connectie met de ZigBee coördinator.

### Cluster-Boom(Tree)  topologie
Deze topologie bestaat uit een ZigBee coördinator, routers en eindapparaten. Elke cluster heeft een router/coördinator die verbonden is met een hoofd ZigBee coördinator.

### Mesh  topologie
Deze topologie bestaat uit een ZigBee coördinator, routers(nodes) en eindapparaten. Elke eindapparaat kan direct communiceren met aangesloten eindapparaten. Als een node niet werkt, zal het ZigBee netwerk blijven functioneren.

## Protocol
Het protocol van ZigBee is gebaseerd op de Instituut of Electrical And Electronics Engineers(IEEE) 802.15.4-standaard. Deze standaard specificeert de fysieke en MAC-lagen van het OSI model.

 ### Fysieke laag
Deze laag wordt nog eens verdeeld in twee verschillende lagen. Elke laag werkt op twee verschillende frequenties: 868/915 MHz en 2.4GHz. Met behulp van Direct Sequence Spread Spectrum worden frequentiebanden in verschillende kanalen verdeeld.
- 2.402 – 2.480: 16 kanalen
- 915 MHz: 10 kanalen
- 868 MHz: 1 kanaal

De functies van de fysieke laag zijn energiedetectie, kanaalselectie en activatie en de- activatie van radio-ontvanger.

### MAC-laag
Zorgt voor een toegang tot het radiokanaal, door gebruik te maken van Carrier Sense Multiple Access.

## Voor- en nadelen

### Voordelen
- ZigBee kan huidige infra-red technologie  vervangen.
- ZigBee is zeer efficiënt  in energieconsumptie.
- ZigBee netwerk is makkelijk aanpasbaar(flexibel)
	- het is makkelijk om nieuwe eindapparaten toe te voegen in  netwerk.
- ZigBee is gewoon simpel en  makkelijk te  gebruiken.

### Nadelen
- Bitrate van ZigBee is  laag.
- Niet aangeraden voor gevoelige privé informatie netwerk 
	-  geen sterke encryptie, niet beveilig zoals  Wi-Fi.
-  Er bestaat nog niet veel eindapparaten voor ZigBee.
- Niet praktisch voor buiten  gebruikt.

## Toepassingen

### Industriële Toepassingen

Industriële bedrijven hebben nood aan apparaten met lage energieconsumptie, waardoor ze dan kosten kunnen verminderen. ZigBee is een van de technologieën die het meeste gebruikt wordt in deze industriële setting. Een ZigBee netwerk kan verbonden worden met het internet, waarmee men kan toezicht houden van op verre afstand.


#### Smart Home

_Controle van lichten_

Beheren van lichten met uw stem kon alleen maar God kan doen. Maar in hedendaagse wereld, kunnen we allemaal God-Like zijn met hulp van technologie zoals AI en draadloze netwerk.

Grootste bedrijf van smart light is Philips met zijn Hue Bulbs. IKEA, Hive en nog veel andere bedrijven begint mee te spelen. Smart Lighting is een systeem dat je jou lichten kunt beheren met jou smartphone, tablet of via Digitaal Assistant zoals Amazon Echo, Google Home ...

_Meten van temperatuur_

TS-9ZBS van Climax
![ZigBee Temperature Sensor for Home Automation and Energy Management](https://p.globalsources.com/IMAGES/PDT/BIG/214/B1158127214.jpg)
Met deze toestel kan je temperatuur detecteren van jou omgeving en krijgt er melding als +- 2 graden stijgt of daalt. Dit kan handig zijn in server lokalen.

_Motion Sensors:_ 
Philips Hue – Motion Sensor
![enter image description here](https://external-preview.redd.it/W9kKzmx33q1eF_mlYlO-tsIGpzanvjzqEfMlYf9txPc.jpg?auto=webp&s=fae6c35f70075369426e2f9f1bd0212b59d479ae)

Met deze sensor, kan je andere toestellen op gang brengen(trigger) bv. Lichten aanzetten Of kan je meldingen krijgen op jou smartphone.

  

_Medische toepassingen_

![Medische toepassingen van Zigbee](https://qtxasset.com/styles/breakpoint_sm_default_480px_w/s3/fierceelectronics/1561068902/HERO.jpg?O75raI25OcBD8xQQ9Iu4j4648BolgsW2&itok=QEIwgcpS)

In de linkerkant ziet je alle eindapparaten die men kunt verbinden met ZigBee netwerk en de informatie die gegenereerd zullen zichtbaar zijn op jou scherm, door het door u gebruikte eindapparaat.

## Bronnen


Wat is Zigbee? Een korte introductie en uitleg | 50five.nl. (z.d.). Geraadpleegd 3 maart 2020, van [https://www.50five.nl/blog/wat-is-zigbee.html](https://www.50five.nl/blog/wat-is-zigbee.html)

What is ZigBee Technology, Architecture and its Applications? (2018, 10 november). Geraadpleegd 3 maart 2020, van [https://www.elprocus.com/what-is-ZigBee-technology-architecture-and-its-applications/](https://www.elprocus.com/what-is-ZigBee-technology-architecture-and-its-applications/)

Zigbee - Wikipedia. (2019, 27 november). Geraadpleegd 3 maart 2020, van [https://en.wikipedia.org/wiki/ZigBee](https://en.wikipedia.org/wiki/ZigBee)

Praveen Kumar | Zigbee: A wireless Communication Protocol. (2017, 19 maart). Geraadpleegd 3 maart 2020, van [https://www.youtube.com/watch?v=N_KyK-4oJiA](https://www.youtube.com/watch?v=N_KyK-4oJiA)

Zigbee uitgelegd - wat is Zigbee? | Homey. (z.d.). Geraadpleegd 3 maart 2020, van [https://www.athom.com/nl/what-is-zigbee/](https://www.athom.com/nl/what-is-zigbee/)

Ankita Patil | Zigbee Networking. (2017, 24 maart). Geraadpleegd 3 maart 2020, van [[https://www.youtube.com/watch?v=vt1TTd5CfiE](https://www.youtube.com/watch?v=vt1TTd5CfiE)]
