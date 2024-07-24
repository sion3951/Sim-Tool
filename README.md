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

```sudo apt-get install wget gpg```
```wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg```
```sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg```
```echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" |sudo tee /etc/apt/sources.list.d/vscode.list > /dev/null```
```rm -f packages.microsoft.gpg```

```sudo apt install apt-transport-https```
```sudo apt update```
```sudo apt install code # or code-insiders```

##Install The Repo

```git clone https://github.com/sion3951/Sim-Tool.git```

