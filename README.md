# Whaticket instalador com docker
Instalação com docker / Ubuntu 22

Adcione manualmente o usuário deploy:

useradd -m -p [[senhadeploy]] -s /bin/bash -G sudo deploy
usermod -aG sudo deploy

cd /home
ls
sudo apt install -y git && git clone https://github.com/launcherbr/saasinstalador_docker.git saasinstalador_docker && sudo chmod -R 777 saasinstalador_docker && cd saasinstalador_docker && sudo ./install_primaria

 
