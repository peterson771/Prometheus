
# Monitorando uma aplicação NodeJS

 - Ajustando o arquivo de configuração do Prometheus para acessar o servidor com a aplicação NodeJS 


### Instalação do NodeJS.

    sudo apt update
    sudo apt install nodejs npm
    node -v
    npm -v
    mkdir meu-projeto
    cd meu-projeto
    npm init -y
    npm install express
    npm install prom-client
    vim index.js
    node index.js

### No container do Prometheus faça os ajustes

    cd prometheus-setup
    vim prometheus.yml
    docker container restart prometheus