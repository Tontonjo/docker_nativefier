# docker_nativefier
For more infos and references please check the gituhb page and catalog
https://github.com/nativefier/nativefier
https://github.com/nativefier/nativefier/blob/master/CATALOG.md

### 1.1 - Create Windows app with firefox agent:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows https://url /target/  
### 1.2 - Create Windows app with firefox agent:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --user-agent firefox https://url /target/  
### 1.2 - Create Windows app with custom Icon:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --icon /target/jo.jpg --user-agent firefox https://url /target/  
