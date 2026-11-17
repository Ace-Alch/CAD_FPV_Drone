# FPV Quadcopter CAD Design: setup

## Current entry point

1. Open `CAD/Assem1.SLDASM` in SolidWorks 2022 or a compatible release.
2. Resolve its referenced parts from `CAD/`.
3. Inspect mates and missing-reference warnings.
4. Use the PDF drawings and exploded animation in `Docs/` to inspect the assembly.
5. Export neutral formats only after the assembly resolves. Record the export settings.

## Required records

- STEP and STL export evidence
- Materials and fasteners
- Mass properties
- Physical assembly checks

## Reproducibility record

Record the source commit, operating system, tool versions, dependencies, input files, configuration and command. Store the output separately from the expected result. Mark any manual step.
