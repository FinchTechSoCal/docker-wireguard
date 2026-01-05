# docker-wireguard
Wireguard in docker via [LinuxServer.io](https://linuxserver.io/)

Use:
```bash
rm -fr ~/appdata/docker_files/wireguard
git clone https://github.com/FinchTechSoCal/docker-wireguard.git ~/appdata/docker_files/wireguard
```

Modify .env, then

```bash
docker compose -f ~/appdata/docker_files/wireguard/docker-compose.yml up -d
```

[LISO wireguard github](https://github.com/linuxserver/docker-wireguard)