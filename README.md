# SBC09-CPU_X-3_rev-2

Simple SBC design around MC6809 Revision 2

This was the fist atemp/test to make a full SBC system based on my old
modem X-3 construction.

This was done during Christmas weekend 2024.
To test my simple & basic setup, to start expermenting.

My goal is to have an uncomplex build
* but not with a few large ICs
* not with PAL/GAL

So my setup is:
* CPU: MC6809
* MEM: 6x HM6264ALP-15
* ROM: 2764 eq EPROM / EEPROM
* PTM: MC6840
* ACIA: 2x MC6850
* ACIA: R6551
* PIA: 3x MC6821
* Glue logic:
  * 74HCT04
  * 74HCT138
  * <del>74HCT154</del> 74HCT138

My testing setup:
![PCB in case](https://github.com/RlinkSystem/SBC09-CPU_X-3_rev-2/blob/e1f1b1ddd3a8c246b288238bed58164f2a0f0caa/CPU_X-3_r2_box.jpeg)
