
# Ambiente React native no Linux(Ubuntu)

## Node

Para Instalar o Node a maneira mais adequada é através do Gerenciador de Versionaemnto do Node - NVM., Ele nos permite instalar várias versões do Node e alternar entre elas de maneira fácil. Clique aqui para saber como instalr o Node via NVM n o Linux.

## Instalando Yarn

O Yarn é uma "concorrente" do NPM e possui algumas vantagens em relação ao mesmo. Por isso vem sendo largamente usado pela comunidade. Para instalá-lo é bem simples. Basta executarmos usar o próprio NPM para far uma instalação de forma global:

```
npm insatall -global yarn
```

## JDK

Geralmente, aplicativos nativos para Android são criados em Java. Então Java Development Kit é necessário. Para instalar execute:

```
sudo apt install openjdk-8-jdk
```
## Emulador do Android Studio
Pode ser baixado diretamente no site oficial. Porém uma maneira pŕatica é através do snap ou fazer o download do pacote do site https://developer.android.com/:

```
sudo snap install android-studio --classic
```
Finalizada a instalação abra o Android Studio e siga as intruções. 

## Configurando variáveis de ambiente
Agora algumas variáveis de ambiente precisam ser configuradas para criar aplicativos com código nativo.

```
sudo vim $HOME/.bashrc
```
Eu estou usando o editor de texto vim, você pdoe usar outro de sua escolha, por exemplo o vim.

```
export ANDROID_HOME=~/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

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
