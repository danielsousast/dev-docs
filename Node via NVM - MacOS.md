
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
Agora o NVM está disponível apra que possamos instalar a versão desejada do Node. O NVM possui alguns comandos disponíveis, para ver todos eles execute ***nvm --help**. 

Para ver todas as versões do Node disponíveis para download execute:

```
nvm ls-remote
```
Agora execute o comando nvm install **<version>** abaixo para instalar a versão desejada:

```
nvm install -s v12.14.1
```

Pronto, agora o Node está instalado no seu Mac.
