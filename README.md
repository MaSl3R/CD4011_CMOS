# \# CMOS CD4011 NAND Gate – TSMC 180nm

# 

# This project implements a CMOS NAND gate used as a building block of the CD4011 logic IC.

# 

# The design includes transistor-level schematic design, SPICE simulations, layout implementation in Magic VLSI and analysis of output drive capability.

# 

# Technology: TSMC 180nm  

# Supply voltage: 1.8V

# 

# ---

# 

# \## Design flow

# 

# 1\. Transistor-level NAND gate design in SPICE

# 2\. Functional verification and operating point analysis

# 3\. Output buffer design using tapered CMOS buffer chain

# 4\. Layout implementation in Magic VLSI

# 5\. Post-layout verification

# 

# ---

# 

# \## Circuit structure

# 

# The circuit consists of:

# 

# \- CMOS NAND logic core

# \- multi-stage output buffer

# \- input protection structures

# \- bonding pads

# 

# The output buffer uses a scaling factor of 3 between stages to improve drive capability.

# 

# ---

# 

# \## Tools used

# 

# \- SPICE

# \- Magic VLSI

# 

# ---

# 

# \## Layout

# 

# (images/layout\_cd4011.png)

# 

# ---

# 

# \## Future improvements

# 

# \- parasitic extraction

# \- post-layout timing analysis

# \- delay characterization

