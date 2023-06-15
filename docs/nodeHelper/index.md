# NodeHelper

NodeHelpers are used to configure sides of tile. The parameters are the following:

+  **UID:** for identification
+ **Socket name:** useful to preview at a glance which type of helper is.
+ **SocketCodes**: used to identify a side. In the how they work section is explained how codes works to create adjacencies but the user can add as many identifiers as they want. The only rule is that it has to be consisten with all the other nodes that want to be paired. If a side is BBB and the next is also BBB it needs to use the same amount of codes spelled the same way (case sensitive).



![Screenshot 2023-06-16 005319](assets\Screenshot 2023-06-16 005319.png)

## How they work

Node helpers are used to defining adjacency codes without explicitly defining each adjacency. The process of defining every adjacency is a very time-consuming process prone to error. 

NodeHelpers try to make this process less painful. As shown in the pic, a node nodeHelper defines the pattern of a side of the tile. The are defined through a list of patterns. Patterns are depictions of the side of a tile, it can be represented by a colour, code or a definition of the side such us path or stairs in the example. The side of the node can be split as in many sections as the user wants and make use of a single code. In the case of 2d nodes, it supports symmetrical and asymmetrical rotations but to make asymmetrical rotations is fundamental to make use of proper tagging of a side.

 We can see how the notation should be done. Starting from the side on top and following a clockwise rotation. So, the first code would be BBB, the second BPB and so on. When proper tagging is done, all types of rotations can be used no matter if the tile has a symmetrical structure or not.



![Screenshot 2023-06-16 005933](assets\Screenshot 2023-06-16 005933.png)
