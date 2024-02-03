# Whaticket instalador com docker
Instalação com docker / Ubuntu 22

Adcione manualmente o usuário deploy:

useradd -m -p [[senhadeploy]] -s /bin/bash -G sudo deploy</br>
usermod -aG sudo deploy

cd /home</br>
sudo apt install -y git && git clone https://github.com/Onndigital/instalador_docker.git instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria

 
