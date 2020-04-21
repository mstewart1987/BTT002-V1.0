# BTT002-v1.0-MMU2S
* The firmware of this motherboard is default Marlin2.0；
* Since the prusa machine is not equipped with endstop switch, to use the endstop switch function, either TMC2130 or TMC2209 must be used.According to the test results, using the TMC2209 driver is more cost-effective. Therefore, it is recommended that the customer use TMC2209 driver；
* If you want to use drivers other than TMC2209 and TMC2130, you need to install endstop switch on the machine；
* Because the board uses a plug drive, the overall height is higher than the original machine housing. According to the motherboard, our company makes a 3D model to adapte the shell. So the customer can printed out the shell and install on the machine for use;
* The firmware of the motherboard is updated by SD card. The client can put the compiled. bin file into the SD card of LCD2004 screen, then repower to update the firmware.
* When using Marlin firmware, you can use the new processing capabilities such as RGB light function, WIFI printing function, TFT touch screen and dual-mode touch  screen.
## Wire changes needed for MMU2S
* The green and white wires need to move over 1 spot each respectively.
   Original MMU Wiring | BTT002v1.0 TFT Wiring
   ------------------- | ----------------------
   ![Original MMU Wiring](/images/Original%20MMU.jpg) | *![BTT002v1.0 TFT Wiring](/images/Fixed%20mmu.jpeg)
* This then connects to the TFT port on the BTT002 board.
  ![Side View](/images/mmu1.jpeg)
  ![Top View](/images/mmu2.jpeg)
