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

## File modification

`chmod [references][operator][modes] filename` - change permission mode for file
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

`ps` - view running processes
 - `-a`: all

`ln [target] [link name]` - link two files

## Docker

`docker images` - list images
- `-a`: all

`docker ps` - list containers
- `-a`: all

`docker rm -vf $(docker ps -aq)` - delete all containers

`docker rmi -f $(docker images -aq)` - delete all images

## GIT
