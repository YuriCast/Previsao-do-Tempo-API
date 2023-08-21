Este repositótio foi criado utilizando ReactJS, TypeScript e TailwindCSS. Ele também toda no node 18 (veja .nvmrc) e utiliza o formatador - prettier. Se você estiver rodando a aplicação pela primeira vez, por favor, verifique se você possui o nvm (node version manager).

## Como Rodar a Aplicação

Se você não possui o nvm instalado, cole o comando a baixo em seu terminal:
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

Depois de você possuir o nvm baixado em seu computador, use o comando `nvm i` e depois `nvm use` (para ter a versão correta do nodeJs)

Depois de você verificar se possui a versão correta do node, use o comando `npm i` para instalar todas as dependências necessárias

Depois de tudo instalado, use o comando `npm run start` e cole o seguinte URL em seu navegador: http://localhost:3000

## Chamar a API

+++: A OpenWeather API utiliza uma API Key. No repositório você conseguirá encontrar o `.env.example` que você precisa copiar/salvar como `.env` e colar o valor da sua API key (que você consegue ao se registrar no site OpenWeather API).
