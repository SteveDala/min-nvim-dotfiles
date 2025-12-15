# alpine-nvim-dotfiles
This repo is built from the ground up for lightweight Docker dev containers.

## Example Dockerfile:
```dockerfile
FROM anatolelucet/neovim:latest

RUN apk update
RUN apk add git curl make gcc xclip unzip ripgrep
```
