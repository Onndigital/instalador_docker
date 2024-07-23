# Whaticket instalador com docker
Instalação com docker / Ubuntu 22

Adcione manualmente o usuário deploy:

useradd -m -p [[senhadeploy]] -s /bin/bash -G sudo deploy</br>
usermod -aG sudo deploy

cd /home</br>
sudo apt install -y git && git clone https://github.com/Onndigital/instalador_docker.git instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria


wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel

docker run --name pluszap -e POSTGRES_USER=pluszap -e POSTGRES_PASSWORD=pluszap -p 5432:5432 -v /data:/var/lib/postgresql/data3 -d postgres

apt install software-properties-common
add-apt-repository --help

 
