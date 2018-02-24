# Starter django nginx gunicorn project in docker
    
Add line to /etc/hosts

    127.0.0.1 example.dj

Then

    git clone https://github.com/MichaelPavlov/django-nginx-gunicorn-in-docker/
    cd django-nginx-gunicorn-in-docker
    sudo docker-compose build
    sudo docker-compose up
    
http://example.dj
