# Enfugue-Android-Termux
Yeah! You can run  Enfugue Webui on Android! I DIDN'T know it existed 😳 






Prerequisites First you have to install Termux and install PRoot. Then install and login to Ubuntu in PRoot


1>


pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh


 Run below commands sequentially as root user in Ubuntu
Install basic tools


2>

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && pip install ffmpeg && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3


3>


pip install enfugue


4>

pip install diffusers==0.26.0

5>


To Launch

python3 -m enfugue run



