# linux working env setup
- Linux CheatSheet:
  - Add user
  ```shell
  sudo adduser <username>
  ```
  - Add username to sudoers (https://www.linuxandubuntu.com/home/fixed-username-is-not-in-sudoers-file)
  ```shell
  sudo usermod -aG sudo <username>
  ```
