## Installing Docker


### Uninstall old versions
```
for package in $(old_docker.txt); do sudo apt remove -y $package; done
```

<br>

The "old_docker.txt" file contains the unoffical packages that need to be uninstalled before installing docker 
<br>
<br>
The "old_docker.txt" file contains the following:

- docker.io
- docker-compose
- docker-compose-v2
- docker-doc
- podman-docker
