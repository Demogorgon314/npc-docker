# npc-docker
自用，群晖 最新版npc docker 版

## 执行命令
```bash
docker run -d --name npc -e SERVERIP=127.0.0.1:8284 -e VKEY=123 deepdream314/npc:latest
```
or
```bash
docker run -d --name npc --net=host -e SERVERIP=127.0.0.1:8284 -e VKEY=123 deepdream314/npc:latest
```
