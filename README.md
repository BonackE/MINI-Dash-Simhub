# MINI Dash Simhub
 Simhub dash code for a 2002-2008 MINI dash cluster


### Requirements:
- MINI Cooper Cluster (Auxillery and Main) from 2002-2008 Gen 1 (BMW)MINI Coopers
- [Arduino IDE](https://www.arduino.cc/en/software)
- [SimHub](https://www.simhubdash.com/)
- Arduino UNO (Should not matter which REV)
- 12v Power block for cluster
- [Seeed CANbus shield](https://www.amazon.com/dp/B076DSQFXH?ref=nb_sb_ss_w_as-reorder-t1_k2_1_5&amp=&crid=1JRM0CG8IECQ5&sprefix=canbu&th=1)
- Wires, soldering kit, electrical tape, wire strippers.

#### What to do:
1. [This](https://defcon.org/images/defcon-21/dc-21-presentations/Staggs/DEFCON-21-Staggs-How-to-Hack-Your-Mini-Cooper-WP.pdf) is how to know where wires go and what CANbus IDs are used (code already has those IDs being used for Tachometer, temp, and speedometer)
2. [MINI Cooper S wiring diagram](http://wtxmc.org/MiniCooperDocs/WIRING.pdf). This is a PDF of the wiring used for the instrument cluster, CAN H and CAN L need to be the only wires used on the arduino as the dash has to be powered seperately.
3. Compile Arduino code.
4. Open SimHub to connect using 19200 baud rate.
5. Do gauge testing on SimHub.

