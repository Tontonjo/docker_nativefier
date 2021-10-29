# Nativefier

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo  
If you find this usefull, please consider supporting my work: [Subscribe to my youtube channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)  
<a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> <a href="https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> </a> <a href="https://www.xvinlink.com/?a_fid=TontonJo"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/79/ExpressVPN-logo.svg/261px-ExpressVPN-logo.svg.png"></a>  

## Informations:  
For more infos and references please check the gituhb page and catalog  
https://github.com/nativefier/nativefier  
https://github.com/nativefier/nativefier/blob/master/CATALOG.md  
## Installation:

### Create Windows app from a website:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows https://url /target/  
### Create Windows app from a website with firefox agent:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --user-agent firefox https://url /target/  
### Create Windows app from a website with custom Icon:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --icon /target/jo.jpg --user-agent firefox https://url /target/  
### Create Windows app from a website with custom name:
docker run --rm -v /path/to/docker/nativefier/apps/:/target/ nativefier/nativefier -p windows --name testexe --user-agent firefox https://url /target/  

## Commands:

### Show menu bar
ctrl
### Reload page
ctrl + r  
