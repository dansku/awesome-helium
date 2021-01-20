# Awesome-Helium [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of all helium projects, tutoriais, and resources.


## Contents

- [Community](#community)
- [Software](#software)
- [Hardware](#hardware)
- [Exchanges](#exchanges)
- [Education](#education)
- [Network Operators](#network-operators)

---

## Community

* [Discord](http://discord.gg/helium) - Official Helium Community Discord; many people, very busy
* [Monthly Community Calls](https://docs.google.com/document/d/1bMm2alBigBj3detA775Dn0Gz9UM5XczAeK9vnjBB3l0/edit#) - Noon ET on the last Wednesday of the month
* [Weekly Helium Hacks Happy Hour](https://zoom.us/meeting/register/tJ0qdeyorDgqHdbWZTQhBSphsFEytiyc5BiP) - Every Wednesday at 3p PT

## Software
### Docker Miner

* [Blockchain Sync Progress Script](https://github.com/Doginal/helium-network-scripts) - Bash script to get the current progress of your Helium miner running via docker

### Development Environments

* [Leroy's Updated & Unofficial CubeCell repo](https://github.com/leroyle/ASR650x-Arduino) - Heltec ASR650x; Heavily improved.

### Explorers/Analytics/Hotspot Analysis

* [Helium Explorer](https://explorer.helium.com) Open-source helium explorer
* [Helium Network Map](https://network.helium.com)
* [Sitebot](https://sitebot.com/helium)
* [Hotspotty](https://hotspotty.net) Hotspot management platform
* [Mylar](https://mylar.app)
* [Helium Coverage Mapping](https://mappers.helium.com)
* [Cargo Live Mapper](https://cargo.helium.com/)
* [Line of sight measurement](https://www.scadacore.com/tools/rf-path/rf-line-of-sight/)
* [Helium Chain Variables](https://helium.plus/chain-vars)
* [LoRa documentation](https://lora.readthedocs.io/en/latest/)
* [Cloud-RF](https://cloudrf.com/) - RF coverage modeling and mapping utility
* [Patrium](https://patrium.app/) - Another hotspot management platform
* [Mock sensor code to send lorawan otta join](https://github.com/gradoj/sensor)
* [Helium+](https://helium.plus/) Helium hotspot earnings calculator

### Dashboards
* [Datacake.co](https://datacake.co/) Enterprise IoT platform
* Cayenne
* [Adafruit.io](https://learn.adafruit.com/welcome-to-adafruit-io) - Adafruit.io is a cloud service - that just means we run it for you and you don't have to manage it. You can connect to it over the Internet. It's meant primarily for storing and then retrieving data but it can do a lot more than just that!
* Ubidots
* Thingsboard
* [Node Red](https://nodered.org/)

### Mobile Apps

* [Unofficial Hotspot Utility](https://github.com/kent-williams/hotspot-utility) - Unofficial Android/iPhone Hotspot Utility

### DIY Hotspots

Build tutorials

* [DIY Hotspot auto update automation scripts](https://github.com/Wheaties466/helium_miner_scripts) - Wheaties466/helium_miner_scripts, automation for setting up DIY hotspots. All things DIY.
* [Helium developer docs guide](https://developer.helium.com/hotspot/developer-setup) - Pilot Gateway (sx1301-based)
* [maco2035/DiyHeliumHotspots](https://github.com/maco2035/DiyHeliumHotspots) - Collection of guides for setting up various builds
* [PastaGringo/balenaos-helium-gtw](https://github.com/PastaGringo/balenaos-helium-gtw) - BelanaCloud-based build with docker-compose
* [bottxrnife/helium-2245](https://github.com/bottxrnife/helium-2245) - Forked from PastaGringo, BelanaCloud + docker-conmpose configuration for RAK2245-based builds, like the RAK Pilot Gateway (SX1301-based chip)
* [bottxrnife/helium-2287](https://github.com/bottxrnife/helium-2287) - Above but for RAK2287-based builds, like the RAK Discover Kit 2 (SX1302-based chip)
* [just4give/helium-dyi-hotspot-balena-pi4](https://github.com/just4give/helium-dyi-hotspot-balena-pi4) - "Build your own helium hotspot ( miner + packet forwader ) on Raspberry pi 4 using BalenaOS"
* [jamiew/helium-diy-hotspot](https://github.com/jamiew/helium-diy-hotspot) - Collection of shell scripts for setting up, updating, and monitoring a DIY hotspot
* [23RoMax/h2b](https://github.com/23RoMax/h2b) - Helium DIY Hotspot Bootstrapping script with a few utilities
* [meshferg/lorawan-helium-diy-gateway_miner](https://github.com/meshferg/lorawan-helium-diy-gateway_miner ) - RAK2245 & rPi4 gateway miner collecting wetlands data
* [dansku/helium-rak833-pisupply](https://github.com/dansku/helium-rak833-pisupply) PiSupply LoRa Gateway with the RAK833 for Helium.
Video tutorials

* [Setting up a Helium miner on DigitalOcean](https://www.youtube.com/watch?v=rR2Z0vOufLM)
* [Adding a DIY Hotspot to the Helium Blockchain](https://www.youtube.com/watch?v=SzFWSv6UcIE)

### Payload Decoders

* [VolleyBoast VoBo GP1](https://github.com/VolleyBoast/Decoder) - Decodes standard payload
* [Helium Decoder Repo](https://github.com/helium/console-decoders)


## Hardware

### Hotspots

* Helium official hotspot
* [RAK Hotspot Miner](https://www.calchipconnect.com/products/rak-hotspot-miner)
* Dragino LPS8
* DIY gateway builds
* ...

### Outdoor Enclosures

* RAK Outdoor Enclosure [RAKWireless Shenzhen](https://store.rakwireless.com/products/outdoor-gateway-enclosure?variant=29748845051949), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/collections/accessories/products/outdoor-gateway-enclosure?variant=37786576781491)

### Sensor Guides and Tutorial

* [Browan TBHV110 Quickstart](https://github.com/mikedsp/helium/blob/master/MyDocuments/BrowanTBHV110_HeliumQuickStart-SHARE.pdf)
* [Browan TBHH100 Quickstart](https://github.com/mikedsp/helium/blob/master/MyDocuments/HowTo_BrowanTBHH100_to_GoogleSheet-SHARE.pdf)
* [Connect a RAK7204 to Helium and forward its data to Ubidots](https://www.hackster.io/mariacarlinahernandez/connect-a-rak7204-to-helium-and-forward-its-data-to-ubidots-073793)
* [KiCAD version of WisBlock-Sensor-RTC-Example](https://github.com/ManuIoT/WisBlock-Sensor-RTC-Example)

### Coverage Mapping

* [CubeCell Helium Coverage Mapper](https://github.com/jas-williams/CubeCell-Helium-Mapper) - Mapper using the CubeCell w/ GPS/OLED by jas-williams

### Antennas

* [OG Stock Hotspot Antenna](https://www.mouser.com/datasheet/2/238/ant-916-cw-hwr-1633319.pdf) - (pdf datasheet)
* 3dBi RAK Stock Replacement Antenna - [RAKWireless Shenzhen](https://store.rakwireless.com/collections/accessories/products/3-dbi-lora-antenna?variant=32429030637613), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/collections/accessories/products/3-dbi-lora-antenna)
* RAK 5.8dBi [RAKWireless Shenzhen](https://store.rakwireless.com/products/fiber-glass-antenna), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/products/rak-fiber-glass-lorawan-antenna-us915?variant=37264623468723)
  * [5.8 dBi Base support 3D STL File](https://www.thingiverse.com/thing:4607962)
* RAK 8dBi [RAKWireless Shenzhen](https://store.rakwireless.com/products/fiber-glass-antenna), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/products/rak-fiber-glass-lorawan-antenna-us915?variant=37563940733107)
* Nearson 9dBi
* [ANT-916-MHW-RPS-S](https://linxtechnologies.com/wp/wp-content/uploads/ant-916-mhw-fff-x.pdf) - Indoor antenna - pdf
* ...

### Cables & adapters

* ...

## Exchanges

* [Binance US](https://www.binance.us)
* [Binance](https://www.binance.com/)
* [Bilaxy](https://bilaxy.com/)
* OTC Telegram groups
* [HotBit](hotbit.io/)

## Education

 * [LoRaWAN Academy](https://lora-developers.semtech.com/resources/lorawan-academy/) - self-paced on-demand LoRaWAN training course
 * [HIP 17 Visualizer](https://hip17.helium.wtf/) - static snapshots of network state visualize the effects of HIP 17 hex density scaling

## Network Operators

Interested in hosting a hotspot? Get in touch with one of these companies:

 * [Buildmesh.io](https://www.buildmesh.io/) - 20% of HNT earnings plus $10 donation to STEM non-profit
 * [Emrit](https://emrit.io/) – 20% of HNT earnings
 * [Hostify](https://www.hostify.cc/) - New Jersey-only. $35+/monthly, $50+/referral
 * [IoWe (Internet of We)](https://www.InternetOfWe.net) - 20% Partner referrals. 50% of HNT earnings after referral [where applicable].
 * [Loris.club](https://www.loris.club) - 25% of HNT earnings
 * [ZataFi](https://zatafi.com/ShareNet/) - 50% of HNT earnings


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
