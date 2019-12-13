# byol

### build docker image 
`docker build -t reproduce-cve-2019-11043 .`
### run docker image 
`docker run --rm -ti -p 8080:80 reproduce-cve-2019-11043`
### test exploit 
`docker run --rm --net=host ypereirareis/cve-2019-11043 http://127.0.0.1:8080/script.php`
