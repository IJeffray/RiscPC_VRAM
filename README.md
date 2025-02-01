# Acorn RiscPC 1MB/2MB VRAM module

January 2025


![3D View](Generated/RiscPC_VRAM_3D_View.PNG)

This is my implementation of the standard RiscPC 1MB/2MB VRAM module, as per schematic and board shape in the RiscPC TRM.

The design works as well as Acorn's - with the same tiny caveat that IC1 may need to be a faster part if the machine is heavily loaded - after experimentation with a number of machines and configurations, this only manifested as an issue in machines with Mk3 motherboards and the maximum possible 128+128MB main RAM, with RAMs that were probably not even correct (maybe 3v3 parts, sold as 5V!).   Acorn fitted their 2MB VRAMs with IC1 as a faster part which was apparently sufficient to consider the matter resolved.   It's unlikely (very pointless) anyone will have so much RAM installed anyway.  Also noted that when using Kinetic, the amount of RAM made no difference there, so even a machine with 128MB+64MB SIMMs, and max 256MB SODIMM on the Kinetic still functioned perfectly.

## Licence

No warranty is provided, and this work is used at your own risk.  

Licenced as CC BY-SA 4.0

Copyright 2025 Ian Jeffray

