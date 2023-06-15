# Features



Wave function collapse is an algorithm of procedural generation that rely on adjacency constrains to create visually consistent compositions. The  algorithm was initially used as a texture synthesis algorithm.

To know more about the algorithm we suggest either reading the TFG document or watch the following video:  [Wave function collapse by Martin Donald](https://www.youtube.com/watch?v=2SuvO4Gi7uY&t=2s)



## Models

The tool provides four models or topologies for  procedural generation:

+ One dimensional generation: ideal for sides scroller games such as super Mario bros  or downwell.
+ Two dimensional generation: all kinds of tile based 2d games. This includes the use of sprites and3d models.
+ Three dimensional generation: allows to create games with with depth and height.
+ Hexagonal games: great for games that rely on hexagonal tiles.



While all models allow for generation, no all of the have the  same feature set. The  following table shows the feature set of each topology:

| Topology | Manual configuration | Helpers | Gizmo representation | Rotations |
| :------: | :------------------: | :-----: | :------------------: | --------- |
|    1D    |        **✔**         |  **✔**  |        **✔**         | n/a       |
|    2D    |        **✔**         |  **✔**  |        **✔**         | **✔**     |
|    3D    |        **✔**         |  **✔**  |        **✔**         | **✔       |
|   HEX    |        **✔**         |  **✔**  |        ***✔**        | x         |

*Although hexagonal has a gizmo, it doesn't provide a precise representation.

**3D rotations are only available for symmetrical configurations

## Node helpers



Node helpers  allow to give a code to a certain type of shape to a side of a tile. This allows for easy to use and less work intensive configurations. The use of rotations also prove fundamental for rotate certain tiles



## Node editor

All the configurations are done through the node editor. In  this enviroment all tools an features are provided to  create the relations in a visual friendly enviroment. All the topologies share the same editor, so the learning curve is very easy.



![Screenshot 2023-06-15 222048](assets\Screenshot 2023-06-15 222048.png)



## Rotations

Rotations allow for easier configurations by allowing to just  configurate a single tile and then provide which rotations  also take part in the generation to know more visit [WFCTile](../Tile/index.md)

## Tile exported

The tile exporter allows to serialise a whole configuration into a json file.

![Screenshot 2023-06-15 222637](assets\Screenshot 2023-06-15 222637.png)



## Unified  generator

Don't worry about any setUp, just create a root gameObject and add the WFCGenerator, everything  will be handled with any more generation. Focus on provide the proper configurations such us  frequency, adjacencies etc.

![Screenshot 2023-06-10 022816](assets\Screenshot 2023-06-10 022816.png)

## Multiple sets

Add multiple sets of textures under  the same configuration. By understanding a tile as a pattern we can abstract an reuse the same configuration to use it with multiple sets of textures

![Screenshot 2023-06-16 001143](assets\Screenshot 2023-06-16 001143.png)



We can add multiple textures or gameobjects and indicate in the generator in the tileSetIndex  which is the tileSet index based on the list index.



![Screenshot 2023-06-16 001331](assets\Screenshot 2023-06-16 001331.png)
