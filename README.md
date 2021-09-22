# Time_Measurement

This repository defines a package gathering software elements allowing to measure time on an
embedded software.

The package is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model) and implemented
according to [these C language
patterns](https://github.com/HomeMadeBots/C-language-patterns-for-Embedded-Software-Meta-Model).

## Content

The Arduino_Pins package gathers :
* Data_Types :
  * E_Day
* Interfaces :
  * Clock_Data
  * Clock_Setting
* Component_Types :
  * Clock

## Overview

![Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Time_Measurement/master/doc/overview.puml)

## Dependencies

![Packages dependencies](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Time_Measurement/master/doc/dependencies.puml)

The following repository shall be retrieved :
* [Embedded_C_Framework](https://github.com/HomeMadeBots/Embedded_C_Framework)

## Use

### With the Arduino IDE

This repository shall be clone within the _libraries_ folder of the _Arduino sketchbook folder_.