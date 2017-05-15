# MdMs
MySensors 6 Button Node

Focus on the use with the library MySensor

License: CERN Open Hardware License 


#Technical Specification
- Small footprint, 24 mm x 36 mm
- Arduino IDE 1.6.x compatible.
- 64kb SPI flash / e2prom onboard. Useful for over-the-air firmware updates. Also possible to use memory for a local sensor data cache.
- ATSHA204A on board (connected to A3). Used for HMAC-SHA256 message authentication support
- On board battery holder CR2032
- SMD radio module NRF24/RFM69
- Small program connector
- Status LED
- Inclusion button
- Factory programmed with DualOptiBoot bootloader.

#Available pins
- 6 buttons
- Programming connector