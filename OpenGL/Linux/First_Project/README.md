

# Steps to create Linux OpenGL starter project

1) Install prerequisite GLFW libraries and runtimes from the command prompt
```bash
sudo apt install libglfw3 libglfw3-dev libgl1-mesa-dev libx11-dev
```
2) Set up GLAD using the open source web service using GLAD1 version and make sure the language is set to C++, and in the API section select an OpenGL version of at least 3.3. Also make sure the profile is set to Core and that the Generate a loader option is ticked. Ignore the extensions and click Generate to produce the resulting library files.

3) Clone this repo and use the Makefile to compile, clean, and run the code to your hearts content. Feel free to modify, contribute, expand and experiemnt as much as you'd like.
    1) Compile code : ``` make ```
    2) Run compiled code : ``` make run ```
    3) Clean and erase binaries : ``` make clean ```

