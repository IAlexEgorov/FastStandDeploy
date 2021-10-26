# FastStandDeploy

CI/CD: Bitbucket + Jenkins
Virtualisation: Docker, KVM

Back: MongoDB 
Front: nginx

1) Создать Bitbucket кряк 
	-Для подъема скачать php

		sudo apt install php7.4-cli

	-Копируем Server ID и заменяем его в license_key_bitbucket.txt
	-Генерим ключ командой:

		php atlassian-keygen.php -e license_key_product.txt

    - Активируем продукт
    
2) Установка KVM? (а там дадут простанство в виде 50ГБ под все нужды?)

3) Залить jenkins и написать, как связать их по webhook

4) Подключить Mongo 

5) Подключить nginx 

6) Определиться с языками ( 1.python 2.c# ?) 
