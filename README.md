# byol

### build docker image 
`docker build -t reproduce-cve-2019-11043 .`
### run docker image 
`docker run --rm -ti -p 8080:80 reproduce-cve-2019-11043`
### test exploit 
`docker run --rm --net=host ypereirareis/cve-2019-11043 <ip>:8080/script.php`

### docker install script if you're using kali 
`https://gist.githubusercontent.com/decidedlygray/1288c0265457e5f2426d4c3b768dfcef/raw/9a50356da74e6cd271e0b00902783cfa39c6535b/kali_docker_install.sh`


## steps to create 
* install docker using the script above
* add flag to box
* in the passwords.txt file add the credentials for a user in box
