Back to [Projects List](../../README.md#ProjectsList)

# SlicerAR

## Key Investigators

- Adam Rankin (Robarts Research Institute)
- Mitchell Doughty (Sunnybrook)

# Project Description

<!-- Add a short paragraph describing the project. -->

## Objective

1. Enable video passthrough to OpenVR family of devices

## Approach and Plan
Mitch's goals:
1. Learn about capabilities of the [SlicerVirtualReality](https://github.com/KitwareMedical/SlicerVirtualReality) module and how to perform basic visualization/transformation tasks.
2. Streamline and optimize 3D model creation from manual or automated segmentation. Edge refinement, etc. 
3. Export 3D location information of imaging [fiducials](https://www.slicer.org/wiki/Documentation/4.8/Modules/Markups) for use in marker registration. 
4. [OpenIGTLink](https://github.com/openigtlink/OpenIGTLink) for communication with imaging devices, rendering in Slicer. Tie in with visualizationa dn transformation tasks ultimately.

## Progress and Next Steps
1. 

2. Per [this](https://discourse.slicer.org/t/refinement-of-stl-files/243/6) forum post, could perform simple model refinement using the [Segmentations](https://www.slicer.org/wiki/Documentation/4.8/Modules/Segmentations) module. [MeshLab](http://www.meshlab.net/) is another alternative. 

3. Fiducial markers can be manually (or automatically) placed on selected positions across the image using the [markups](https://www.slicer.org/wiki/Documentation/4.8/Modules/Markups) module. 

Automatic fiducial placement through Python command line interface. Can create with initial parameters (x0, y0, z0).

```  
slicer.modules.markups.logic().AddFiducial(x0,y0,z0)
```
**TODO:** identify consistent fiducial points or imaging markers, segment and export the 3D locations of these parameters. Positions of fiducials can be saved to a text file. 

<!--Describe progress and next steps in a few bullet points as you are making progress.-->

# Illustrations

<!--Add pictures and links to videos that demonstrate what has been accomplished.-->

<!--![Description of picture](Example2.jpg)-->

<!--![Some more images](Example2.jpg)-->

# Background and References

<!--Use this space for information that may help people better understand your project, like links to papers, source code, or data.-->

- [Documentation](https://www.slicer.org/wiki/Documentation/Labs/Augmented_Reality_and_Virtual_Reality_support)  on AR/VR support in Slicer.

- [Slicer forum](https://discourse.slicer.org/t/connecting-htc-vive-with-3d-slicer/1299/2) post on HTC Vive integration with 3D Slicer.

- Source code: https://github.com/YourUser/YourRepository
- Documentation: https://link.to.docs
- Test data: https://link.to.test.data

