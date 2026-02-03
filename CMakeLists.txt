cmake_minimum_required(VERSION 3.10)
project(OST_Lab_Exercises)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include directories
include_directories(include)

# Add source files
file(GLOB_RECURSE SOURCES "src/*.cpp")

# Create executable
add_executable(lab_exercises ${SOURCES})

# Optional: Enable testing
enable_testing()
add_subdirectory(tests)
