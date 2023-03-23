# Hello-world
Just seeing how to use github.

## State of play:

Software Issues

	- PS and PL LEDs... Work individually, but have not been included in main code.

	- Serial-Pass relay drive not implemented?

	- IN/OUT ENC - Can software-block names be matched to axes? (3 and 4 are axes 5 and 6).

	- axi_lite_slave.vhd - only a subset of the some ack lines are used (see lines 196-206 and 252-261)

	 -SFP Power-Up reset not working.  Probably due to reset_i coming from axi_reset not server startup. (clock currently comes from ST1 clock-gen which isn't set upt until kernel boots)

Hardware that isn't implemented in GUI:

	- EQU Inputs
	- AUX SPI
	- Watchdog and Abort
	- System Information (CPU Temps etc)
	- LoS inputs from Quad Decoders
  
