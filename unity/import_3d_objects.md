# Import 3D Modeling Objects



Unity is further a integrated creation platform. While creating objects or scenes in the game or in reality design, it supports to import them from others desgin tools like `sketchup`, `autocad`, `maya`, etc. It mainly supports the following file format: `.FBX`, `.dae`, `.3DS`, `.dxf` and `.obj` files. If tools you used support to export the above format, it would be imported into unity. In the document, we demostrate how to import a 3D modeling object into unity.

The procedure to import a object into unity is the same, we take sketchup as the example.



## Import Steps



- You have already done a 3D modeling in Sketchup / AutoCAD / Maya, etc.

![image/sketchup2unity.png](../image/sketchup2unity.png)

- Export a 3D object in recepted formats :
  - In `sketchup`, click `file`, `export`, `3D modeling`, and save as a `.dae` file.
  - In `AutoCAD`, export the model in `.FBX` format by clicking `A` (on the most top-left), `Export`, `FBX` and select all types and materials.
  - In `Maya`, you can choose exporting file formats (`.DAE`, `.FBX`) by clicking `File`, `Export All`, and select the format in `Files of type`.
- In unity, click `Assets`, `Import New Asset`, and choose the `.dae` (or `.fbx`, etc.) file exported from sketchup. And you will see the object in the `Project View` and its sub view `Assets`.
- In unity, click the imported object and set the following attributes in `Inspector`. Click `Generate Colliders`, click `Import Materials`, choose `Model Name + Model's Material` on the `Material Naming` and click `Apply`.

![../image/sketup2unity_inspector.png](../image/sketup2unity_inspector.png)

- Drag the object in `Assets` view to the scene.

![../image/unitywithsketchup.png](../image/unitywithsketchup.png)

