# FastScanningAndMCIS
Directory of code for OCPI fast scanning / MCIS publication

This repository contains no code.  It is only meant as a directory to the various software components used for the work published in [insert here].

### Microscope control
[Imagine](https://github.com/HolyLab/Imagine)               C++ software for making recordings with the microscope.  Qt-based GUI. 

[Imagine.jl](https://github.com/HolyLab/Imagine.jl)            Partial implementation of Imagine in the Julia language (scriptable, no GUI).

[ImagineInterface.jl](https://github.com/HolyLab/ImagineInterface)   Allows designing experiments in Julia, design files can be read and run by Imagine.

### Adjusting PID settings of piezo
[PiezoSerial.jl](https://github.com/HolyLab/PiezoSerial.jl)        Serial interface to the Piezosystem Jena 30DV300 amplifier.

### Calibrating image timings
[EmpiricalTiming.jl](https://github.com/HolyLab/EmpiricalTiming.jl)    Julia package for generating and analyzing recordings to calibrate image timing.

### Aligning and stitching images acquired with Multi Camera Image Sharing (MCIS)
[TeamedImaging.jl](https://github.com/HolyLab/TeamedImaging.jl)      (Currently limited to dual-camera MCIS systems)

### "Lazy" temporal interpolation of stacks
[ImageInterpLast.jl](https://github.com/HolyLab/ImageInterpLast.jl)

### Manual segmentation of neurons in calcium imaging data
[RoiTool.jl](https://github.com/HolyLab/RoiTool.jl)            GUI implemented using Julia's interface to GTK
