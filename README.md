# pirate-watchdog
Arduino-based watchdog utilizing regular ICMP pings over ethernet to the target device. When pings are not answered, a powercycle is performed through a gpio pin controlling e.g. a power switch or a relay circuit. It is assumed that the Arduino Ethernet shield (or equivalent) is present.
