## Research Phase (Mostly done along the way)
Learn some more detail about the separate processes which will be integrated into one program

- Text → Netlist (LLMs like ChatGPT/SKiDL).

- Netlist → PCB Layout (KiCad).

- PCB → 3D Model (KiCad STEP export).

- 3D Model → Enclosure (FreeCAD/Fusion 360).

## Implementation Phase

- Python will be used to tie all the programs together (Spyder IDE)

- Python script will send text to a LLM, the results of which would be converted to a KiCad netlist

- KiCad built-in Python API pcbnew will be used for next step, netlist file will be loaded, footprints will be placed in a grid, and then exported to 
- 
