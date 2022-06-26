# linux working env setup

### Add user
```shell
sudo adduser <username>
```
Add username to sudoers (https://www.linuxandubuntu.com/home/fixed-username-is-not-in-sudoers-file)
```shell
sudo usermod -aG sudo <username>
```
### ifconfig
Fixed for `ifconfig command not found`
```shell
sudo apt install net-tools
```
```shell
# add to path
nano ~/.bashrc
# add this line to file
# export PATH=$PATH:/sbin
```
