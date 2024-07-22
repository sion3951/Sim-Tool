# Sim-Tool

## WSL install instructions:

Open cmd

```wsl --install```

reboot PC

WSL will now be installed as a program.


##Set up WSL/Ubuntu

```sudo apt update && sudo apt upgrade```

```sudo apt-get install cmake git g++ gcc build-essential vulkan-sdk```

```wget -qO- https://packages.lunarg.com/lunarg-signing-key-pub.asc | sudo tee /etc/apt/trusted.gpg.d/lunarg.asc```
```sudo wget -qO /etc/apt/sources.list.d/lunarg-vulkan-1.3.283-jammy.list https://packages.lunarg.com/vulkan/1.3.283/lunarg-vulkan-1.3.283-jammy.list```
```sudo apt update```
```sudo apt install vulkan-sdk```

```export CMAKE_CURRENT_SOURCE_DIR=./```