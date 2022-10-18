# vscode_ros1_devcontainer

My approach to create a vscode devcontainer for ros-noetic.

This repository is mainly based on <https://github.com/athackst/vscode_ros2_workspace> and <https://www.allisonthackston.com/articles/vscode-docker-ros2.html>.

## Requirements:

Install:

> https://github.com/athackst/vscode_ros2_workspace#prerequisites

* [docker](https://docs.docker.com/engine/install/)
* [vscode](https://code.visualstudio.com/)
* [vscode remote containers plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

Clone or download this repository.

## Reopen the Folder in a Dev Container

Use <https://github.com/athackst/vscode_ros2_workspace/blob/foxy/README.md#open-it-in-vscode> as a tutorial about how to open this folder in a container.

## Tutorial Modification

The official tutorials of <http://wiki.ros.org/ROS/Tutorials> need minor modifications, because ros is already installed in this docker image.

The docker image `althack/ros:noetic-full` specified in [.devcontainer/Dockerfile](.devcontainer/Dockerfile) already includes the **ROS Noetic** installation. Therefore, you can skip section `1. Install ROS` of [Installing and Configuring Your ROS Environment](http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment).

