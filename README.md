# 3D-Reconstruction-from-2D-Images

You can find my Medium article on reconstructing 3D models from 2D images:
https://medium.com/@popovici.cristina211/3d-reconstruction-from-2d-images-using-openmvg-and-openmvs-b23bc7adb616

An effective open-source solution for reconstructing complete 3D models from 2D images involves the combination of openMVG and openMVS.

MVG, which stands for Multiple View Geometry, is dedicated to recovering camera locations and orientations from data such as images and camera intrinsics. It yields a sparse set of 3D points through triangulation based on feature points observed in the photographs.

MVS, or Multi View Stereo, focuses on generating a dense 3D reconstruction of the object. This can take the form of a dense point cloud, a faceted surface (mesh), or a set of planes. These results can be visualized as a realistic 3D rendering of the scene.

To reconstruct 3D models, you have to install and use openMVG and openMVS:
https://github.com/openMVG/openMVG
https://github.com/cdcseacave/openMVS

Steps in reconstructing a 3D model from 2D images
1. Image collection
2. Feature extraction
3. Feature matching
4. Structure from Motion
5. Dense point-cloud reconstruction
6. Mesh Reconstruction
7. Mesh Refinement
8. Mesh Texturing
