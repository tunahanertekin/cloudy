# Let's Get Started!
Up to know, we've introduced some basic concepts about robotics, ROS, and ROS 2. In this part, we'll dive into ROS 2 essential concepts. 

For more details make sure to check out the links given in each part.

## ROS 2 Filesystem
ROS 2 uses a distributed file system to manage the storage and communication of data between different nodes in a robotic system. The ROS 2 filesystem is based on a set of conventions and rules that govern how data is organized and accessed within a ROS 2 environment.

The ROS 2 filesystem is structured around the concept of packages, which are collections of related ROS 2 nodes, libraries, and other resources. Each package contains a set of directories and files that define its functionality and dependencies.

?> Follow [**here**](https://ros2-industrial-workshop.readthedocs.io/en/latest/_source/basics/ROS2-Filesystem.html) to navigate through ROS 2 filesystem.

## ROS 2 Workspace
ROS 2 (Robot Operating System 2) uses a workspace concept for organizing and building packages. A workspace is a directory that contains one or more ROS 2 packages, along with the tools and configuration files needed to build and run them.

?> To create a new ROS 2 workspace, see [**official documentation**](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html).

## ROS Packages
In ROS 2 (Robot Operating System 2), a package is the basic unit of software organization. A package is a directory that contains one or more ROS 2 nodes, libraries, configuration files, and other resources related to a specific functionality.

Overall, ROS 2 packages provide a flexible and modular way to organize your ROS 2 code, making it easier to develop, share, and collaborate on robotics applications.

?> To create a new ROS 2 package, see [**official documentation**](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html).

## ROS Nodes
In ROS 2 (Robot Operating System 2), a node is the basic building block of a ROS 2 system. A node is an executable that performs a specific task and communicates with other nodes via messages.

ROS 2 nodes can be implemented in any programming language as long as they are compatible with the ROS 2 message passing system. Nodes can publish messages on a topic, subscribe to messages on a topic, or provide a service that other nodes can call.

?> To learn about the functions of nodes in ROS 2 and the tools to interact with them, see [**official documentation**](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Nodes/Understanding-ROS2-Nodes.html).
## ROS Topics
In ROS 2 (Robot Operating System 2), a topic is a named bus over which nodes can exchange messages. Topics are the primary communication mechanism used in ROS 2 to enable nodes to communicate with each other.

ROS 2 nodes can publish messages on a topic or subscribe to messages on a topic. When a node publishes a message on a topic, all other nodes that have subscribed to that topic will receive the message. Similarly, when a node subscribes to a topic, it will receive all messages that are published on that topic.

To create a new ROS 2 topic, you can start by creating a new ROS 2 node that publishes or subscribes to the desired topic. 

?> To understand topics more, see [**official documentation**](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Topics/Understanding-ROS2-Topics.html).

## ROS Launch Scripts
ROS 2 launch files are similar to ROS 1 launch files, but with some differences in syntax and usage. They are XML files that allow you to start multiple ROS 2 nodes simultaneously with specific configurations and dependencies.

?> To create a launch file to run a complex ROS 2 system, see [**official documentation**](https://docs.ros.org/en/humble/Tutorials/Intermediate/Launch/Creating-Launch-Files.html).