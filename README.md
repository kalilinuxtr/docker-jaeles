# docker-jaeles

Build:	
```
  docker run -t docker-jaeles .
```
Help:
```
  docker run -t --rm docker-jaeles -h
```
Scan:
```
	docker run -t --rm  docker-jaeles scan -u https://kali-linuxtr.net
```
Web Ui
```
	docker run -d -p 5000:5000 --name jaeles-server docker-jaeles server --host 0.0.0.0
```
