Cave world
=============

## Description

Cave environment using both DARPA provided[1,2] tiles and custom made 3D models with the following features:

* Large void areas
* Vertical shafts
* Gate with apriltags
* Foldable drone evaluation area
* Areas with stalactites and stalagmites
* Artifacts (backpack, extinguisher and survivor). Ten artifacts of each type are randomly placed in the world. Use existing ones or your own.
* Specification document with artifacts and their positions
* External dimensions (height x width x length): 33 x 102 x 150 [meters]

## Preview
![example](https://i.imgur.com/T4VOFeV.png)


## Installation

Clone the package into your catkin workspace:
```
git clone https://github.com/LTU-CEG/gazebo_cave_world.git
```
Use `catkin_make` on your workspace to compile, or `catkin build` if you are using catkin_tools.

## Usage

To load cave world use:
```
roslaunch gazebo_cave_world cave_world.launch
```

To add models copy them to ~/worlds/models folder inside the package.

## Licence

MIT License

## References

[1] https://subtchallenge.world/openrobotics

[2] https://bitbucket.org/osrf/subt/wiki/Home
