# jupyter notebook docker
Store your jupyter notebook server in docker container with gpu support   
[current tf-gpu docker image](https://hub.docker.com/r/yhavinga/jupyter-tensorflow-pytorch-gpu)
### installation
You will need an installed portainer to get connection token
1. Clone repo:
```
git clone https://github.com/format37/jupyter_notebook_docker.git
cd jupyter_notebook_docker
```
2. define your GPU's in docker-compose.yml   
3. define your work path on the left side, in volumes: section, in docker-compose.yml   
4. select and uncomment actual for your tasks image in jupyter/Dockerfile   
[More jupyter images](https://hub.docker.com/u/jupyter)
```
./compose.sh
```
5. Open docker container's logs and get connection string   
6. Paste connection string in browser and go.   
Only files, stored in mounted volume work/ will be saved after container's restart.

