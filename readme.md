# Maze Visualizer


<img width="800" height="518" alt="Maze-Visualizer" src="https://github.com/user-attachments/assets/86397996-1fa8-442d-a167-3e183a44960a" />

An interactive visualizer built in C to visually show how different algorithms generate and solve mazes.

## Demo
[Maze Visualizer Web Demo](https://logorhythmic.github.io/Maze-Visualization/)

## Info
* Generation: Randomized DFS and Randomized Prim's algorithm
* Solving: Breadth First search and Depth First search
* Interactive UI: Randomize start and end positions. Modify the number of rows and columns
* Playback Controls: Change animation speed or skip animation.

## Future Plans
* Generation: Implement Randomized Kruskals, Wilsons Algorithm for generation
* Solving: Implement AStar search for solving.

## Prerequisites
1. CMake (v3.20 or higher)

2. A C Compiler:
* Linux: gcc (via build-essential)

* Windows: Visual Studio (with C++ workflow) or MinGW

* macOS: Xcode Command Line Tools

3. SDL3 Development Libraries - [Install Instructions](https://github.com/libsdl-org/SDL/blob/main/INSTALL.md)

> [!NOTE]
> On Ubuntu, all dependencies can be installed by running:
> ```sudo apt update && sudo apt install -y build-essential cmake libsdl3-dev```



## Building the Program
1. Clone the repository and cd into it:
   ```sh
    git clone https://github.com/logorhythmic/Maze-Viusalizer.git && cd Maze-Visualizer
   ```

2. Make the build directory:
   ```sh  
	cmake -B build  
   ```

3. Compile and run the Raycaster:
   ```sh
   cmake --build build --config Release  
   ```



## References
[Visualizer concept](https://weblog.jamisbuck.org/2011/2/7/maze-generation-algorithm-recap)
