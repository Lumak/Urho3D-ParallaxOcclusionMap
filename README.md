# Urho3D Parallax Occlusion Map
  
---
### Description
Parallax Occlusion Mapping for Urho3D
  
#### Implementation Info
* shaders written for GL and DX9. Would require renaming sample texture for DX11.

#### Fixes and Updates
* created PlaneTangent.mdl which fixes the tangent vectors
* bitangent calculation is changed based on https://www.gamasutra.com/blogs/RobertBasler/20131122/205462/Three_Normal_Mapping_Techniques_Explained_For_the_Mathematically_Uninclined.php?print=1
* transpose applied to GLSL TBN matrix
* added cube parallax occlusion
* added terrain parallax occlusion

---
### Screenshots

![alt tag](https://github.com/Lumak/Urho3D-ParallaxOcclusionMap/blob/master/screenshot/Screenshot.png)
![alt tag](https://github.com/Lumak/Urho3D-ParallaxOcclusionMap/blob/master/screenshot/Screenshot2.png)
![alt tag](https://github.com/Lumak/Urho3D-ParallaxOcclusionMap/blob/master/screenshot/Screenshot3.png)
![alt tag](https://github.com/Lumak/Urho3D-ParallaxOcclusionMap/blob/master/screenshot/parallaxTerrain.jpg)

---
### To Build
To build it, unzip/drop the repository into your Urho3D/ folder and build it the same way as you'd build the default Samples that come with Urho3D.  
**Built with Urho3D 1.7 tag.**
  
---  
### License
The MIT License (MIT)







