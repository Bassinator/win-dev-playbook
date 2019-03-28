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
  sudo apt install ansible python-pip
```
* intall pywinrm (python winrm support)
```
  pip install pywinrm
```
