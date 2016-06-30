# Alpine Linux Teamspeak 3 Docker Image

#### Specs:
Alpine Linux: 3.4

glibc: 2.23-r3

Teamspeak 3: 3.0.12.4

Size: 24.57 MB

#### Run:
```
docker run -d --name teamspeak -p 9987:9987/udp hafenio/teamspeak
```
#### Server Admin Token & Admin Account
You can find it in the logs with:
```
docker logs teamspeak
```

#### Ports:

* 9987/udp: Default Port
* 30033/tcp: Filetransfer Port
* 10011/tcp: Serverquery Port
