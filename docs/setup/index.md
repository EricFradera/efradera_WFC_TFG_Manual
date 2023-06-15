# SetUp

The setUp for the project is very easy. Just follow the next steps:

## You got the TFG folder

1. Download the unity package from the folder.
2. Open the project where you want to import the tool.
3. Drag it to the asset explorer or double click to import.



## You don't have the folder

1. Download the repository from  the following link: [GitHub repository](https://github.com/EricFradera/TFG_WFC_UNITY)
2. On the folder Unity Package you can find the asset, just follow the previous section.



## Quickstart guide

Once everything is imported  you are halfway there!

The tool is thought to be as easy to use as possible. Follow the next steps to create your own configuration: 

1. Create a WFCConfiguration asset from the file explorer:

![Screenshot 2023-06-15 231736](assets\Screenshot 2023-06-15 231736.png)

You can decide whichever type of topology you want to use,  all of  them follow the same workflow.

2. Once created, by double clicking the asset we can access the node editor.

![Screenshot 2023-06-16 001636](assets\Screenshot 2023-06-16 001636.png)

3. By right clicking in the node editor we are  given 2 options:
   1. Node tile: tile assets that need to be configured. For more information go to:  
   2. Node helpers: node that help add  code identifiers to the tiles. go to:
4. Now its time to configure each side of a node tile manually (by connecting an output tile to the input of another tile) or by a node helper (connecting an output tile to a node helper). As we can see in the the picture below

![rel](assets\rel.png)



5. This process is the most time consuming part of the configuration. The main difficulty is give the proper codes for an optima configuration.

![Screenshot 2023-06-16 002803](assets\Screenshot 2023-06-16 002803.png)




6. Once the whole configuration has been finished we are ready to start generating.
6. Create a empty game object and add the component: WFCGenerator
6. Once it's added you can add the file on the WFCConfigFile field  and start the generator.

![Screenshot 2023-06-16 003116](assets\Screenshot 2023-06-16 003116.png)
