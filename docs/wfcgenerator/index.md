# WFCGenerator

The wfc generator handles all the generation made by the tool.

+ **M_gridSize**: indicates how big a tile will be.
+ **Grid extent**: indicates how big the grid will be
+ **Backtracking:** by default the generator uses a greedy approach. When this greedy fails its starts again until it finds a solution. When configurations become very complex is better to use backtracking to avoid greedy to fail too many times. Will increase processing times in bigger and complex generations.
+ **TileSetIndex:** if the tiles have multiple assets you can indicate which index of the list you want them to use.
+ **LineColor:** changes the colour of the lines of the gizmos.
+ **WFCTiles:** shows a preview of all the tiles in the configuration. Some easy to acces parametes has been made available for comodity.

![Screenshot 2023-06-16 010314](assets\Screenshot 2023-06-16 010314.png)
