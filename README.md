# nRF52840_enable_reset_pin
Forth code to enable a reset pin on the nRF52840
The code is general purpose but includes a specific example of how to enable the reset button on the nRF52840-DK.  The code only needs to be run once, because the change is made to non-volatile memory on the chip and therefore the change will persist unless the nRF52840 is either bulk erased or deliberately changed again.
