# FastStandDeploy

CI/CD: Bitbucket + Jenkins
Virtualisation: Docker, KVM

Back: MongoDB 
Front: nginx

Скачать docker и docker-compose:
		
		sudo apt install docker.io
		sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
		sudo chmod +x /usr/local/bin/docker-compose
		docker-compose --version
		
1) Создать Bitbucket кряк 
	- Для подъема скачать php

		sudo apt install php7.4-cli

	- Копируем Server ID и заменяем его в license_key_bitbucket.txt
	- Генерим ключ командой:

		php atlassian-keygen.php -e license_key_product.txt

    - Активируем продукт

2) Установка KVM? (а там дадут простанство в виде 50ГБ под все нужды?)

3) Залить jenkins и написать, как связать их по webhook

4) Подключить Mongo 

5) Подключить nginx 

6) Определиться с языками ( 1.python 2.c# ?) 
