# 1. Criar criar ou atualizar as dependencias (node_modules)
docker run -it -v ${PWD}/app:/projetos/dtmoney node:alpine /bin/sh -c 'cd /projetos/dtmoney && yarn'

# 2. Iniciar app
docker-compose up
