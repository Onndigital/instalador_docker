# Whaticket instalador com docker
Instalação com docker / Ubuntu 22

Adcione manualmente o usuário deploy:

useradd -m -p [[senhadeploy]] -s /bin/bash -G sudo deploy</br>
usermod -aG sudo deploy

cd /home</br>
sudo apt install -y git && git clone https://github.com/Onndigital/instalador_docker.git instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria


wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel

//###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##@///


 
