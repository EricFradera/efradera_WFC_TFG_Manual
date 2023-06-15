# Tiles

Tiles are the basis of all generation. Tiles in this context shouln't be taken as the common sprites used in common 2d games. Tiles work more as patterns to a certain visual element. Tiles can also be 2d sprite tiles, but also 3d models, hexagons... By having a good understanding of the concept, we can get the most out of the generator.

In the WFCTile we provide a few parameters for the user:

+ **TileName:** name of the tile
+ **TileId:** used for identification
+ **Frequency:** how common is a tile. The frequency is done by the sum of all frequencies. In the editor is used as a slider between 1 to 100, but we give full freedom to use its own values.
+ **AdjacencyCodes:** easy to visualize codes from nodeHelpers
+ **TileVisuals:** list of gameObjects that will be spawned when the tile is selected.
+ **Tile texture:** same thing as tileVisuals but with textures.
+ **PreviewTexture:** is used to preview in the inspector, by default it takes the first item on the texture list or the preview from the firstgamobject.
+ **AssetType:** the user can decide which type of asset will be spawned, either gameobjects or textures.
+ **Rotations:** rotations allow for a tile to be rotated clockwise.  Not all topologies have support for every feature take a look at [Features](../features/index.md)

!!! note "Make sure to check the tick use rotations in the configuration file"

![Screenshot 2023-06-16 003629](assets\Screenshot 2023-06-16 003629.png)