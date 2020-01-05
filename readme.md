### Install
- ./install-docker-register.sh

#### Host Use
- Add insecure registry 
vim /etc/docker/daemon.json
 ```json
    {
      "insecure-registries" : ["jllado-server:5000"]
    }
 ```
