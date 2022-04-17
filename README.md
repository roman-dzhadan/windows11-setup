# windows11-setup

### [WSL: Choose & Install Distro](https://docs.microsoft.com/en-us/windows/wsl/install)
- ```wsl --list --online```
- ```wsl --install -d Ubuntu-20.04```

### [Docker Desktop: Install & Enable Additional Distro](https://docs.docker.com/desktop/windows/install)
- ```Settings >> Resources >> WSL Integration >> Enable Integration with Additional Distros >> Ubuntu-20.04```

### [Download & Install MSYS2](https://www.msys2.org/#installation)
https://github.com/msys2/msys2-installer/releases/download/2022-03-19/msys2-x86_64-20220319.exe

### Open MSYS2 Terminal & Install Libraries via Pacman
- ```pacman -Syu```
- ```pacman -Su```
- ```pacman -S --needed base-devel mingw-w64-x86_64-toolchain mingw-w64-x86_64-clang mingw-w64-x86_64-cmake git```
- ```gcc --version```
- ```clang --version```
- ```make --version```
- ```cmake --version```
- ```git --version```
