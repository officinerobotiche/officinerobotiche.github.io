---
title: "#003 IR Blaster"
excerpt: "La presentazione dell’IR Blaster, un telecomando a infrarossi a larga copertura per controllare dispositivi da remoto via WiFi"
header: 
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/or-aperitech/2020-07-01-or-aperitech-ir-blaster/ir-blaster-teaser.jpg
    teaser: /assets/or-aperitech/2020-07-01-or-aperitech-ir-blaster/ir-blaster-teaser.jpg
categories:
  - OR-Aperitech
tags:
  - ir
  - mqtt
  - http
  - node-red
  - openhab
  - gianluigi
---

Il progetto vede una collaborazione tra [SettoreZero](https://www.settorezero.com/) e OfficineRobotiche.

Questo circuito nasce dall’esigenza di collegare i dispositivi controllabili con telecomandi infrarossi al **sistema di automazione domestico**. Si tratta quindi di un bridge tra IR e protocollo **MQTT** o **HTTP** con un notevole **raggio di copertura**.

L’utilizzo principale di questo telecomando è via MQTT perchè consente di interfacciarlo ai sistemi domotici che fanno uso di **Node-RED**, **OpenHAB** e simili, ma nulla vieta di utilizzarlo via HTTP fornendo dei parametri nell’url da richiamare, magari realizzando un’app o una pagina HTML.

{% include video id="Nxys9f37a3w" provider="youtube" %}
