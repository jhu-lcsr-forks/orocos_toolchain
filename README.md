Orocos: The Open Robot Control Software
=======================================

[![Build Status](https://travis-ci.org/jhu-lcsr-forks/orocos_toolchain.png)](https://travis-ci.org/jhu-lcsr-forks/orocos_toolchain)

The Orocos Toolchain is your primary tool to create real-time robotics
applications using modular, run-time configurable software components.

The toolchain provides:

* Multi-platform support: Linux, Windows (Visual Studio) and Mac OS-X
* Extensions to other robotics frameworks: ROS, Rock, Yarp
* Code generators to transfer user-defined data between distributed components
* Run-time & real-time configurable and scriptable components
* Logging and reporting of system events and communicated data.

The toolchain consists of:

* The Real-Time Toolkit, a component framework that allows us to write real-time components in C++
* The Orocos Component Library, the necessary components to start an application and interact with it at run-time
* OroGen and TypeGen, tools to generate ready-to-compile-and-run code from existing headers or component description files
* AutoProj, A tool to download and compile the necessary libraries (optional)

Components built by users of Orocos are hosted in their own repositories.
