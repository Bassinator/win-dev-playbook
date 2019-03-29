# win-dev-playbook
install development tools on windows

## prerequisites
* Windows Subsystem for Linux (WSL) enabled
```
  Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
* install linux (I use ubuntu, so it's best supported)
[Windows Subsystem for Linux Installation Guide for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
* install ansible and python-pip (python package manager)
```
  sudo apt-get install ansible python-pip
```
* intall pywinrm (python winrm support)
```
  pip install pywinrm
```
* of follow the instructions of Jeff Geerling
https://www.jeffgeerling.com/blog/2017/using-ansible-through-windows-10s-subsystem-linux


## install sshd on WSL to enable remote access to linux bash console
* install openssh-server
```
  sudo apt-get install openssh-server 
```

## side notes


* install hyper-v
  run powershell as administrator
  ```
  Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
  ```
