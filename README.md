# Script déploiement Centreon pour Wazo Payant

This script has been writed by Kévin Perez for AtConnect Anglet

![asciicast](http://www.atconnect.net/images/header/logo.png)
![image](https://image.noelshack.com/fichiers/2019/17/3/1556112297-telechargement.png)

## Compatible with Debian 7/8/9 only.
#### Need Bash 4.2 at least to run.

# Step 1 - Run update and install git
```
apt-get update && apt-get install git-core -y && apt-get install curl -y

```
# Step 2 - Clone the repository and install it
```
cd /tmp
git clone https://github.com/AtConnect/ScriptWazoPayantDeploiement
cd ScriptWazoPayantDeploiement
chmod a+x lancercescriptsurwazopayant.sh
./lancercescriptsurwazopayant.sh
```


## Versions
- **1.0** Kévin Perez
  - *New:* Repository added
  - *New:* Fix for services syntax


### If your key is outdated, update your key like that
```
wget http://mirror.xivo.solutions/xivo_current.key -O - | apt-key add -
```
