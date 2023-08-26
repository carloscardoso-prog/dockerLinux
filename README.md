# dockerLinux
Fixing some problems booting up docker on linux

I had some problems booting up docker on linux (fedora), so i'm documenting everything to help others (and myself) in the future.

Remember to open the terminal in your project folder before running any commands in the terminal.

1- 
systemctl stop docker

2- 
rm ~/.docker/config.json

3- 
systemctl start docker
 

3.5- open docker desktop manually

4- 
docker login
 
5- 
docker context ls

6- 
docker context use desktop-linux

7- 
docker-compose up -d --build


DONT.USE.SUDO.WITH.ANYTHING
Sudo literally makes docker unusable
