**rpitx10** Radio frequency transmitter for x10 rf devices

this uses librpitx to transmit more info at 
https://github.com/F5OEO/rpitx and
https://github.com/F5OEO/librpitx



# Installation

```sh
git clone https://github.com/chaos511/rpitx10
cd rpitx10/src
make
cd ../app
make
```
Connect a wire to GPIO 4 for a antenna

# Usage

```sh
cd librpitx/app
sudo ./x10_send <housecode> <unitcode> <command>
```
Housecode: A-P
Unitcode: 1-16
Command : ON, OFF, DIM, BRIGHT

# Example
```sh
sudo ./x10_send A 4 ON
```
