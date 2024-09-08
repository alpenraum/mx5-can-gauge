
# mx5-can-gauge

Config of [Gauge.S by Sorek.uk](https://github.com/handmade0octopus/gauge.s-sorek.uk) for ND MX-5 using the car's CAN network.

  

**THIS IS VERY MUCH WORK IN PROGRESS**

  

## Resources

- https://github.com/timurrrr/RaceChronoDiyBleDevice/blob/master/can_db/mazda_mx5_nd.md
- https://docs.google.com/spreadsheets/d/1uqwIMof9DdaEv0EkWHXe70XNGt0FGeDxpbMAgfKbbdk/edit?gid=0#gid=0
- https://www.mx5-nd-forum.de/forum/thread/7187-tpms-data-through-obd-ecu/?pageNo=1
- https://github.com/majbthrd/MazdaCANbus/blob/master/skyactiv.kcd
- https://github.com/Viaszx/Mazda-SkyActiv-EngineCoolantTemp/blob/main/can/can.c -> fetches skyactiv coolant temp from id 0x420

  

## Encyclopedia

  

| Key | Meaning |

| ------- | ------------ |

| sleepTime |time in seconds until the Gauge shuts down, is reset after every interaction (**TODO**: CHECK HOW IT REACTS IN CAR WITH OBD SIGNALS) |
