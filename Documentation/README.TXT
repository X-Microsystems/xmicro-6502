All files are for XMICRO-6502 V2.3.

V2 was a quick re-spin of the XMICRO-6502 card to use the new IOSEL signal added to the bus. At this time, the bank switching circuit was modified and a clock divider was added. Other changes from V1 were insignificant.
V2.3 added Schmitt-trigger inputs for the !BRST and !BWAIT signals. Wait states were fixed by manipulating the clock source instead of using the CPU's RDY input - keeping the bus stable during a wait state.
V2.4 made it necessary to manually clear DMA interrupts by reading $X01.
