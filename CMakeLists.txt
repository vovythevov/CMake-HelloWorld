#
# Create a very simple CMake project
#

cmake_minimum_required (VERSION 2.6) 
set (Project_Name SauronSong)
project (${Project_Name})

add_executable (${Project_Name} SauronSong.cxx)