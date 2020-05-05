sudo apt update
exit
sudo apt update
ls
sudo apt install curl
ls
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker spring
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
reboot
sudo reboot
ls
docker --version
docker-compose --version
docker run -d --restart=always -e PASSWORD=1234 -p 0.0.0.0:8089:8089 -v ${HOME}/.local/share/code-server:/home/coder/.local/share/code-server -v $(pwd):/home/spring -u "$(id -u):$(id -g)" codercom/code-server:latest --port 8089
docker ps -a
docker ps-sa
docker ps -a
docker exec -it relaxed_gates /bin/bash
docker ps -a
docker stop relaxed_gates
docker run -d --restart=always -e PASSWORD=1234 -p 0.0.0.0:8089:8089 -v ${HOME}/.local/share/code-server:/home/spring/.local/share/code-server -v $(pwd):/home/spring -u "$(id -u):$(id -g)" codercom/code-server:latest --port 8089
docker ps -a
docker rm relaxed_gates
sudo sysctl -w vm.max_map_count=262144
cd elasticsearch/
ls
docker-compose up
docker ps -a
docker-compose down
docker ps -a
docker-compose up -d
docker-compose logs -f
docker ps- a
docker-compose ps
exit
ls
exit
docker ps -a
ls
git init
sudo apt install git
git init
git remote add origin https://byungchul@bitbucket.org/springgos/dockerize.git
git status
cd elasticsearch/
ls
vi docker-compose.yml
exit
~