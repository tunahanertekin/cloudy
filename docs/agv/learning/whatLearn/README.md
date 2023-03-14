# Warming up: Essential Knowledge before Getting Started
This section is designed to help users who are new to the world of robotics and ROS 2 to get started with the basics. We understand that getting started with robotics and ROS 2 can be intimidating, and that's why we've created this section to provide a gentle introduction to the fundamentals.

Whether you're a student, hobbyist, or professional, this section is designed to provide a solid foundation for your journey into the exciting world of robotics and ROS 2. So let's get started!

## What is ROS? How to use and develop?
<img src="https://raw.githubusercontent.com/robolaunch/cloudy/docs/docs/images/ros-equation.png">


[ROS (Robot Operating System)](https://www.ros.org/) is a popular open-source robotics middleware that provides a collection of software libraries, tools, and frameworks to help developers build complex robotics applications. It was first introduced in 2007 by the Willow Garage Robotics Research Institute and is now maintained by the [Open Robotics](https://www.openrobotics.org/) organization.

ROS is designed to be a flexible and modular system that can be used with a wide range of robotic platforms and sensors. It provides a standardized framework for communicating between different software components in a robot's system, such as sensors, actuators, and controllers. ROS also includes a large and active community of developers who contribute to the development of new tools and packages, making it easy to find and use existing code for common robotic tasks.

Some of the key features of ROS include:

- **Message passing:** ROS uses a message passing system to facilitate communication between different software components in a robot's system.

- **Package management:** ROS provides a package management system that makes it easy to find, download, and install new software components.

- **Visualization tools:** ROS includes a variety of visualization tools that make it easy to visualize sensor data and robot behavior.

- **Simulation tools:** ROS provides a number of simulation tools that enable developers to test their code in a virtual environment before deploying it on a physical robot.

## ROS 1 vs. ROS 2
Here's a table comparing some of the key differences between ROS 1 and ROS 2:

| **Aspect** | **ROS 1** | **ROS 2** |
| ----- | ----- | ----------- |
| Real-time performance | Limited real-time performance capabilities. | Improved real-time performance. |
| Distributed computing | Limited support for distributed computing. | Improved support for distributed computing. |
| Language support | Supports C++ and Python primarily. | Supports C++, Python, and Java. |
| Interoperability | Limited interoperability with other middleware platforms. | Designed to be more interoperable with other systems. |
| Security | Limited security features. | Improved security features, such as authentication and encryption. |
| Development process | Developed more informally by a large community of contributors. | Follows a more structured development process, with a designated development team and release schedule. |
| Backward compatibility | Fully backward compatible. | Not fully backward compatible, some packages and code written for ROS 1 may need to be modified. |

## Why robolaunch Prefers ROS 2?
There are several reasons why someone might choose (also we) ROS 2 over other robotics middleware frameworks or earlier versions of ROS. Here are a few of the main advantages of using ROS 2:

- **Improved real-time performance:** ROS 2 has been designed with real-time performance in mind, making it a better choice for applications that require low latency and high determinism. ROS 2 uses a DDS (Data Distribution Service) middleware layer for communication, which allows for better control of message delivery and prioritization.

- **Better support for distributed systems:** ROS 2 includes improvements to its distributed system architecture, making it easier to work with multi-robot systems and to deploy robotic applications across a network of machines.

- **Improved security:** ROS 2 includes better security features than earlier versions of ROS, including support for authentication and encryption of messages.

- **Easier integration with other systems:** ROS 2 has improved support for integration with other systems, including support for a wider range of programming languages and better interoperability with non-ROS systems.

- **Active development and community support:** ROS 2 is actively developed and maintained by the Open Robotics organization, with regular updates and new features being added. There is also a large and active community of developers and users who contribute to the development of new tools and packages, making it easy to find and use existing code for common robotic tasks.

Overall, ROS 2 offers several significant improvements over earlier versions of ROS and other robotics middleware frameworks, making it a better choice for certain types of robotic applications.
## Most Popular ROS 2 commands
When working with ROS 2, you will likely use a variety of commands to run nodes, view information about topics and nodes, set parameters, and more. Here are some of the most popular ROS 2 commands:

| **Command** | **Action** | 
| --- | --- |
| `ros2core` | Fundamental command that initializes and manages core components of ROS system. It is typically the first command that you run when working with ROS, as it sets up the necessary communication infrastructure for ROS nodes to communicate with each other. |
| `ros2run` | The command `ros2run` launches an executable from a package. Use ros2 run to run a ROS 2 node. `ros2run` makes it easy to run an executable in a package without having to specify the path to the executable. |
| `ros2node` | Various node related sub-commands. Use `ros2node` to view information about ROS 2 nodes. `ros2node` allows you to list, get information about, and manage these nodes in your ROS 2 system. |
| `ros2topic` | Various topic related sub-commands. Use `ros2topic` to view information about ROS 2 topics. It allows you to inspect the status of topics, view messages published on them, and publish messages to them.|
| `ros2msg` | Various msg related sub-commands. Use `ros2msg` to view information about message types. It allows you to inspect the structure of a message and view its contents in a human-readable format. |
| `ros2service` | Various service related sub-commands. `ros2service` provides a set of commands that allow you to interact with ROS 2 services in different ways, such as listing available services, calling a service with a request, or advertising a new service.|
| `ros2param` | Various param related sub-commands. `ros2param` provides a set of commands that allow you to manage parameters in your ROS 2 system, such as getting the value of a parameter, setting a parameter value, or listing all the parameters that are currently available. |
| `ros2service` | Various service related sub-commands. `ros2service` provides a set of commands that a provides a set of commands that allow you to interact with ROS 2 services in different ways, such as listing available services, calling a service with a request, or advertising a new service.  | 

## What is micro-ros?   
[Micro-ROS](https://micro.ros.org/) is a project aimed at bringing the benefits of ROS to microcontrollers and other resource-constrained embedded systems. It provides a lightweight, real-time middleware that allows small embedded systems to communicate with ROS nodes, enabling distributed computing across various hardware platforms.

Micro-ROS is designed to work on a variety of microcontrollers, including those with limited resources such as RAM and flash memory. It provides a way to abstract hardware and enables developers to write portable code that can be easily transferred between different embedded systems.

By enabling ROS on microcontrollers, Micro-ROS opens up new possibilities for robotics and other embedded systems applications. It allows developers to create distributed systems that can handle complex tasks and interactions, and provides a way to easily integrate different hardware and software components into a single system.

<img src="https://raw.githubusercontent.com/robolaunch/cloudy/docs/docs/images/micro-ROS_architecture.png">

## What is Cloud and Why We Need it for Robotics Applications?
Cloud computing refers to the delivery of computing services over the internet, including storage, processing, and analysis of data. In cloud computing, users can access computing resources and services on-demand and pay for what they use, rather than having to maintain their own infrastructure.

In the context of robotics applications, cloud computing offers several benefits:

* **Scalability:** Cloud computing can provide access to vast amounts of computing power and storage, which is useful for applications that require large-scale processing or analysis of data.

* **Collaboration:** Cloud computing enables easy storage and sharing of data among different robots and applications, facilitating collaboration and enabling more advanced applications.

* **Remote Monitoring and Control:** Cloud computing enables remote monitoring and control of robots, allowing them to operate more efficiently and safely in hazardous or remote environments.

* **Cost Savings:** Cloud computing can reduce costs and increase flexibility by allowing users to access computing resources on-demand and pay for what they use, rather than maintaining their own infrastructure.

* **Real-time Processing:** Cloud computing can enable real-time processing of sensor data, allowing robots to make decisions and react quickly to changing conditions.

* **Data Analytics:** Cloud computing can provide powerful data analytics tools, allowing for more advanced analysis and insights into robot performance and behavior.

## robolaunch Cloud Application Examples
You get a unified, off-the-shelf solution to deploy, manage and automate your robots with robolaunch Platform. You can find some example applications you can create by using robolaunch's building blocks/features. 

These applications are just to give some inspiration. There is no limit what you can create with robolaunch!

<img src="https://raw.githubusercontent.com/robolaunch/cloudy/docs/docs/images/robolaunch-applications.png">

## robolaunch Cloudy AGV applications
The [Cloudy](https://www.robolaunch.io/cloudy) robot paltform is a highly flexible and adaptable robot suitable for a wide range of users, including students, educators, hobbyists and professionals. It utilizes micro ROS, ROS 2, Nav 2, ROS 2 Control, NVIDIA, and if desired, [robolaunch Platform](https://www.robolaunch.io/platform), enabling a broad range of functionalities:

* **Basics:** ROS learning
* **Teleoperation:** robot remote control over robolaunch Platform
* **Map Building:** make maps of environments for the robot to use
* **Autonomous Path Planning and Navigation:** Cloudy moves autonomously around your lab, class or office
* **Tele-Viewing:** see what your Cloudy robot sees over robolaunch Platform
* **Simultaneous Localization and Mapping (SLAM):** Cloudy autonomously explores unknown places
* **Computer Vision:** Cloudy recognizes objects in its environment and avoids obstacles

## References
- https://www.ros.org/
- https://www.openrobotics.org/
- https://micro.ros.org/
