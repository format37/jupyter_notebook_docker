# jupyter notebook docker
Store your jupyter notebook server in docker container with gpu support   
### installation
You will need an installed portainer to get connection token
1. Clone repo:
```
git clone https://github.com/format37/jupyter_notebook_docker.git
cd jupyter_notebook_docker
```
2. define your GPU's in docker-compose.yml   
3. select and uncomment actual for your tasks image in jupyter/Dockerfile   
[More jupyter images](https://hub.docker.com/u/jupyter)
```
./compose.sh
```
4. Open docker container's logs and get connection string   
5. Paste connection string in browser and go. All files will be stored in mounted volume work/

