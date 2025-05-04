---
title: cleep-desktop
date: 2025-05-03
draft: false
# series: ['tools']
# series_order: 4
---

## Introduction

Cleep project provides full continuous integration to automatize delivery process.

Code quality is focused during continuous integration. Some criteria are mandatory about code quality and confidence before application publication.
The main goal of this is to guarantee application market contains quite good applications.

{{< alert icon="circle-info" >}}
For now CI is not opened to public. We planned to develop web application to create developer account and get access to the CI results. But before we need to create a community and then, dependending of community enthusiasm we'll spend time to create it.
{{< /alert >}}

## CI features

### For application

- Version check
- Installation on fresh Cleep environment (latest core version)
- Source code validation (generate a code quality note)
- Breaking changes detection
- Unit tests execution (generate a ode confidence note)
- Code coverage publication
- Api documentation generation and publication
- Publication on Cleep application market

### For core

- Version check
- Installation on fresh Cleep environment (latest core version)
- Unit tests execution
- Code coverage publication
- Api documentation generation and publication
- Package publication
- New CleepOS generation and publication if necessary (new release)
