---
sidebar_position: 3
---

# Configuration

Both application CompuTec Labels and CompuTec Gateway have to be configured. Communication flow as explained below:

1. Label request has been triggered through some application,
2. Label request has been processed by CompuTec Label Service/Manager,
3. CompuTec Label Service determines that assigned printer is a gateway printer,
4. CompuTec Label Service sends detail of request to Gateway Machine through AppEngine address and port(by CompuTec Gateway Plugin),
5. After CompuTec Gateway Service on targer machine received the request, it processes the request and sends print request into printer queue,
6. Print out on physical printer.

## Configuration on CT Label Manager

Configuration should be done on CT Label Manager is adding Gateway type printer and entering AppEngine address as shown below:

CompuTec Gateway application can be download from [here](https://computec-docs.pages.dev/pdc/administrator-guide/weight-scales-integration/gateway-service-installation).
<!-- TODO: Replacement above Link to path -->

## Configuration on CT Gateway Application

CompuTec Gateway application installation guide can be found [here](https://computec-docs.pages.dev/pdc/releases/downloads#computec-gateway-service).
<!-- TODO: Replacement above Link to path -->