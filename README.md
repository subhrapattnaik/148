# 148

gLTF stands for Graphics Language Transmission Format.

It is a standard file format for 3D models and scenes.


To store 3D models, the file formats used are .obj, .fbx, .gltf(or .glb) etc.

3D models are stored in the form of polygons, for example, a set of triangles, which is called a mesh.
This information can be stored in the form of vertices, edges or faces depending on the applica


======================================================
Asset Management in A-Frame.

In A-Frame assets can be added
under <a-assets>
And Assets can be:
<a-asset-item> - Miscellaneous
assets like 3D models.
<audio> - Sound files
<img> - Image textures
<video> - Video textures


free 3D models (.gltf, .obj etc) can be downloaded.
Link : https://sketchfab.com/feed

To download gLTF models from the website(eg. sketchfab.com):
Note 1: Create a free account on sketchfab.com by using goo


--------------------------------------------------

The timeout attribute with the given
value set in “milliseconds” is the time
the scene is going to wait until it starts
showing all the assets in the scene.
The scene and all the other entities in
the scene will wait for every asset to
be loaded, for the time mentioned in


The default timeout is 3 secs.
The scene waits for 3 secs to load all
the assets by default before rendering
entities on the screen.After 3 secs it
will start showing all the entities and
the one which is still not will be
displayed after some once they are
loaded.
If timeout is reached the scene will
start showing entities on the screen.

