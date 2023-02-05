<p align="center">
  <a href="#" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>
docker-compose.yml:

version: '2'
services:
  web:
    build: .
    image: shaimaalsharif/nest-repo-1:3.0
    restart: always
    environment:
      NODE_ENV: development
    ports:
      - "80:5000"
    command: npm start
  

   
