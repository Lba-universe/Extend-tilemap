# ExtendTileMap_Generator 

## based on [This GitHub Repo](https://github.com/gamedev-at-ariel/05-tilemap-pathfinding)

###

### in this game you need to go to right-up corner without the enemy touch you,then the map extend.

### example pic

![](/pics/1.png)

###

there are 2 scripts 
1. generate matrix of random ints - between 0 and num of tiles given,
also it has smoothing method that attach smilar tiles togther to make realistic tilemap.
[Script-MatrixGenerator](https://github.com/Lba-universe/TileMap_Generator/blob/main/Assets/Scripts/TilesGenerator.cs)

2. is to convert the matrix of ints - to tiles each number has index of uniqe tile in the scene
[Script-TileMapGenerator](https://github.com/Lba-universe/TileMap_Generator/blob/main/Assets/Scripts/TileMapGenerator.cs)

every changed line commented with "my change".

###
### in this example there is 5 diffrent tiles

![](https://github.com/Lba-universe/TileMap_Generator/blob/main/pics/tilemap1.png)

![](https://github.com/Lba-universe/TileMap_Generator/blob/main/pics/tilemap3.png)


