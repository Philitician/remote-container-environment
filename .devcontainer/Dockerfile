FROM node:lts

RUN npm install -g prettier
RUN npm install -g eslint
RUN npm install -g type-coverage
RUN npm install -g json-server

# https://reposhub.com/linux/system-utilities/deluan-zsh-in-docker.html
RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.1.1/zsh-in-docker.sh)" -- \
    -t robbyrussell \
    -p git \
    -p docker \
    -p docker-compose \
    -p https://github.com/zsh-users/zsh-autosuggestions \
    -p https://github.com/zsh-users/zsh-completions
