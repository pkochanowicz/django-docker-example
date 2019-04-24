# django-rest-cms-docker
A Django 2.2 fresh template made using Docker
Steps:
1 - Install Docker Desktop - https://docs.docker.com/docker-for-windows/install/ (version 1.13.0 or higher)

2 - Clone the repository

3 - Run "docker-compose up" command in terminal

4 - Execute django specific terminal commands with "docker-compose run web django-admin" . For example "docker-compose run web django-admin createsuperuser", "docker-compose run web django-admin migrate". (In case of linux use "sudo docker-compose run web django-admin")
