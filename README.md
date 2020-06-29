
#### Extracts all API endpoints from AngularJS & Angular javascript files ####
curl -s URL | grep -Po “(\/)((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)*((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)((?:[a-zA-Z\-_\/\:\.0–9\{\}]+))” | sort -u

#### Find sensitive files using dirsearch ####
dirsearch -e php,asp,aspx,jsp,py,txt,conf,config,bak,backup,swp,old,db,sql,json,xml,log,js -u <target>
