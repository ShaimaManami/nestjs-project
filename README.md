<p align="center">
  <a href="#" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

<h4>docker-compose.yml:</h4>
<br/>
<p>
version: '2'
<br/>
services:
<br/>
  web:
  <br/>
    build: .
    <br/>
    image: shaimaalsharif/nest-repo-1:3.0
    <br/>
    restart: always
    <br/>
    environment:
    <br/>
      NODE_ENV: development
      <br/>
    ports:
    <br/>
      - "80:5000"
      <br/>
    command: npm start
    <br/>
    
</p>
  

   
