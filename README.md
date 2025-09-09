# Physics--Gravity# Particle and Gravity Simulations with SFML

This project contains several physics-based simulations implemented using **C++17** and **SFML 2.6.1**.  
It demonstrates gravitational interactions, particle collisions, atomic models, and various visual patterns such as galaxies and spirals.

**Note:** This is my first experience working with C++.  
For this project, I studied Newton's laws of motion and gravity to better understand and implement the physics simulations.

---

## Features
- Binary Star Dance  
- Swirling Galaxy  
- Magnetic Spiral Chaos  
- Chaotic Spiral  
- Atoms Cloud Simulation  
- Lattice Pattern Simulation  
- Exploding Supernova  
- Orbital Ring  
- Galactic Collapse  
- Electric Dipole Oscillation  

---

## Requirements
- Visual Studio 2022 (Desktop development with C++)  
- [vcpkg](https://github.com/microsoft/vcpkg) installed  

---

## How to Install vcpkg

This project uses [vcpkg](https://github.com/microsoft/vcpkg) as a package manager to automatically download and build dependencies (like SFML).

### Windows (PowerShell)
```powershell
# Clone vcpkg (for the first time)
git clone https://github.com/microsoft/vcpkg %USERPROFILE%\vcpkg

# Bootstrap vcpkg
%USERPROFILE%\vcpkg\bootstrap-vcpkg.bat

# (Optional) Add vcpkg to PATH for easier usage
setx PATH "%PATH%;%USERPROFILE%\vcpkg"

## How to Run the Project:


Option 1: Download Prebuilt Executable
If you don't want to build the project yourself, you can download a ready-to-run ZIP file containing Universe.exe and all required DLLs from the Releases page on GitHub.



Option 2: Build from Source

Clone the repository and configure with CMake:
git clone https://github.com/<your-username>/Universe.git
cd Universe
cmake -B build -S . -G "Visual Studio 17 2022" -A x64 -DCMAKE_TOOLCHAIN_FILE="%USERPROFILE%\vcpkg\scripts\buildsystems\vcpkg.cmake" -DVCPKG_TARGET_TRIPLET=x64-windows


Notes

Dependencies are defined in vcpkg.json.

