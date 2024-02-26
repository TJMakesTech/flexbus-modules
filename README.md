# Flexbus - Performant Electronics Modules for Under 1 USD

### Every electronics product and project can be reduced to a set of basic individual functions. 

These functions can be things like sensors (temperature, voltage, cameras), actuators (motors, solenoids), interfaces (displays, switches) and communications (2.4GHz radio, WiFi, LoRa).

These days, the vast majority of these functions can be achieved by components costing less than 1USD, and using standard power levels and interfaces such as 3.3V I2C.

These components are also power optimised, and often have supporting libraries for arduino (or similar) available.

### Existing Hobby or Enthusiast electronics modules are often $30+ for these functions, and do not maintain satisfactory levels of power performance for deployed products. 

The cost and poor performance of these modules are a result of their designers desire to provide something universal with many quality of life features.

But this leads many hobbyists astray when it comes to forecasting product costs, and increases the gap between personal projects and professional electronics product design.

### FlexBus modules were designed to answer the question "how many core electronics functions can be achieved for under 1USD".

This was then extended to the goal of providing a standard interface that allows for the easy daisy-chaining and generic use of these functionalities to provide the fastest, cheapest and most performant prototyping platform available.

FlexBus is built around a double-sided, 20 pin FPC Connector, GPIO Selector system, and a variety of flex cables. FPC cables are fantastic, they are low impedance, extremely cheap and reliable, and can be any shape, size and can split into multiple paths as well.

My goal is to design a new FlexBus module every week to add to my own prototyping toolkit, and provide the design files here in the spirit of open source.

Where applicable, alongside each module will be a usage guide, as well as supporting arduino code examples in order to achieve the target function.

There are now also a series of powerful Risc-V MCU's available for under 1USD, as well as a number of STM32 offerings. I intend to complete a purpose built MCU module using these platforms, however for now the seeduino XIAO product line is the MCU platform of choice. They are compact, capable and well priced.

## Completed Modules:
- I2C GPIO Expander
- 15A Power Relay
- LiPo Charger and Power Regulator

## Prototypes Ordered:
- Xiao Adapter board
- OLED Display

## Needs Refinement
-  2.4GHz Radio (NRF24L alternative).
  
## Coming Soon:
