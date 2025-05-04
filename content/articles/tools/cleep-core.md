---
title: cleep-core
date: 2025-05-03
draft: false
# series: ['tools']
# series_order: 1
---

## Introduction

cleep-core is the basis of Cleep project.

Core acts like a framework to provide standard way to create an application that will bring functionnality to the device.

It also provides some libraries to help developer to easily interact with the Raspberry pi and configure it.

![image](cleep.jpg)

## Features

### Backend

- Python 3.9
- Libraries to update Raspberry pi configuration files
- Libraries to help during developments (make task, access filesystem, unit tests helpers...)
- Libraries to execute system binaries and handle their response easily
- Internal message bus to easily communicate with other applications

### Frontend

- Based on AngularJS framework
- Components library to quickly develop pages
- Native icon library
- Library to handle requests with your application backend
- Native application lazy-loading

## CleepOS

Cleep framework is provided as ready to install .deb file and also with CleepOS image.

CleepOS image is a tuned Raspberry pi OS image with readonly OS to protect SDCard from failure.
This image has also some tweak to optimize it.

The latest CleepOS image is directly available from cleep-desktop application. You can find it [here](https://github.com/CleepDevice/cleep-desktop/releases).

If you prefer install Cleep directly on your existing Raspberry pi, you can download latest cleep package [here](https://github.com/CleepDevice/cleep/releases)

## Why AngularJS in 2025

Historically AngularJS was the framework available when the project starts in 2016.

After some reflexions about migration to a newest framework, it has been decided to keep it until it doesn't work.

The main pro of this framework is the simplicity of usage. All stuff realized with Cleep hides AngularJS complexity (lazy-loading) and for now Cleep doesn't need more.
Also the non-need to compile source code (typescript) optimizes rendering and make easy application package building.

Too, while workforce of the project are not important, we are not wasting time to refactor something that still work. But if you are motivated to bring knowledge about new framework, we are pleased to help you in that work.
