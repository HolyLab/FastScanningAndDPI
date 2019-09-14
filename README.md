# FastScanningAndDPI
Directory of code for OCPI fast scanning / DPI publication

This repository contains no code.  It is only meant as a directory to the various software components used for the work published in [insert here].

### Microscope control
[Imagine](https://github.com/HolyLab/Imagine)               C++ software for making recordings with the microscope.  Qt-based GUI. 

[Imagine.jl](https://github.com/HolyLab/Imagine.jl)            Partial implementation of Imagine in the Julia language (scriptable, no GUI).

[ImagineInterface.jl](https://github.com/HolyLab/ImagineInterface)   Allows designing experiments in Julia, design files can be read and run by Imagine.

### Adjusting PID settings of piezo
[PiezoSerial.jl](https://github.com/HolyLab/PiezoSerial.jl)        Serial interface to the Piezosystem Jena 30DV300 amplifier.

### Calibrating image timings
[FastScanning.jl](https://github.com/HolyLab/FastScanning.jl)    Julia package for generating and analyzing recordings to calibrate image timing during fast 3D scans.

### Extracting Point Spread Functions from bead images
[ExtractPSF.jl](https://github.com/HolyLab/ExtractPSF.jl)          Contains routines for locating beads and fitting Gaussian PSFs to bead images

### Aligning and stitching images acquired with Distributed Planar Imaging (DPI)
[StitchDPI.jl](https://github.com/HolyLab/StitchDPI.jl)      (Currently limited to dual-camera DPI systems)

### "Lazy" temporal interpolation of stacks
[ImageInterpLast.jl](https://github.com/HolyLab/ImageInterpLast.jl)

### Manual segmentation of neurons in calcium imaging data
[RoiTool.jl](https://github.com/HolyLab/RoiTool.jl)            GUI implemented using Julia's interface to GTK
