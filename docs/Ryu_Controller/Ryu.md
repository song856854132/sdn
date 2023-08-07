---
layout: default
title: Ryu_Controller
nav_order: 2
has_children: true
permalink: /docs/Ryu_Controller
---

# Components
```shell=
ryu
├── app
├── base
├── cfg.py
├── cmd
├── contrib
├── controller
├── exception.py
├── flags.py
├── hooks.py
├── __init__.py
├── lib
├── log.py
├── ofproto
├── services
├── tests
├── topology
└── utils.py
```
## base
### ryu.base.app_manager
Q: What does this component do?
A: The central management of Ryu applications.
- Load Ryu applications
- Provide `contexts` to Ryu applications
- Route messages among Ryu applications

class RyuApp
-> base class for Ryu applications.
-> specify OFP version

class AppManager
-> singleton pattern for global usage??? what that mean??


## controller

## application

## ofproto

## lib

## third-party

