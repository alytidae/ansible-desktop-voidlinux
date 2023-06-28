## ansible-desktop-voidlinux
Are you tired of the long manual setup of your Linux after installation? Then this project will help you! 

This is my ansible playbook, which will configure Void Linux for you the same way it is configured for me. This is my personal project, so it does not pretend to be universal, but it can be very useful if you are writing your ansible playbook or setting up your Void!

## Installation
This playbook is written in such a way as to run it locally, but I will also show what can be changed so that it can be run via ssh

### Locally 
1. Minimally install your Void. Reboot after xchroot
2. Log in to your root
3.  Install dependencies
```
# xbps-install -S python3 git ansible
```
4. Clone this repository
```
# git clone https://github.com/alytidae/ansible-desktop-voidlinux.git
```
5. Go to the repository
```
# cd ansible-desktop-voidlinux
```
6. In ``defaults/main.xml`` change the username, password and other
8.  Launch playbook
```
# ansible-playbook playbook.yml
```

## License
Licensed under [The MIT License](https://opensource.org/license/mit/)

