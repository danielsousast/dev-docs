# Instalando Node.js via NVM-Windows

Há várias maneiras de instalar o Node. js. É recomendável usar um Gerenciador de versão como versões alteradas muito rapidamente. Para fazer isso podemos usar o NVM-Windows:

## Baixando e instalando o NVM-Windows

**1.** Abra o repositório do **Windows-NVM** no navegador da Internet e selecione o link baixar agora.

**2.** Baixe o arquivo **NVM-setup**.zip para a versão mais recente.

**3.** Depois de baixado, abra o arquivo zip e, em seguida, abra o arquivo NVM-setup.exe.

**4.** O assistente de instalação do setup-NVM-for-Windows guiará você pelas etapas de instalação, incluindo a escolha do diretório onde NVM-Windows e node. js serão instalados.


## Utilizando NVM-Windows

**5.** Quando a instalação for concluída. Abra o PowerShell e tente usar o Windows-NVM para listar quais versões do nó estão atualmente instaladas (não deve ser nenhuma neste ponto): 

```
nvm ls
```
**6.** Instale a versão atual do node. js (para testar as melhorias de recursos mais recentes, mas com mais probabilidade de ter problemas do que a versão LTS): 

```
nvm install latest
```

**7.** Instale a versão mais recente do LTS estável do node. js (recomendado) examinando primeiro qual é o número de versão atual do LTS: nvm list available, em seguida, instalando o número de versão do LTS com: nvm install <version> (substituindo <version> pelo número).
  
```
nvm install 12.14.0
```

**8.** Para verificar qual versão do node. js é o padrão no momento, digite: 

```
node --version
```
**9.** Para alterar a versão do node. js que você deseja usar para um projeto, crie um novo diretório do projeto mkdir NodeTeste insira o diretório cd NodeTeste, em seguida, insira nvm use <version> substituindo <version> pelo número de versão que você deseja usar.
  
**10.** Verifique qual versão do NPM está instalada com: npm --version, este número de versão será alterado automaticamente para qualquer versão do NPM associada à sua versão atual do node. js.

