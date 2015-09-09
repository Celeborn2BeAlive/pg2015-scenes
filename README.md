# Skeleton based Vertex Connection Resampling for Bidirectional Path Tracing - Scenes

![teaser image](https://raw.githubusercontent.com/Celeborn2BeAlive/pg2015-code/master/teaser_image.png)

This repository contains the scenes used to compare our method proposed at the conference [Pacific Graphics 2015](http://cg.cs.tsinghua.edu.cn/pg2015/).

The repository [pg2015-code](https://github.com/Celeborn2BeAlive/pg2015-code) contains the source code of the method.

## Folder structure

* assets: Contains OBJ files and textures for the 3D models.
* results: Destination folder for results generated with the application [pg2015](https://github.com/Celeborn2BeAlive/pg2015-code). Also contains the reference images to compare results with.
* scenes: Contains scenes descriptions.

The directory of a scene has the following structure:
* name_of_the_scene
    * configs: Contains XML files for each scene configuration. A config is a camera positions and a set of non area lights (point or directional lights).
    * scene.bnz.xml: Contains a description of the scene
    * viewer.bnz.xml: Contains a description of the view window