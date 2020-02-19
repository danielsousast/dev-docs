
# Ambiente React native no Linux(Ubuntu)

## Node

Para Instalar o Node a maneira mais adequada é através do Gerenciador de Versionaemnto do Node - NVM., Ele nos permite instalar várias versões do Node e alternar entre elas de maneira fácil. Clique aqui para saber como instalr o Node via NVM n o Linux.

## Instalando Yarn

## JDK

Geralmente, aplicativos nativos para Android são criados em Java. Então Java Development Kit é necessário. Para instalar execute:

```
sudo apt install openjdk-8-jdk
```
## Android Studio
Pode ser baixado diretamente no site oficial. Porém uma maneira pŕatica é através do snap:

```
sudo snap install android-studio --classic
```
Finalizada a instalação abra o Android Studio e siga as intruções. 

## Configurando variáveis de ambiente
Agora algumas variáveis de ambiente precisam ser configuradas para criar aplicativos com código nativo.

```
sudo vim $HOME/.bashrc
```
Eu estou usando o editor de texto vim, você pdoe usar outrop de sua escolha, por exemplo o nano.

## React Native CLI

CLI que significa command-line interface (interface de linha de comando), ele permite passagem de parâmetros via linha de comando em terminais e/ou semelhantes. Para instalar o React Native CLI podemos usar o npm. No terminal, execute o comando:

```
npm install -g react-native-cli
```
Agora que temos o React Native CLI devidamente instalado, podemos criar um novo projeto. Crie uma pasta no diretório onde ficarão todos os seus projetos. Depois basta executar o comando abaixo e aguardar:

```
react-native init nomedoprojeto
```

Terminada as confurações abra a pasta do seu projeto no seu editor de código.  