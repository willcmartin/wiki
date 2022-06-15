# Terminal Commands

## Common utilities

`ls` - list files
- `-l`: long list
- `-h`: human-readable
- `-a`: all
- `-G`: no group names
- `-F`: add indicator

`df` - disk space
- `-h`: human-readable
- `-a`: all

`ps` - view running processes
 - `-a`: all

`ln <target> <link_name>` - link two files

## Redirection/Operators

`>` - output to

`>>` - append to

`<` - input from

`|` - pipe

`-` - stdin/stdout

## File modification

`chmod [references][operator][modes] <filename>` - change permission mode for file
- references:
  - `u`: user
  - `g`: group
  - `o`: other
  - `a`: all
- operator:
  - `+`: add
  - `-`: remove
  - `=`: explicitly set
- modes:
  - `r`: read
  - `w`: write
  - `x`: execute

## Docker

`docker build` - builds Docker images from a Dockerfile
- `-t`: tag, name you docker image

`docker run` - derive container from image
- `--rm`: clean up, remove file system when container exits
- `-it`: interactive
- `--gpus <device>`: use gpu, (device=1,2,...,all)
- `-v`: volume
- `-e`: environment variable

`docker cp <source> <container>:<dest>` - copy file/folder to docker container

`docker images` - list images
- `-a`: all

`docker ps` - list containers
- `-a`: all

`docker rm -vf $(docker ps -aq)` - delete all containers

`docker rmi -f $(docker images -aq)` - delete all images

## GIT
