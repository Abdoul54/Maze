# 3D Maze Game (ALX Maze Project)

### Overview
This 3D maze game was developed as part of the ALX Maze Project, where I explored OpenGL concepts such as vertex buffers, matrices, and shaders. The project aimed to enhance my understanding of OpenGL, resulting in the creation of this compact maze game.

In the game, players navigate a camera using arrow keys, collecting spinning yellow cubes (purely aesthetic). To complete each maze, locate a spinning rainbow cube that transports you to another randomly generated maze. While the code may not adhere to high standards and the controls may feel clunky, sharing this project provides insights into the learning process.

### Controls
- Left Arrow: Turn camera left
- Right Arrow: Turn camera right
- Up Arrow: Move forward
- Down Arrow: Move backward
- Space: Jump

### Compilation Instructions
To compile the source code, execute the following commands:

```bash
cd Maze
cd build
cmake ..
make
```

To run the program, use `./3d-maze`. Ensure that the 'shaders' folder is in the same directory as the executable for the game to function correctly.
```bash
./3d-maze
```

### Dependencies
Ensure the following dependencies are installed:
- [GLFW](https://www.glfw.org/)
- [glad](https://glad.dav1d.de/)
- [glm](https://github.com/g-truc/glm)

### Platform Note
The code was primarily developed for Linux Ubuntu.

### Screenshots
![Screenshot 1](https://github.com/JLi69/3d-maze-game/blob/main/screenshots/Screenshot-1.png)
![Screenshot 2](https://github.com/JLi69/3d-maze-game/blob/main/screenshots/Screenshot-2.png)
![Screenshot 3](https://github.com/JLi69/3d-maze-game/blob/main/screenshots/Screenshot-3.png)


Feel free to contribute, report issues, or enhance the game as part of the ALX Maze Project!