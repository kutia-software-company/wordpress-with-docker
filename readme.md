<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your wordpress project in docker.

### Instalation
1. Create directory where you want to clone repository
```sh
mkdir yourproject && cd yourproject
```
2. Clone the repo on directory
```sh
git clone https://github.com/kutia-software-company/wordpress-with-docker.git .
```
3. Run docker compose
```sh
docker-compose up -d --build
```

open in browser:
```
http://locahost:8000
```

Inside src folder you can see wordpress contents here you can work your plugin or theme

![Select Language](https://docs.docker.com/samples/images/wordpress-lang.png)

![Setup](https://docs.docker.com/samples/images/wordpress-welcome.png)

if you want to access in phpmyadmin:
```
http://localhost:8181/
```
username: wordpress
password: wordpress

you can change all information in .env file