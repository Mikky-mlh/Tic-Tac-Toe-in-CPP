# Contributing

Thanks for your interest in contributing to Tic-Tac-Toe-in-CPP! This document explains how to get started.

## Getting the code
1. Fork the repository on GitHub.
2. Clone your fork locally:
   git clone https://github.com/Mikky-mlh/Tic-Tac-Toe-in-CPP.git
   cd Tic-Tac-Toe-in-CPP

## Development setup (Windows)
We recommend using Visual Studio (MSVC) or MinGW with CMake. For dependencies we suggest vcpkg.

### Using vcpkg (recommended)
1. Install vcpkg: https://github.com/microsoft/vcpkg
2. Install dependencies (example):
   cd C:/vcpkg
   .\bootstrap-vcpkg.bat
   .\vcpkg install sfml:x64-windows
3. When configuring CMake, pass the vcpkg toolchain file:
   cmake -S . -B build -DCMAKE_TOOLCHAIN_FILE=C:/vcpkg/scripts/buildsystems/vcpkg.cmake

## Building
Using CMake:
   mkdir build && cd build
   cmake .. -DCMAKE_BUILD_TYPE=Debug
   cmake --build . --config Debug

Or, for simple single-file changes, compile with g++ (MinGW) as appropriate.

## How to contribute
- Create a branch named: feat/your-feature or fix/issue-number-description
- Make small, focused commits with clear messages.
- Open a Pull Request against the `main` branch and reference the issue (e.g., "Closes #1").

## Coding style
- Keep code simple and readable.
- Prefer C++17 features where appropriate.

## Reporting issues and pull requests
- Use the issue templates provided in `.github/ISSUE_TEMPLATE/` when opening issues.
- Fill the PR template when opening a pull request.

Thank you for contributing!
