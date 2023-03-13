# What You Will Learn in This Module
This section is designed to help users who are new to the world of robotics and ROS 2 to get started with the basics. We understand that getting started with robotics and ROS 2 can be intimidating, and that's why we've created this section to provide a gentle introduction to the fundamentals.

In this section, we will cover the basics of robotics, including what is ROS, how it works, and the how to use it to make up a robot. We'll also introduce you to ROS 2, explaining what it is, why it's useful, and the key concepts you need to understand to get started.

We'll start with the basics of programming, including the programming languages commonly used in robotics, and the concepts and tools you'll need to start writing your own programs. We'll then move on to the ROS 2 architecture, explaining how it's structured and the key concepts you need to understand to start building your own robotics applications.

Throughout this section, we'll provide hands-on examples and exercises to help you apply what you've learned and build your own simple robotics applications. By the end of this section, you should have a solid understanding of the fundamentals of robotics and ROS 2, and be ready to start building your own robotics projects with confidence.

Whether you're a student, hobbyist, or professional, this section is designed to provide a solid foundation for your journey into the exciting world of robotics and ROS 2. So let's get started!

## What is ROS? How to use and develop?
[ROS (Robot Operating System)](https://www.ros.org/) is a popular open-source robotics middleware that provides a collection of software libraries, tools, and frameworks to help developers build complex robotics applications. It was first introduced in 2007 by the Willow Garage Robotics Research Institute and is now maintained by the [Open Robotics](https://www.openrobotics.org/) organization.

ROS is designed to be a flexible and modular system that can be used with a wide range of robotic platforms and sensors. It provides a standardized framework for communicating between different software components in a robot's system, such as sensors, actuators, and controllers. ROS also includes a large and active community of developers who contribute to the development of new tools and packages, making it easy to find and use existing code for common robotic tasks.

Some of the key features of ROS include:

- **Message passing:** ROS uses a message passing system to facilitate communication between different software components in a robot's system.

- **Package management:** ROS provides a package management system that makes it easy to find, download, and install new software components.

- **Visualization tools:** ROS includes a variety of visualization tools that make it easy to visualize sensor data and robot behavior.

- **Simulation tools:** ROS provides a number of simulation tools that enable developers to test their code in a virtual environment before deploying it on a physical robot.

## Why robolaunch prefers ROS 2?
There are several reasons why someone might choose (also we) ROS 2 over other robotics middleware frameworks or earlier versions of ROS. Here are a few of the main advantages of using ROS 2:

- **Improved real-time performance:** ROS 2 has been designed with real-time performance in mind, making it a better choice for applications that require low latency and high determinism. ROS 2 uses a DDS (Data Distribution Service) middleware layer for communication, which allows for better control of message delivery and prioritization.

- **Better support for distributed systems:** ROS 2 includes improvements to its distributed system architecture, making it easier to work with multi-robot systems and to deploy robotic applications across a network of machines.

- **Improved security:** ROS 2 includes better security features than earlier versions of ROS, including support for authentication and encryption of messages.

- **Easier integration with other systems:** ROS 2 has improved support for integration with other systems, including support for a wider range of programming languages and better interoperability with non-ROS systems.

- **Active development and community support:** ROS 2 is actively developed and maintained by the Open Robotics organization, with regular updates and new features being added. There is also a large and active community of developers and users who contribute to the development of new tools and packages, making it easy to find and use existing code for common robotic tasks.

Overall, ROS 2 offers several significant improvements over earlier versions of ROS and other robotics middleware frameworks, making it a better choice for certain types of robotic applications.
## Most Popular ROS2 commands
When working with ROS 2, you will likely use a variety of commands to run nodes, view information about topics and nodes, set parameters, and more. Here are some of the most popular ROS 2 commands:

| **Command** | **Action** | **Example Usage** |
| --- | --- | ----------- |
| `ros2core` | Fundamental command that initializes and manages core components of ROS system. It is typically the first command that you run when working with ROS, as it sets up the necessary communication infrastructure for ROS nodes to communicate with each other. |  |
| `ros2run` | The command `ros2run` launches an executable from a package. Use ros2 run to run a ROS 2 node. `ros2run` makes it easy to run an executable in a package without having to specify the path to the executable. |  |
| `ros2node` | Various node related sub-commands. Use `ros2node` to view information about ROS 2 nodes. `ros2node` allows you to list, get information about, and manage these nodes in your ROS 2 system. |  |
| `ros2topic` | Various topic related sub-commands. Use `ros2topic` to view information about ROS 2 topics. It allows you to inspect the status of topics, view messages published on them, and publish messages to them.|  |
| `ros2msg` | Various msg related sub-commands. Use `ros2msg` to view information about message types. It allows you to inspect the structure of a message and view its contents in a human-readable format. |  |
| `ros2service` | Various service related sub-commands. `ros2service` provides a set of commands that allow you to interact with ROS 2 services in different ways, such as listing available services, calling a service with a request, or advertising a new service.|  |
| `ros2param` | Various param related sub-commands. `ros2param` provides a set of commands that allow you to manage parameters in your ROS 2 system, such as getting the value of a parameter, setting a parameter value, or listing all the parameters that are currently available. |  |
| `ros2service` | Various service related sub-commands. `ros2service` provides a set of commands that a provides a set of commands that allow you to interact with ROS 2 services in different ways, such as listing available services, calling a service with a request, or advertising a new service.  | |  |


## What is Cloud and why we need it for robotics applications?


## robolaunch cloud application examples


## What is micro-ros?    


## robolaunch Cloudy AGV applications


## References
- https://www.ros.org/
- https://www.openrobotics.org/
