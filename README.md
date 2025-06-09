## Research Phase (Mostly done along the way)
Learn some more detail about the separate processes which will be integrated into one program

- Text → Netlist (LLMs like ChatGPT/SKiDL).

- Netlist → PCB Layout (KiCad).

- PCB → 3D Model (KiCad STEP export).

- 3D Model → Enclosure (FreeCAD/Fusion 360).

## Expermentation Phase

- Python will be used to tie all the programs together (Spyder IDE)

- Python script will send text to a LLM, the results of which would be converted to a KiCad netlist

- KiCad built-in Python API pcbnew will be used for next step, netlist file will be loaded, footprints will be placed in a grid, and then exported as a STEP to a CAD application (not decided yet)
  
- CAD application must have a built-in Python API, scripts will be used to create design, which will be imported as the output

## Integration Phase

- Knowing how each component works, they can be combined into a single Python program

- Tie up loose ends and add edge cases
