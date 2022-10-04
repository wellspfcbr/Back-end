                                    BACK-END ANOTAÇÕES

INICIAR A CONFIGURAÇÃO DO SERVIDOR
*1* Abrir o terminal do vscode e digitar o comando 'npm init' e continuar a instalação (apertando o enter).Após apertar
enter ele vai instalar o packege.json qué é uma agenda em que vamos anotar todas as bibliotecas que iremos instalar.

*2* Instalar o typeScript, no terminal digite o comando (npm install -g typescript) em seguida instalar os outros pacotes
do typescript: (npx tsc --init) e depois instalar (npm install -D ts-node) em seguida ira aparecer dois arquivos que 
são NODE_MODULES e TSCONFIG.JSON
NODE_MODULES é onde vai ficar todas as bibliotecas que vamos instalar e o ts config.json é a configuraçao do typescript

*3* Ir no arquivo tsconfi.json e descomentar as seguintes linhas de codigo:
moduleResolution:node 
rootDir": "./src //adicionar o src
outDir": "./dist // adicionar o dist

*4* Instalar a biblioteca do TS. Vá no terminal e digite o comando npm isntall --save-dev @types/node

*5* Criar uma pasta na raiz chamada SRC e dentro criar um arquivo Index.ts e colocar algum codigo de sua preferencia para
teste.

*6* em seguida para rodar o projeto vamos instalar o nodemon no temrinal: npm install -g nodemon (o nodemon serve para
rodarmos o projeto automaticamente.)

*7* para rodar i projeto usar o comando nodemon src/index.ts 

***PARAR DE EXECUTAR O TERMINAL CNTRL+C*** 