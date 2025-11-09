# Setup & Usage

## Install Dependencies

### Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install flex bison build-essential make
```

### macOS (Homebrew)
```bash
brew install flex bison make gcc
```

### Windows
- Install [MSYS2](https://www.msys2.org/) or use WSL.
- Inside the MSYS2/WSL shell, run the appropriate package manager:

```bash
# MSYS2
pacman -S flex bison make gcc

# WSL (Ubuntu example)
sudo apt update
sudo apt install flex bison build-essential make
```

## Build the Project

```bash
make
```

## Run the Compiler

```bash
./build/javaco input.java
```
