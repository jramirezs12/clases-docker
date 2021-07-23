# Clase 21 de julio:
En esta clase ya se vio un poco mas de practica y la configuracion de nuestro primer entorno docker, lo hicimos utilizando una maquina virtual y MobaXterm para su manipulacion se ejecutaron algunas lineas de codigo, en mi caso copie manualmente las lineas y tambien me funciono, se ejecutaron la seri de comandos que aparecen tanto en el blog del profe como en la pagina de Docker:


* Realizar una actualización:
    sudo apt-get update
    
* sudo apt-get install \
apt-transport-https \
ca-certificates \
curl \
gnupg-agent \
software-properties-common

* curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

* sudo add-apt-repository \
"deb [arch=amd64] https://download.docker.com/linux/ubuntu \
$(lsb_release -cs) \ stable"

* sudo apt-get update

* sudo apt-get install docker-ce docker-ce-cli containerd.io





