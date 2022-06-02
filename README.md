# Criar node_modules
docker run -it -v ${PWD}/app:/projetos/dtmoney node:alpine /bin/sh -c 'cd /projetos/dtmoney && yarn'