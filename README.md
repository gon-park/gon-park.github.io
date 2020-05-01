# Description of my projects

# RUN docker
	docker run -p 80:80 --name web -v ./:/usr/share/nginx/html:ro -d nginx
	docker rm -f web

# RUN docker-compose
	docker-compose up -d
	docker-compose down -v