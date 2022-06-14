# Terminal Commands

## Common utilities

`ls` - list files
- `-l`: long list
- `-h`: human-readable
- `-a`: all
- `-G`: no group names

`df` - disk space
- `-h`: human-readable
- `-a`: all

## Docker

`docker images` - list images
- `-a`: all

`docker ps` - list containers
- `-a`: all

`docker rm -vf $(docker ps -aq)` - delete all containers

`docker rmi -f $(docker images -aq)` - delete all images
