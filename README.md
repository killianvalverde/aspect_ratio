### aspect_ratio ###

aspect_ratio compute the aspect ratio of a source using a target. For more information use 
`aspect_ratio --help` command.

### Build ###

Use the folowing commands to buil the CMake project and install it :

    Create a directory to hold the build output and generate the native build scripts:
            $ cmake -H. -Bbuild

    Compile the project directly from CMake using the native build scripts:
            $ cmake --build build

    Install the binary in your environment:
            $ sudo cmake --install build

#### Dependencies ####

In order to compile this software you have to use a C++ revision equal or highter to C++17 
(ISO/IEC 14882:2017). Also the following tools and libraries are necessary with a version equal or 
highter the specified one:
- GCC 8.3.0 (sudo apt-get install g++)
- CMake 3.15 (http://www.cmake.org/)
- speed (https://github.com/KillianValverde/speed)
