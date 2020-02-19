
O Node Version Manager (NVM), como o próprio nome já diz, é uma ferramenta que permite que gerenciar diferentes versões do Node. Você pode instalar cada versão com um único comando e definir um padrão via linha de comando de maneira rápida e prática.

Para a instalação do NVM utilize o seguinte comando no terminal (visite o site do projeto para checar a versão mais atual):

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash

```

Se o terminal não reconhecer o comando curl instale-o com o apt-get:

```
sudo apt-get install curl

```

## Utilizando NVM

Agora vamos ver os principais comando que o NVM provê.

### Verificando a versão

```
nvm --version
```

### Listando completa de versões disponíveis do Node
```
nvm ls-remote node
```

### Instalando versões do Node.js
O NVM nos permite instalar várias versões do Node.js. Basta executar o comando de instalação seguido da versão desejada.
Para instalarmos o Node.js na versão 8.3.0, executamos o seguinte comando:

```
nvm install v12.13.1
```
Para instalar a versão mais recente do Node.js, execute:
```
nvm install node
```
### Listando as versões instaladas
```
nvm ls
```
