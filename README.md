# getpass 1.2.14
## password manager with gnupg encryption for debian based linux distributions
<hr>

### Dependencies
```
sudo apt install gnupg 
sudo apt install qrencode
```

### Download
```
curl https://debian.initiatio.pl/getpass_1.2.14_all.deb -O getpass_1.2.14_all.deb
```
### Installation
```
dpkg -i ./getpass_1.2.14_all.deb
or
sudo apt install getpass_1.2.14_all.deb

rm ./getpass_1.2.14_all.deb

getpass create-bcv
getpass set-key user@domain.com
```
### Commands List
```
create-bcv                       - sets bcv ( blackcat vault) folder location
set-key                          - sets gpg key
help                             - shows this help
version                          - shows version
v                                - shows version

add                              - adds record
add-a         HOST USER PHRASE   - adds record
add-comment   TOKEN COMMENT      - adds comment to record
add-c         TOKEN COMMENT      - adds comment to record
add-file      TOKEN PATHTOFILE   - adds file to record
add-f         TOKEN PATHTOFILE   - adds file to record
get           TOKEN              - gets full record
get-qr        TOKEN              - gets qr code 
qr            TOKEN              - gets qr code 
remove        TOKEN              - removes record
rm            TOKEN              - removes record
search-host   PHRASE             - search in hosts
sh            PHRASE             - search in hosts
search-user   PHRASE             - search in users
su            PHRASE             - search in users
list                             - gets all records
ls                               - gets all records
```

## Changelog

### Planned New Functionality
 - [X] Internal GPG key
 - [ ] External GPG key 
   - [ ] importing and droping key
 - [ ] External .bcv path
   - [ ] Tomb support
 - [ ] Install script
   - [ ] Preinstall script
   - [ ] Postinstall script

### 1.2.14 Standalone Release
- [x] Moved from blackcat-termux to standalone deb package.
- [x] Separate gpg key from blackcat env





## Download
[getpass_1.2.14_all.deb]( https://debian.initiatio.pl/getpass_1.2.14_all.deb)
