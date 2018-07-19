Back to [Projects List](../../README.md#ProjectsList)

# SlicerAR

## Key Investigators

- Adam Rankin (Robarts Research Institute)
- Mitchell Doughty (Sunnybrook)

# Project Description

<!-- Add a short paragraph describing the project. -->

## Objective

1. Enable video passthrough to OpenVR family of devices.

## Approach and Plan
1. 

### Mitch's goals for the week
1. Learn about capabilities of the [SlicerVirtualReality](https://github.com/KitwareMedical/SlicerVirtualReality) module.
2. [OpenIGTLink](https://github.com/openigtlink/OpenIGTLink) for communication with imaging devices, rendering in Slicer. 
3. Experiment with registration toolkits for deformable and between modality image registration.

## Progress and Next Steps
1. 

### Mitch's progress
1. SlicerVR capabilities are mainly limited to visualization and some basic transformation tasks currently. Support for several devices
    - No current VTK support for HoloLens [source](https://www.na-mic.org/wiki/2017_Winter_Project_Week/Slicer_VR)
    - SlicerVR works with OpenVR-compatible headsets including HTC Vive, WMR headsets (not the HoloLens), Oculus Rift
    - Potential for integration with [OpenCV](https://opencv.org) through the [SlicerOpenCV](https://www.slicer.org/wiki/Documentation/4.8/Extensions/SlicerOpenCV) module


    

3. Lots of tools available for registration. Need to fine tune registration parameters for my needs.
    - [Elastix](https://github.com/lassoan/SlicerElastix) module in Slicer for deformable registration.
    - [Sequence](https://www.slicer.org/wiki/Documentation/4.8/Extensions/Sequences) module for visualization of 4D data.
    - [Sequence registration](https://github.com/moselhy/SlicerSequenceRegistration) module which builds off the Elastix module for registration of 4D data.


<!--Describe progress and next steps in a few bullet points as you are making progress.-->

# Illustrations

<!--Add pictures and links to videos that demonstrate what has been accomplished.-->

<!--![Description of picture](Example2.jpg)-->

<!--![Some more images](Example2.jpg)-->

# Background and References

<!--Use this space for information that may help people better understand your project, like links to papers, source code, or data.-->

- [Documentation](https://www.slicer.org/wiki/Documentation/Labs/Augmented_Reality_and_Virtual_Reality_support) on AR/VR support in Slicer.
- [Wiki](https://github.com/ValveSoftware/openvr/wiki/API-Documentation) on OpenVR API.