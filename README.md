# Nativefier

## Tonton Jo  
### Join the community:
[![Youtube channel](https://github-readme-youtube-stats.herokuapp.com/subscribers/index.php?id=UCnED3K6K5FDUp-x_8rwpsZw&key=AIzaSyA3ivqywNPQz0xFZBHfPDKzh1jFH5qGD_g)](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)
[![Discord Tonton Jo](https://badgen.net/discord/members/h6UcpwfGuJ?label=Discord%20Tonton%20Jo%20&icon=discord)](https://discord.gg/h6UcpwfGuJ)
### Support the channel with one of the following link:
[![Ko-Fi](https://badgen.net/badge/Buy%20me%20a%20Coffee/Link?icon=buymeacoffee)](https://ko-fi.com/tontonjo)
[![Infomaniak](https://badgen.net/badge/Infomaniak/Affiliated%20link?icon=K)](https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35)
[![Express VPN](https://badgen.net/badge/Express%20VPN/Affiliated%20link?icon=K)](https://www.xvuslink.com/?a_fid=TontonJo)  
## Informations:  
For more infos and references please check the gituhb page and catalog  
https://github.com/nativefier/nativefier  
https://github.com/nativefier/nativefier/blob/master/  
https://github.com/nativefier/nativefier/blob/master/CATALOG.md  


## Installation:

### Create Windows app from a website:
```shell
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows https://url /target/  
```
### Create Windows app from a website with firefox agent:
```shell
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --user-agent firefox https://url /target/  
```
### Create Windows app from a website with custom Icon:
```shell
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --icon /target/jo.jpg --user-agent firefox https://url /target/  
```
### Create Windows app from a website with custom name:
```shell
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --name testexe --user-agent firefox https://url /target/  
```
### Create Windows app from a website and disable old build warning (yeah, it's insecure)
```shell
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier --disable-old-build-warning-yesiknowitisinsecure -p windows --user-agent firefox https://url /target/  
```

## Controls in app:
### Show menu bar
ctrl
### Reload page
ctrl + r  
