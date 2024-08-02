# Enfugue-Android-Termux
Yeah! You can run  Enfugue Webui on Android! I DIDN'T know it existed 😳 






Prerequisites First you have to install Termux and install PRoot. Then install and login to Ubuntu in PRoot


1>


pkg updated && pkg upgrade -y && termux-setup-storage && pkg install wget -y && pkg install git -y && pkg install proot -y && cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh

 Run below commands sequentially as root user in Ubuntu
Install basic tools


2>

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && pip install ffmpeg && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3


3>


pip install enfugue


4>


To Launch

python3 -m enfugue run



