
# Instalando Node via NVM no MacOS

A melhor forma para instalar o Node em nossa máquina é através do **NVM**, que é um gerenciador de versões do Node. Instalaremos o NVM através do Gerenciador de pacotes Homebrew

## Instalando Homebrew
Uma ótima forma de instalar pacotes no macOS é através do Homebrew. Para instalar basta executar o comando no seu terminal:

``` 
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Instalando NVM
Com o Homebrew instalado vamos instalar o NVM. Para isso execute o seguinte comando em seu terminal:

``` 
brew install nvm
```
## Utilizando NVM

Agora o NVM está disponível apra que possamos instalar a versão desejada do Node. O NVM possui alguns comandos disponíveis, para ver todos eles execute ***nvm --help**. 


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
