# Cisl.Qclm.Public
This is the home to public source code of `Cisl.Qclm` project, the control software for _Infrared
spectroscopic laser scanning confocal microscopy for whole-slide chemical imaging_.

## System requirements
Please refer to the publication for hardware requirements.

### Libraries
Libraries listed below requires either purchased license or being directly supplied by vendor. NuGet downloadable libraries are bundled directly in supplied project file, automatically restored by `dotnet restore` or first time running `dotnet build`.

**Software**
| Type | Library | Version |
| - | - | - |
| UI | `SciChart.*` | 6.2.1.13304 | 
| | `Syncfusion.*` | 16.1.0.26 |

**Hardware**
| Type | Vendor | Library | Version |
| - | - | - | - |
| Laser | Block Enginnering | `BLKQCL_Proxy` | 1.0.3.9 |
| Stage | Aerotech | `Aerotech.*` | 3.8.0.0 |
| | Prior | `Interop.PRIORLib` | 1.80.0.0 |
| | Thorlabs | `Thorlabs.MotionControl.*` | * |
| Signal | National Instruments | `NationalInstruments.DAQmx` | 15.5.45.109 |
| | Zurich Instruments | `ziDotNET-win64` | 1.0.6632 | 
| Camera | Teledyne | `SpinnakerNETGUId_v140` | 1.24.0.60 |


## Installation
We provide compiled binaries and MATLAB scripts on the [Releases](https://github.com/chemimage/Cisl.Qclm.Public/releases) page.
Latest version is [here](https://github.com/chemimage/Cisl.Qclm.Public/releases/tag/1.0.0).

## Demo
If all the hardware and software dependencies are resolved, you should be able to have something similar to this recording

https://user-images.githubusercontent.com/2089799/233740609-65b7796f-6a91-49a3-8823-4bbd7ead190e.mp4

## Instructions for use
Please refer to the demo. 

## Disclaimer
The acquisition software for the microscope, post-processing, and analysis code is available from the corresponding author upon reasonable request. The requestor is responsible for procuring all necessary licenses for 3rd party libraries used.
