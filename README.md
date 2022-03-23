# hastebin
Simple hastebin server with redis

Usage:

1. Install docker and doker-compose
2. Clone this repro
3. Run "docker-compose up"

Backups:

In default configuration of this container Redis backups data under /data.
Simply backup appendonly.aof and dump.rmb to different location.
To restore copy it back.
