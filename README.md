# Structural Analysis | Vectenor Engineering

Abaqus model examples covering closure dynamics and body-in-white structural analysis.

## Door-slam simulation

An Abaqus/Explicit input deck with rotating-velocity initial conditions, general contact, connectors, fasteners, and geometric nonlinearity. The example demonstrates preparation of a closure-dynamics model and requests displacement, stress, and energy output.

Download **Doorslam.zip** from [Model downloads](https://github.com/vectenor-engineering/abaqus-structural-analysis/releases/tag/models-v1). Extract the archive and inspect `Doorslam/Doorslam.inp` in your Abaqus workflow.

## Door-slam result review

The supplied front-door result view shows contour distributions on the inner and outer panels, with detailed views around local connection regions. It illustrates the post-processing review of localized response. The supplied image does not identify the plotted variable, units, or frame time, so a numerical acceptance assessment requires that information.

## Body-in-white bending

An Abaqus static bending setup comprising `Model.inp` and `Run_bending.inp`. The run file includes the base model, defines support constraints, and applies two vertical nodal loads of -1500 in the model's consistent force units. It requests displacement, stress, and energy output.

Download **Bending_BIW.zip** from [Model downloads](https://github.com/vectenor-engineering/abaqus-structural-analysis/releases/tag/models-v1). Keep both input files together and use `Run_bending.inp` as the entry deck.

## Package status

These are supplied input-model examples. Packaging checks covered file inclusion and keyword inspection. Solver execution, numerical results, and performance claims require a separate verification run. Confirm the unit system, material assumptions, solver compatibility, and load definitions before adapting a deck.

The archives preserve the supplied input files. SHA-256 checksums are recorded in `SHA256SUMS.txt`.

[Vectenor Engineering](https://github.com/vectenor-engineering)
