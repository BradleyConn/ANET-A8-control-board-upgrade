# ANET-A8-control-board-upgrade
## Marlin Configuration
I relied heavily on [this]( https://caggius.wordpress.com/anet-a8-skr-v1-3-and-marlin-2-0-x/) website to perform the upgrade. I started with those configuration files and made some edits which should mostly be marked with a "BC:".

I did face issues with apparent motor skips which were fixed by increasing the powers to the motor drivers.

## Adapter cables
Cables are needed to interface the wires of the ANET-A8 to the Big Tree Tech (BTT) SKR v1.4 control board, while maintaining backwards compatibilty. The connectors and pinout vary between boards. The website mentioned above has documentation for this.
