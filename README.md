# NSO Stack Service Example

This repo contains a very simple example on how to create an _stack_ service in NSO. An stack service usually includes 
references to other services in order to avoid duplication of XMLs and yang models. 

## Packages

The repo includes three different service packages: 

1. dns: A very simple template and python service to configure name server
2. ntp: A very simple template and python service to configure ntp server
3. common-services: A very simple template and python service that import yang definitions from the two above 
and references their XML templates.

## Installation

Just copy these folders in your package directory and you should be ready to go. Tested on 5.2.0.3, make sure to 
re-compile before doing a package reload. 

## Contacts

* Santiago Flores Kanter - sfloresk@cisco.com
