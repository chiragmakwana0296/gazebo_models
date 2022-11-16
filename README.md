# Gazebo Resource


### Installing

And add the following lines to the end of your `.bashrc` or `.zshrc` file.

```
source /usr/share/gazebo/setup.sh
```
```
export GAZEBO_MODEL_PATH=<path-to-clone-dir>/models:${GAZEBO_MODEL_PATH}
```
```
export GAZEBO_RESOURCE_PATH=<path-to-clone-dir>/worlds:${GAZEBO_RESOURCE_PATH}
```