# Wave Function Collpase
This is an image generator based on input tiles that have certain border rules.
You can read more about it here:
[Wikipedia page](https://en.wikipedia.org/wiki/Wave_function_collapse)

And visit GitHub repo about it:
[WFC github page](https://github.com/mxgmn/WaveFunctionCollapse)

## Result demo with backtracking
GIF presented below is a result of final version of the project with implemented backtracking for 14 tiles in 40x40 grid.
<p align="center">
<img src="results/WithBacktracking/result.gif" width="400" height="400">
</p>

## First working result - no backtracking
Used tiles:  
![Tile0](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/lines/0.png "Tile 0")
![Tile1](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/lines/1.png "Tile 1")
![Tile2](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/lines/2.png "Tile 2")  
After loading tiles with boundaries, algorithm computes all possible rotations. 
Example result for 5x5 grid:
<p align="center">
<img src="https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/results/V1%20-%20No%20backtracking/result.png" width="400" height="400">
</p>

## Second example - no backtracking
Used tiles:  
![Tile0](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/0.png "Tile 0")
![Tile1](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/1.png "Tile 1")
![Tile2](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/2.png "Tile 2")
![Tile3](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/3.png "Tile 3")
![Tile4](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/4.png "Tile 4")
![Tile5](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/5.png "Tile 5")
![Tile6](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/6.png "Tile 6")
![Tile7](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/7.png "Tile 7")
![Tile8](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/8.png "Tile 8")
![Tile9](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/9.png "Tile 9")
![Tile10](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/10.png "Tile 10")
![Tile11](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/11.png "Tile 11")
![Tile12](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/12.png "Tile 12")
![Tile13](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/13.png "Tile 13")  
After loading tiles with boundaries, algorithm computes all possible rotations. 
Example result for 10x10 grid:
<p align="center">
<img src="https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/results/V1%20-%20No%20backtracking/circuitResult.png" width="400" height="400">
</p>

## Third example - with implemented backtracking
Backtracking done recursivly by solve function  
Used tiles:  
![Tile0](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/0.png "Tile 0")
![Tile1](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/1.png "Tile 1")
![Tile2](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/2.png "Tile 2")
![Tile3](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/3.png "Tile 3")
![Tile4](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/4.png "Tile 4")
![Tile5](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/5.png "Tile 5")
![Tile6](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/6.png "Tile 6")
![Tile7](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/7.png "Tile 7")
![Tile8](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/8.png "Tile 8")
![Tile9](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/9.png "Tile 9")
![Tile10](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/10.png "Tile 10")
![Tile11](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/11.png "Tile 11")
![Tile12](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/12.png "Tile 12")
![Tile13](https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/img/Circuit/13.png "Tile 13")  
After loading tiles with boundaries, algorithm computes all possible rotations. 
Example result for 40x40 grid:
<p align="center">
<img src="https://github.com/nowakkuba99/SDL/blob/main/WaveFunctionsCollapse/results/WithBacktracking/circuitResultBacktrack.png" width="400" height="400">
</p>
