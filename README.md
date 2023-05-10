# innovation_lab
Hacking lab for Security SW Lab, Samsung Device Solutions.

## Lecture 2
### Challenge
- We will cover [basic_rop_x64](https://dreamhack.io/wargame/challenges/29/) challenge in Dreamhack.

### Reading
- [STAGE 5~7](https://dreamhack.io/lecture/roadmaps/2) in Dreamhack System Hacking roadmap for whom less famaliar with return oriented programming. 

### Requirements
- Ubuntu 22.04.2 virtual machine
  - You may use Oracle Virtualbox and Ubuntu Server [.iso file](https://ubuntu.com/download/server) to create a virtual machine.
- Run following commands in your home directory after install.

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install gcc git wget python3 python3-dev python3-pip libssl-dev libffi-dev build-essential software-properties-common tmux -y
git clone https://github.com/pwndbg/pwndbg .pwndbg
cd .pwndbg && ./setup.sh
echo "export PATH=\"$PATH:/usr/local/lib/python3.10/dist-packages/bin\"" >> $HOME/.bashrc
```
