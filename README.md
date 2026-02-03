# Open Source Technologies Lab - C++ Exercises

This repository contains C++ lab exercises for the Open Source Technologies Lab.

## Project Structure

```
.
├── src/              # Source files (.cpp)
├── include/          # Header files (.h)
├── tests/            # Test files
├── build/            # Build output directory
├── CMakeLists.txt    # CMake configuration
├── .gitignore        # Git ignore rules
└── README.md         # This file
```

## Building the Project

### Prerequisites
- C++17 compatible compiler (GCC, Clang, MSVC)
- CMake 3.10 or higher

### Build Instructions

1. Create a build directory:
   ```bash
   mkdir build
   cd build
   ```

2. Generate build files:
   ```bash
   cmake ..
   ```

3. Build the project:
   ```bash
   cmake --build .
   ```

4. Run the executable:
   ```bash
   ./lab_exercises  # On Linux/Mac
   lab_exercises.exe  # On Windows
   ```

## Lab Exercises

Add your lab exercises here!

## Getting Started

1. Add your C++ source files to the `src/` directory
2. Add header files to the `include/` directory
3. Update `CMakeLists.txt` if needed for additional dependencies
4. Rebuild using CMake

## License

Open Source Technologies Lab
