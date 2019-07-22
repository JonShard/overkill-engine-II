# Overkill Engine II

### About
OK engine.

### Featrues
- [X] yiap.
- [X] yap.
- [ ] yepp!

### Installation
#### Windows

#### Ubuntu
1. Install latest grapics drivers. The OKEII uses OpenGL version 4.3.
1. Install CMake 3.8 version or above. 
    ```bash
    sudo apt-get install cmake libx11-dev xorg-dev libglu1-mesa-dev freeglut3-dev libglew1.5 libglew1.5-dev libglu1-mesa libglu1-mesa-dev libgl1-mesa-glx libgl1-mesa-dev
    ```
1. Install clang++:
    ```bash
    sudo apt-get install clang++6.0
    ```
1. Install glew globally as the repo only has the windows binaries. 
    ```bash
    sudo apt-get install libglew-dev
    ```
    (not sure if also glu and/or glm)
1. Set up repo:
    ```bash
    git clone [REPO LINK] 
    cd overkill-engine-II 
    mkdir build && cd build
    cmake .. -DCMAKE_CXX_COMPILER=clang++-6.0
    make
    ./overkill-engine-II
    ``` 