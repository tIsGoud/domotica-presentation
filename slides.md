
<!-- .slide: data-menu-title="GroSkills 5th edition" data-background-image="images/groskills.jpg" data-background-opacity="0.3" -->
# GroSkills 5th edition

donderdag 6 februari 2020

## Domotica

9:00 - 10:00 & 11:00 - 12:00

note:
GroSkills 5th edition, 6 februari 2020
&#x1F93D;&#x200D;&#x2642;&#xFE0F;

Todo:

- roomba toevoegen ?
- Visualisatie? Grafana
- links bijwerken
- tekst in de titels nazien
- slide tekst in het Engels en Nederlands
- DomoticaGrunn promoten (stickers)

---

<!-- .slide: data-menu-title="Wat is Domotica" data-background-image="images/brain.png" data-background-opacity="0.2" -->
## Wat is Domotica of Home Automation

- Wat kun je ermee?

- Hoe begin je met het 'slimmer' maken van je huis.

---

<!-- .slide: data-menu-title="Domotica" -->
## Domotica

![Domus + Robotica](images/Domus_plus_Robotica.png)<!-- .element height="90%" width="90%" -->

--

<!-- .slide: data-menu-title="Smart vs Automated Home" -->
## Smart vs Automated

![Smart vs Automated](images/smart_vs_automated_home.png)<!-- .element height="90%" width="90%" -->

---

<!-- .slide: data-menu-title="Modern Times (1936)" data-background-image="images/modern-times-automated-eating.gif" data-background-opacity="0.7" -->

## Modern Times (1936)

note:

Charlie Chaplin in Modern Times (1936), [Giphy](https://media.giphy.com/media/o2NnUFBsrOMog/giphy.gif)
en eerder: Fritz Lang's Metropolis (1927)

--

<!-- .slide: data-menu-title="Het Huis van de Toekomst (1989)" data-background-image="images/modern-times-automated-eatingss.gif" data-background-opacity="0.3" -->
## Het Huis van de Toekomst (1989)

![Chriet Titulaer](images/Chriet-Titulaer-bij-het-Huis-van-de-Toekomst-in-Rosmalen-archieffoto-ANP.jpg)

note:

Zomer van 1989, opening Huis van de Toekomst in Rosmalen

---

<!-- .slide: data-menu-title="Definitions" data-background-image="images/wikipedia.png" data-background-opacity="0.1" -->
## Definities

> Het toepassen van elektronica en huisnetwerken ten behoeve van de automatisering van processen in en om een woning. <!-- .element: class="fragment" data-fragment-index="1" -->

> De integratie van technologie en diensten, ten behoeve van een betere kwaliteit van wonen en leven.<!-- .element: class="fragment" data-fragment-index="2" -->

note:

Bronnen Wikipedia en Stichting Smart Homes

Oorspronkelijk bedoelt voor personen met een "functiebeperking"

---

<!-- .slide: data-menu-title="Waarom niet" -->
## Waarom niet?

- Ingewikkeld
- Techniek is niet volwassen (geen standaardisatie)
- Het is duur
- Niet veilig
- Je wordt er lui van
- Je wordt er afhankelijk van
- Het kost te veel tijd

--

<!-- .slide: data-menu-title="Security" -->
## Security

- Waar gaat jouw data naar toe?
- Wat kan iemand met jouw data?
- Je huis in gijzeling? Ransomware?
- etc.
- etc.
- etc.

---

<!-- .slide: data-menu-title="Waarom wel" -->
## Waarom wel?

- Gebruiksgemak <!-- .element: class="fragment" data-fragment-index="1" -->
- Wooncomfort <!-- .element: class="fragment" data-fragment-index="2" -->
- Veiligheid <!-- .element: class="fragment" data-fragment-index="3" -->
- Efficient energie gebruik <!-- .element: class="fragment" data-fragment-index="4" -->
- Leuk <!-- .element: class="fragment" data-fragment-index="5" -->
- Leerzaam <!-- .element: class="fragment" data-fragment-index="6" -->

note:

- Gebruiksgemak (Licht automatisch uit/aan)
- Wooncomfort (Verwarming automatisch uit/aan)
- Veiligheid (Inbraakpreventie)
- Efficient energie gebruik (Tado/Nest)

---

<!-- .slide: data-menu-title="Wat wil je automatiseren" data-background-image="images/modern-times-work.gif" data-background-opacity="0.3"-->
## Wat wil je automatiseren?

--

<!-- .slide: data-menu-title="Voorbeelden" data-background-image="images/chip_bg.jpg" data-background-opacity="0.1"-->
## Voorbeelden

--

<!-- .slide: data-menu-title="Mijn praktijk voorbeelden" -->
## Mijn praktijk voorbeelden

- Verwarming uit en aan o.b.v. aanwezigheid
- Verlichtings scenes
- Kerstverlichting uit en aan met timer
- Bewegingsdetectie en notificatie
- Licht automatisch aan bij thuiskomst van de eerste persoon na zonsondergang
- Slimme meter uitlezen
- Opbrengst Zonnepanelen (Fronius)
- Temperatuur, vochtigheid en luchtdruk metingen
- etc.

---

<!-- .slide: data-menu-title="Hoe werkt het" -->
## Hoe werkt het?

![Sensor - Controler - Actuator](images/sensor-controller-actuator.png)<!-- .element heigth="80%" width="80%" align="center" -->

note:
omgeving => sensor => processor => actuator => omgeving

sensor = apparaat dat informatie uit de omgeving kan waarnemen (zintuig)
actuator = toestel dat invloed kan uitoefenen op de (actuator) omgeving
controller = verwerk sensor gegevens en stuur actuator aan (processor, regelaar, computer)

--

<!-- .slide: data-menu-title="Signalen - Protocollen" data-background-image="images/tin-can-telephone.jpg" data-background-opacity="0.2"-->
## Signalen - Protocollen

- WiFi, 2,4 GHz
- Zigbee
- 6LoWPAN
- Zwave
- RF, X10 afgeleide
- X10
- CHIP, Connected Home over IP(v6)
  - protocol in ontwikkeling
- MQTT, pub-sub messaging

--

<!-- .slide: data-menu-title="Project CHIP" -->
## Project CHIP
![Project CHIP](images/Project-Connected-Home-over-IP-Proposal.jpg)

--

<!-- .slide: data-menu-title="MQTT" -->
![MQTT logo](images/mqtt-logo.png)

> MQTT is a machine-to-machine (M2M)/IoT connectivity protocol. It was designed as an extremely lightweight publish/subscribe messaging transport.

---

<!-- .slide: data-menu-title="Wat is er op de markt?" -->
## Wat is er op de markt?

en wat kun je zelf?

note:

Overgeleverd aan een leverancier of zelf in controle?

--

|              |                 Zigbee                 |              WiFi               |
| :----------- | :------------------------------------: | :-----------------------------: |
| Manufacturer | Philps Hue, Ikea TR&Aring;DFRI, Xiaomi | Sonoff, Shelly, Tuya, Espressif |
| Controller   |           on premise, cloud            |        app, cloud based         |
| Modification |  DeConz/Conbee, Zigbee2MQTT, Tasmota   |        Tasmota, ESPHome         |

---

<!-- .slide: data-menu-title="KlikAanKlikUit set" -->
## KlikAanKlikUit set

![KlikAanKlikUit](images/kaku-set.png)

--

<!-- .slide: data-menu-title="KlikAanKlikUit set" -->
## KlikAanKlikUit

|                                                |                                              |                                                  |                                  |
| :--------------------------------------------: | :------------------------------------------: | :----------------------------------------------: | :------------------------------: |
| ![KAKU schakelaar](images/kaku-schakelaar.png) | ![KAKU bediening](images/kaku-bediening.png) | ![KAKU Control Station](images/kaku-octopus.png) | ![KAKU app](images/kaku-app.png) |
|                    **Lamp**                    |                **Bediening**                 |               **Control Station**                |             **App**              |

note:

Multiprotocol gateway:

- Aansturing Hue gateway via Zigbee
- Default RF-protocol
  - 433 MHz, 868 Mhz

--

<!-- .slide: data-menu-title="KlikAanKlikUit characteristics" data-background-image="images/kaku_bg.png" data-background-opacity="0.1"-->
## KlikAanKlikUit kenmerken

- Protocol: RF (433 en 868 MHz)
- Groeiend assortiment
- Integratie met Philips Hue via gateway
- Geen API's, gesloten eco-systeem
- RF technologie, "fire-and-forget"

--

<!-- .slide: data-menu-title="KlikAanKlikUit integrations" data-background-image="images/diy_rf-link_gateway.png" data-background-opacity="0.2"-->
## KlikAanKlikUit integratie met RFLink

- [How to connect Home Assistant & KlikaanKlikuit](https://medium.com/@renesijnke/how-to-connect-home-assistant-klikaanklikuit-kaku-492f8e7fdf4a)
- [RFLink Gateway](http://www.rflink.nl/blog2/)

---

<!-- .slide: data-menu-title="Philips Hue" -->
## Philips Hue

|                                  |                                      |                                |
| :------------------------------: | :----------------------------------: | :----------------------------: |
| ![Hue lamp](images/hue_lamp.png) | ![Hue Bridge](images/hue_bridge.png) | ![Hue App](images/hue_app.png) |
|             **Lamp**             |              **Bridge**              |            **App**             |

--

<!-- .slide: data-menu-title="Philips Hue characteristics" data-background-image="images/philips-hue-logo.png" data-background-opacity="0.2"-->
## Philips Hue kenmerken

- Protocol: Zigbee
- Integraties met HomeKit, Alexa en Google Assistant
- Groeiend "exclusief" assortiment
- Eigen gateway
- Alternatieve Zigbee gateways mogelijk
  - Deconz/Cponbee, Tasmota of Zigbee2MQTT

--

<!-- .slide: data-menu-title="Philips Hue" data-background-image="images/philips-hue-logo.png" data-background-opacity="0.2"-->
## Philips Hue LivingColors


- [2.4 Ghz device in RFLink device list](http://www.rflink.nl/blog2/devlist)
- [LivingColors 1st generation](http://www.knutsel.org/2009/01/01/livingcolors-1st-generation/)

---

<!-- .slide: data-menu-title="Ikea TR&#x00C5;DFRI" -->
## Ikea TR&Aring;DFRI

|                                    |                                          |                                  |
| :--------------------------------: | :--------------------------------------: | :------------------------------: |
| ![IKEA lamp](images/ikea_lamp.png) | ![IKEA Gateway](images/ikea_gateway.png) | ![IKEA app](images/ikea_app.png) |
|              **Lamp**              |               **Gateway**                |             **App**              |

note: å = &#x00E5;, Å = &#x00C5;

--

<!-- .slide: data-menu-title="Ikea characteristics" data-background-image="images/Ikea-logo-bg.png" data-background-opacity="0.1"-->
## Ikea kenmerken

- Protocol: Zigbee
- Integraties met HomeKit, Alexa en Google Assistant
- Groeiend "betaalbaar" assortiment
- Eigen gateweay
- Alternatieve Zigbee gateways mogelijk
  - Deconz/Conbee, Tasmota of Zigbee2MQTT

---

<!-- .slide: data-menu-title="Xiaomi" -->
## Xiaomi

|                                             |                                             |                                      |
| :-----------------------------------------: | :-----------------------------------------: | :----------------------------------: |
| ![Xiaomi sensor](images/xiaomi_sensors.png) | ![Xiaom gateway](images/xiaomi_gateway.png) | ![Xiaomi app](images/xiaomi_app.png) |
|                 **Sensors**                 |                 **Gateway**                 |               **App**                |

--

<!-- .slide: data-menu-title="Xiaomi characteristics" data-background-image="images/xiaomi_logo_bg.png" data-background-opacity="0.1" -->
## Xiaomi kenmerken

- Protocol: Zigbee
- Standaard Chinese Cloud
- Grote Chinese speler
- Sensoren, Switches, IP Camera, Doorbell
- Alternatieve Zigbee gateways mogelijk
  - Deconz/Conbee, Tasmota of Zigbee2MQTT

---

<!-- .slide: data-menu-title="Tado&deg;" -->
## Tado&deg;

|                                                       |                                                             |                                               |                                       |
| :---------------------------------------------------: | :---------------------------------------------------------: | :-------------------------------------------: | :-----------------------------------: |
| ![Tado&deg; Thermostaat](images/tado_thermostaat.png) | ![Tado&deg; radiator kraan](images/tado_radiator_kraan.png) | ![Tado&deg; gateway](images/tado_gateway.png) | ![Tado&deg; app](images/tado_app.png) |
|                    **Thermostaat**                    |                          **Kraan**                          |                  **Gateway**                  |                **App**                |

--

<!-- .slide: data-menu-title="Tado&deg; characteristics" data-background-image="images/tado_logo_bg.png" data-background-opacity="0.2"-->
## Tado&deg; kenmerken

- Protocol: 6LoWPAN (868 MHz, IPv6)
- Germany based company
- Amazon Cloud
- "Smart Heating"
- Focus op efficiente verwarming
- Warmte "zones" (eigen thermostaatkranen)
- Integraties met HomeKit, Alexa en Google Assistant

note:

Roomba, stofzuiger is een andere "specialist"

---

<!-- .slide: data-menu-title="Sonoff" -->
## Sonoff

|                                            |                                        |                                      |
| :----------------------------------------: | :------------------------------------: | :----------------------------------: |
| ![Sonoff switch](images/sonoff_switch.png) | ![Sonoff lamp](images/sonoff_lamp.png) | ![Sonoff app](images/sonoff_app.png) |
|               **Schakelaar**               |                **Lamp**                |               **App**                |

note:

Smart ON/OFF
[iTead.cc](https://itead.cc/smart-home.html)
Flashen met Tasmota

--

<!-- .slide: data-menu-title="Sonoff characteristics" data-background-image="images/sonoff_logo.png" data-background-opacity="0.1" -->
## Sonoff kenmerken

- Protocol: WiFi
- Standaard Chinese Cloud
- Switches met en zonder verbruiks gegevens, lampen, wandschakelaars
- Firmware aanpasbaar (Tasmota)

--

<!-- .slide: data-menu-title="Sonoff fail" -->

## Sonoff fail

![Sonoff fail](images/sonoff_fail.png)

---

<!-- .slide: data-menu-title="Shelly"  -->
## Shelly

|                                             |                                        |                                      |
| :-----------------------------------------: | :------------------------------------: | :----------------------------------: |
| ![Shelly switch](images/shelly1_switch.png) | ![Shelly lamp](images/shelly_lamp.png) | ![Shelly app](images/shelly_app.jpg) |
|                 **Switch**                  |                **Lamp**                |               **App**                |

note:

[shelly.cloud](https://shelly.cloud)

--

<!-- .slide: data-menu-title="Shelly characteristics" data-background-image="images/shelly_logo_bg.png" data-background-opacity="0.1" -->
## Shelly kenmerken

- Protocol: WiFi
- Shelly Cloud optional
- Groeiend assortiment
- Kleine inbouw WiFi schakelaars
- Firmware aanpasbaar(Tasmota)
- MQTT-support, out of the box

---

<!-- .slide: data-menu-title="LSC (Tuya)" data-background-image="images/action_logo.png" data-background-opacity="0.2" -->
## LSC (Tuya)

|                                  |                                  |                                |
| :------------------------------: | :------------------------------: | :----------------------------: |
| ![LSC Plug](images/lsc_plug.png) | ![LSC lamp](images/lsc_lamp.png) | ![LSC app](images/lsc_app.jpg) |
|           **Stekker**            |             **Lamp**             |            **App**             |

--

<!-- .slide: data-menu-title="LSC (Tuya) characterisatics" data-background-image="images/action_logo.png" data-background-opacity="0.2" -->
## LSC (Tuya) kenmerken

- Protocol: WiFi
- Verkoop bij Action
- Voordelig
- Firmware aanpasbaar (Tasmota)
  - Let op: niet alle devices zijn te flashen

--

<!-- .slide: data-menu-title="LSC (Tuya) firmware" data-background-image="images/action_logo.png" data-background-opacity="0.2" -->
## LSC (Tuya) firmware

![Tuya flashable devices](images/action_tuya_devices.jpeg)<!-- .element height="90%" width="90%" -->

[Tuya-Convert](https://www.heise.de/ct/artikel/Tuya-Convert-Escaping-the-IoT-Cloud-no-solder-needed-4284830.html)

[Tasmota templates](https://templates.blakadder.com)

---

<!-- .slide: data-menu-title="Works with ... (voice)" -->
## Works with ... (voice)

![Voice assist](images/voice-assist.png)

--

<!-- .slide: data-menu-title="Works with Alexa" data-background-image="images/amazon_echo.png" data-background-opacity="0.4" -->
## Works with Amazon

![Alexa](images/alexa.png)<!-- .element height="90%" width="90%" -->

--

<!-- .slide: data-menu-title="Google Assistant" data-background-image="images/google_smart_speaker.png" data-background-opacity="0.4"-->
## Works with Google

![Google Assistant](images/google_assistant_with_nest.png)<!-- .element height="90%" width="90%" -->

--

<!-- .slide: data-menu-title="Apple Homekit" data-background-image="images/siri.png" data-background-opacity="0.2" -->
## Works with Apple

![Apple HomeKit](images/apple_homekit.png)<!-- .element height="50%" width="50%" -->

note:
Siri
Homekit
AppleTV
iPhone
Hue

GitHub OpenSource

---

<!-- .slide: data-menu-title="Opties" -->
## Opties: controle vs gemak

- WiFi: leveranciers firmware of eigen?
- Zigbee: leveranciers gateway of eigen?
- DIY / Zelfbouw

note:

Wat zijn de mogelijkheden?

--

|              |              WiFi               |                 Zigbee                 |
| :----------- | :-----------------------------: | :------------------------------------: |
| Manufacturer | Sonoff, Shelly, Tuya, Espressif | Philps Hue, Ikea TR&Aring;DFRI, Xiaomi |
| Controller   |        app, cloud based         |           on premise, cloud            |
| Modification |        Tasmota, ESPHome         |  Deconz, Conbee, Zigbee2MQTT, Tasmota  |

---

<!-- .slide: data-menu-title="WiFi firmware" -->
## WiFi firmware vervangen

Twee opties:

- Fysiek
- OTA

--

<!-- .slide: data-menu-title="Tasmota" -->
## Tasmota

![Tasmota logo](images/tasmota-logo.svg)<!-- .element height="50%" width="50%" -->

[Tasmota documentation](https://tasmota.github.io/docs/#/)

[Tasmota template list](https://templates.blakadder.com/index.html)

note:

Theo Arends

Templates bevatten de specifieke device informatie

--

<!-- .slide: data-menu-title="ESPHome" -->
## ESPHome

![ESPHome logo](images/esphome.svg)

[ESPHome](https://esphome.io/)

note:

Home Assistant integratie

---

<!-- .slide: data-menu-title="Zigbee gateway vervangen" -->
## Zigbee gateway vervangen

Twee opties:

- Gateway kant en klaar kopen
- Gateway onderdelen kopen

--

<!-- .slide: data-menu-title="Conbee" data-background-image="images/phoscongw.png" data-background-opacity="0.2" -->
## Conbee

Conbee, the universal Zigbee USB gateway
![Conbee](images/conbee.jpg)


[Phoscon / Conbee](https://phoscon.de/en/conbee)

Kosten: 40 euro, snelle levering

note:

Complete omgeving

--

<!-- .slide: data-menu-title="Zigbee2mqtt" -->
## Zigbee2mqtt

![Zigbee2mqtt logo](images/zigbee2mqtt-logo.png)

[GitHub/KoenKK/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt)

[Zigbee2mqtt Documentatie](https://www.zigbee2mqtt.io)

CC2531 USB sniffer, debugger etc.

Kosten: 18 euro, lange levertijd

note:

Onderdelen kopen, hardware flashen met extra hardware.
7 euro voor  Sniffer en extra kabel
11 euro voor de flash hardware

beware: limited number of zigbee devices, [further reading](https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator)

--

<!-- .slide: data-menu-title="Tasmota Zigbee" -->
## Tasmota Zigbee

"Zigbee2mqtt rewrite to make it fit on an ESP82xx"

![Tasmota logo](images/tasmota-blue-logo.svg)<!-- .element height="50%" width="50%" -->

[Documentation](https://tasmota.github.io/docs/#/Zigbee),
[Device Compatibility Repository](https://zigbee.blakadder.com/zigbee2tasmota.html)

CC2530 device + Wemos

Kosten: 10 of 12 euro, lange levertijd

note:

Onderdelen kopen, hardware flashen met extra hardware.
5 of 7 euro voor de Sniffer
2 ero voor de kabel
3 euro voor de Wemos

beware: limited number of zigbee devices, [further reading](https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator)

---

<!-- .slide: data-menu-title="DIY / Zelfbouw" -->
## DIY / Zelfbouw

--

<!-- .slide: data-menu-title="Espressif: ESP8266 & ESP32" data-background-image="images/ESP8266.jpg" data-background-opacity="0.1" -->
## Espressif: ESP8266 & ESP32

[ESP8266](https://nl.aliexpress.com/item/32958591238.html) WiFi + IO ~ 3 euro

[ESP32](https://www.aliexpress.com/item/33057018346.html) WiFi + BLE + IO ~ 5 euro

[ESP32 met camera](https://nl.aliexpress.com/item/4000339060257.html) ~ 6 euro

![ESP 32 met cam](images/ESP32_cam.png)<!-- .element height="20%" width="20%" -->

via Ali Express of Banggood

---

<!-- .slide: data-menu-title="Domoticz" -->
## "The one to rule them all ..."

![the_one_to_rule_them_all.png](images/the_one_to_rule_them_all.png)<!-- .element height="50%" width="50%" -->

--

<!-- .slide: data-menu-title="Domoticz" -->
## Domoticz

![Domoticz](images/domoticz.png)<!-- .element height="30%" width="30%" align="left" -->

- [domoticz.com](https://www.domoticz.com)
- OpenSource
- Loopt een beetje achter
- Extra functies door plugins
- Community wordt kleiner

--

<!-- .slide: data-menu-title="openHAB" -->
## openHAB

![openHAB](images/openhab.png)<!-- .element height="30%" width="30%" align="left" -->

- [openhab.org](https://www.openhab.org)
- OpenSource
- Robuust
- Sterke (Duitse) community
- Ontwikkelingen gaan langzaam
- Minder flexibel

--

<!-- .slide: data-menu-title="Home Assistant"  -->
## Home Assistant

![Home Assistant](images/home_assistant_logo.svg)<!-- .element height="30%" width="30%" align="left" -->
- [home-assistant.io](https://www.home-assistant.io)
- OpenSource
- "New cool kid"
- Snelst groeiende community
- Eenvoud is het motto
- Extra functies door plugins
- Snelle ontwikkelingen

note:
[Home Assistan.io](https://www.home-assistant.io)

---

<!-- .slide: data-menu-title="Home Assistant in depth" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## Home Assistant in depth

![Home Assistant](images/home_assistant_logo.svg)<!-- .element height="50%" width="50%" -->

--

<!-- .slide: data-menu-title="HA-Installatie" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## HA-Installatie

- Hassbian (on Raspberry Pi)
- Hass.io (on Raspberry Pi, Intel NUC, VM)
- Hass.io (on Ubuntu / Debian)
- Docker
- Linux/Mac-Python Virtual Environment
- Windows-Python Virtual Environment

[Home Assistant Install Methods Comparison Matrix](https://docs.google.com/document/d/1KJKfaigHbOQylUUAzCc1wUy70FdTGRFE61HXamgAb-Q/edit)

note:

[Home Assistant Install Methods Comparison Matrix](https://docs.google.com/document/d/1KJKfaigHbOQylUUAzCc1wUy70FdTGRFE61HXamgAb-Q/edit)

--

<!-- .slide: data-menu-title="HACS" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## HACS

Home Assistant Community Store

![HACS](images/hacs-logo.svg)<!-- .element height="40%" width="40%" align="left" -->

[hacs.xyz](https://hacs.xyz)

note:

[HACS](https://hacs.xyz)

--

<!-- .slide: data-menu-title="Home Assistant - Overview" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## Home Assistant - Overview

![Home Assistant overview](images/my_ha_overview.png)<!-- .element height="70%" width="70%" -->

--

<!-- .slide: data-menu-title="Home Assistant Demo" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## Home Assistant - Slaapkamer

![Home Assistant overview](images/my_ha_slaapkamer.png)<!-- .element height="90%" width="90%" -->

--

<!-- .slide: data-menu-title="Home Assistant Demo" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## Home Assistant Demo

---

<!-- .slide: data-menu-title="Hoe begin je?" data-background-image="images/swimmer-on-starting-block-cropped.jpg" data-background-opacity="0.4" -->
## Hoe begin je?

- Doel: wat is het, dat je wil bereiken? <!-- .element: class="fragment" data-fragment-index="1" -->
- Inventarisatie: wat heb je nu? <!-- .element: class="fragment" data-fragment-index="2" -->
- Analyse: wat onbreekt er nog? <!-- .element: class="fragment" data-fragment-index="3" -->
- Planning: maak een plan <!-- .element: class="fragment" data-fragment-index="4" -->
- Actie:<!-- .element: class="fragment" data-fragment-index="5" -->
  - middelen<!-- .element: class="fragment" data-fragment-index="6" -->
  - kennis<!-- .element: class="fragment" data-fragment-index="7" -->
  - aan de slag!<!-- .element: class="fragment" data-fragment-index="8" -->

---

<!-- .slide: data-menu-title="Aan de slag" data-background-image="images/we-can-do-it-rosie-the-riveter.jpg" data-background-opacity="0.4" -->
## Aan de slag

--

<!-- .slide: data-menu-title="Installeer Home Assistant" data-background-image="images/home-assistant-bg.png" data-background-opacity="0.4" -->
## Installeer Home Assistant

![Home Assistant](images/home_assistant_logo.svg)<!-- .element height="50%" width="50%" -->

[Install Methods Comparison Matrix](https://docs.google.com/document/d/1KJKfaigHbOQylUUAzCc1wUy70FdTGRFE61HXamgAb-Q/edit)

--

<!-- .slide: data-menu-title="DIY Temperature sensor" data-background-image="images/wemos-dht-shield.png" data-background-opacity="0.1"-->
## DIY Temperatuur sensor

Wemos D1 mini

DHT temperatuur sensor

EspHome of Tasmota

note:

Wemos met temperatuur sensor laten zien.

--

<!-- .slide: data-menu-title="DIY Smart doorbell" -->
## DIY Slimme Deurbel

![Smart doorbell](images/diy-smart-doorbell-test-bench.png)<!-- .element height="70%" width="70%" -->

[Smart doorbell for just $2](https://frenck.dev/diy-smart-doorbell-for-just-2-dollar/)

--

<!-- .slide: data-menu-title="Flash Tasmota firmware on lamp" -->
## Flash lamp met Tasmota

![Tasmota FLB04](images/tasmota-flb04.png)<!-- .element height="20%" width="20%" -->

Flash een LSC lamp van de Action met [Tuya - Convert](https://www.heise.de/ct/artikel/Tuya-Convert-Escaping-the-IoT-Cloud-no-solder-needed-4284830.html)

note:

Demo Tasmota interface op LSC (Action) lamp

---

<!-- .slide: data-menu-title="Lessons learned" -->
## Lessons learned

- Begin klein
- Plan je tijd (keer 3)
- Omarm Murphy's law
- Beperk de externe afhankelijkheden
- Zorg voor een fall-back scenario
- Houdt rekening met de "PAF"
- Je kunt meer dan je denkt (met een beetje hulp)

note:
PAF = Parter Acceptance Factor

--

<!-- .slide: data-menu-title="Vragen" data-background-image="images/questionmarks.jpg" data-background-opacity="1.0" -->


---

<!-- .slide: data-menu-title="That's all folks" data-background-image="images/Thats_all_Folks.jpg" data-background-opacity="1.0" -->
