# Build My World Project  
## Project Description  
This is the 1st project in the Robotics Software Engineer Nanodegree Program by Udacity.  

### Summary of Tasks
1. Build a single floor wall structure using the **Building Editor** tool in Gazebo. Apply at least one feature, one color, and optionally one texture to your structure. Make sure there's enough space between the walls for a robot to navigate.  
2. Model any object of your choice using the **Model Editor** tool in Gazebo. Your model links should be connected with joints.  
Import your structure and two instances of your model inside an empty Gazebo World.  
3. Import at least one model from the Gazebo online library and implement it in your existing **Gazebo world**.  
4. Write a C++ **World Plugin** to interact with your world. Your code should display “Welcome to ’s World!” message as soon as you launch the Gazebo world file.  

## Directory Structure  
```
 .BuildMyWorld                      # Build My World Project  
    ├── model                       # Model files  
    │   ├── building  
    │   │   ├── model.config  
    │   │   ├── model.sdf  
    │   ├── vehicle  
    │   │   ├── model.config  
    │   │   ├── model.sdf  
    ├── script                      # Gazebo World plugin C++ script      
    │   ├── welcome_message.cpp  
    ├── world                       # Gazebo main World containing models   
    │   ├── myworld.world  
    ├── CMakeLists.txt              # Link libraries   
    └──                              
 ```
