---
title: Project
date: 2025-05-03
draft: false
---

## History

In 2012, I participated of the Ago-Control home automation controller developments for 4 years. Ago-control wanted to be as generic as possible to handle in the same way all existing devices, no matter the device protocol. In my opinion, the more generic an application is, the more complex it is to use.
During that time, I helped to develop a lot of parts of this project: a security plugin, an RPC server, a Z-Wave protocol application, a MySensors application... and started to understand how everything is working together.

## The situation

During those years, I was facing some issues:

- Some new IoT protocols, like Z-Wave or ZigBee, were moving really fast at this time, and devices I bought quickly became obsolete due to hardware evolution. Devices still worked thanks to new protocol version compatibility, but they suffered from a lack of security, performance...
- I also experienced bad communication with those protocols, and I was not really convinced, particularly with security devices (motion sensors). What happens if a security device encounters a communication issue during a robbery? :-(
- Some manufacturers stopped producing some kind of their products, and existing devices became unmaintained (for example, Squeezebox from Logitech, Google Home Assistant displays...). So I spent money for nothing? What is the ecological impact on that... and for my wallet...?
- The prices of Z-Wave devices approached 60€. So to equip my house, I will have had to contact my bank advisor (just kidding, but it cost a lot of money for how many years ?).
- After MySensors plugin development, I started to build my own sensors to reduce the cost of my sensors. I took generally more than 2 hours to build a simple sensor sensor (hardware + software pieces). So I was really frustrated to take so much time to do that. At this time the protocol doesn't allow OTA updates, so it was difficult to perform updates.
- Generic home automation software like Ago-Control was dedicated to people that work in IT. I mean, the complexity of making scenarios is not something everybody can understand without experience.

## Birth of ideas

So strong from encountered problems, I decided to start something new, focusing the project on those main purposes:

- Simplicity: the project should be able to provide a solution to reduce the complexity of IoT developing simple applications with as little configuration as possible.
- Recycling: the project should be based on generic and cheap hardware that could allow software evolution to change the main purpose of the device.
- Standard communication: the project should be based on well-known wireless technology that everybody has in his house, the Wifi. If communication troubles occurred, it is acceptable to buy another Wi-Fi router that will serve for other house devices (phone, tablet...). Security is also performed by the Wi-Fi itself, so that's one less problem.

## The solution

I decided that Raspberry Pi board was really good and stable platform to use:

- This hardware already implements Wi-Fi connection without the need of adding something else.
- The power of the board was enough for most simple usage. If something powerful is necessary (motion detection for example), it is possible to buy a more powerful board version.
- The Raspberry Pi environment is really rich in hardware components (named HAT). The board has by default a lot of inputs and outputs (called GPIOs) ideal for makers.
- The organization behind the Raspberry Pi makes a really good job on application maintenance. So the environment is really stable.

So Raspberry pi was definitely the best choice.

For the software part, I decided to use Python which is one of the most used programmation langage. It is also the langage teached at school. For the graphic part I based my software on angularJS which was one of the most popular at this time.

## The beginning

In 2016, I finally started to develop the project. During the first time it was a project for myself only, but after talking about it with my friends, they convinced me that it should be a great idea to share.
