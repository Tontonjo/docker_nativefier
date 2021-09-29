# docker_nativefier
For more infos and references please check the gituhb page and catalog
https://github.com/nativefier/nativefier
https://github.com/nativefier/nativefier/blob/master/CATALOG.md

## Tips:

### 1.1 - Show menu bar
ctrl
### 1.1 - Reload page
ctrl + r  


### 2.1 - Create Windows app from a website:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows https://url /target/  
### 2.2 - Create Windows app from a website with firefox agent:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --user-agent firefox https://url /target/  
### 2.3 - Create Windows app from a website with custom Icon:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --icon /target/jo.jpg --user-agent firefox https://url /target/  
### 2.4 - Create Windows app from a website with custom name:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --name testexe --user-agent firefox https://url /target/  

