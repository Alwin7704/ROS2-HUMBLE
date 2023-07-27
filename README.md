# ROS2-HUMBLE
ROS 2 Humble is the eighth release of ROS 2, a set of software libraries and tools that help you build robot applications. It is a free and open-source project that is maintained by the ROS community.

The Humble release includes a number of new features and improvements, including:

+A new build system based on ament and colcon.+
+A new Python API.+
+A new set of tools for working with security.
+A number of bug fixes and performance improvements.

Here are some of the key features of ROS 2 Humble:

Ament: Ament is a new build system for ROS 2 that is based on CMake and colcon. Ament makes it easier to build and manage ROS 2 packages, and it also provides a number of features that make it easier to share and reuse code.
Python API: ROS 2 Humble includes a new Python API that makes it easier to write ROS 2 applications in Python. The Python API is based on the ROS 1 Python API, but it has been updated to take advantage of the new features of ROS 2.
Security: ROS 2 Humble includes a number of new features for working with security. These features make it easier to secure ROS 2 applications, and they also provide a number of tools for auditing and analyzing ROS 2 security.
Bug fixes and performance improvements: ROS 2 Humble includes a number of bug fixes and performance improvements. These fixes and improvements make ROS 2 more stable and efficient.
If you are interested in learning more about ROS 2 Humble, you can visit the ROS 2 documentation website. The documentation website includes a number of tutorials and guides that can help you get started with ROS 2 Humble.

# ROS2 - HUMBLE INSTALLATION for amd64 based devices
Follow the instruction carefully ! 

#Set Locales
Make sure you have a locale which supports UTF-8. If you are in a minimal environment (such as a docker container), the locale may be something minimal like POSIX. We test with the following settings. However, it should be fine if you’re using a different UTF-8 supported locale.

```
locale  # check for UTF-8

sudo apt update && sudo apt install locales
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8

locale  # verify settings
```
