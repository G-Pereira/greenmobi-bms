# VESC BMS - A BMS board compatible with the VESC project and BMS firmware

The VESC BMS board system is under closed development at the time of this writing although the BMS firmware is publicly available so this project consists on a VESC compatible BMS board that runs VESC BMS firmware.

This project is under development and the board is not yet ready and contributions are welcome. [KiCAD v6](https://www.kicad.org/) is being used for the board's design.

## Desing approach

Since there is not yet a opensource design of a VESC compatible BMS and only a commercial product was found form MAXKGO (which has its own firmware) this board is being designed with ease of development in mind. So the following principles are followed:

- Popular and easy to source connectors are used (JST XH, scre terminals, etc) even if in most end uses it would be better to have weatherproof panel connectors.
- QFN and BGA chips are avoided at all costs to ease hand assembly.

## Contributions

Since the design is at a schematic phase, it would be helpful if you can review the board's schematic to look for misconnections and erros using any of the given ICs. However, any other kind of productive feedback and work is welcome.