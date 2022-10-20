# Robo_Arm
Robot Arm is a simulation part of a simple robotic arm which has 4DF and can be moved based on the environment along with the safe moves.

Service definitions always contain two sections, seperated by a '---'

- The first section is the definition of the request message
- The second section contains the service response.

## Modifying CMakeLists.txt
In order for catking to generate the python modules or C++ Libraries which allow you to utilize messages in your code your must ifrst modify `simple_arm`'s CMakeLists.txt.

CMake is the build tool underlying catkin, and CMakeLists.txt is nothing more that a CMake script used by catkin.

