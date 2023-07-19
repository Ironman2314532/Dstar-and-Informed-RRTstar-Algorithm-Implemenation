We are going to implement **D*** and **Informed RRT*** algorithms. 

## Instruction

Before starting any coding, please run the code first. Navigating under each of the two folders, and run

`python main.py`

For the **Informed RRT***, the **main.py** loads the map image **WPI_map.jpg** and calls classes and functions to run planning tasks. 

For the **D***,  the **main.py** loads two map, a static one and a dynamic one. The static one is for the initial planning, while the dynamic one tells where the new obstacles are. 

Please keep in mind that, the coordinate system used here is **[row, col]**, which is different from [x, y] in Cartesian coordinates. In README and the code comment, when the word '**point**' is used, it refers to a simple list [row, col]. When the word '**node**' or '**vertex**' is used, it refers to either the Node class in RRT ,or a node/vertex in a graph in PRM. 

## D*

For more details, please go through the lecture and the original paper [Optimal and Efficient Path Planning for Partially-Known Environments](http://web.mit.edu/16.412j/www/html/papers/original_dstar_icra94.pdf). 

## Informed RRT*

For more details, please go through the lecture and the original paper [Informed RRT*: Optimal Sampling-based Path Planning Focused via Direct Sampling of an Admissible Ellipsoidal Heuristic](https://arxiv.org/pdf/1404.2334.pdf).
