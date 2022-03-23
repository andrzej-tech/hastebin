# hastebin
Simple hastebin server with redis
https://hub.docker.com/r/rlister/hastebin

## Usage:

1. Install docker and docker-compose
2. Clone this repro
3. Run "docker-compose up"

## Backups:

In default configuration of this container Redis backups data under /data.
Simply backup "appendonly.aof" and "dump.rdb" to different location.
To restore copy it back.
