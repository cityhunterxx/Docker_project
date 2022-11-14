docker run -it -d --name apache2-container -v /home/cithunter/Training/Docker/cityhunter-website-apache/site:/var/www/html -e TZ=UTC -p 8080:80 ubuntu/apache2:2.4-22.04_beta


docker run -it -d --name nginx-container -v /home/cithunter/Training/Docker/cityhunter-website-nginx/site:/var/www/html  -e TZ=UTC -p 8086:80 ubuntu/nginx:1.18-22.04_beta

