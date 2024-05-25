## Installing Docker


### Uninstall old versions
```
for package in $(cat old_docker.txt); do sudo apt-get remove -y $package; done
```

<br>

The "old_docker.txt" file contains the unoffical packages that need to be uninstalled before installing docker, the `cat` command will display the contents within the file, allowing `package` variable to iterate eache package.
<br>
<br>
The "old_docker.txt" file contains the following:

- docker.io
- docker-compose
- docker-compose-v2
- docker-doc
- podman-docker
