# File System Module 
Esse projeto é uma demonstração básica de como criar um arquivo com conteúdo em Node.js.


## Visão Geral

Este código é uma implementação de um mecanismo CRUD que se concentra apenas na operação de criação (Create). Ele requer o módulo 'fs' (File System) do Node.js para lidar com operações de sistema de arquivos. Em resumo, este código lê um conteúdo passado como argumento para a função create e o escreve de forma síncrona em um arquivo de banco de dados no caminho especificado. Neste exemplo, ele cria ou sobrescreve o arquivo "db".

## Instalação

Antes de começar, certifique-se de ter o Node.js instalado em seu sistema. Em seguida, siga estas etapas para configurar o projeto:

1. Clone o repositório do GitHub:

   ```bash
    https://github.com/nadjaguerra/File-System-Module
   ```
2. Instale as dependências de desenvolvimento:

```bash
 Copy code npm install
```

## Uso
```bash
node ./core/crud.js
```
### Ou como definido no script - package.JSON
```bash
npm run start 
```

## Nodemon

Nodemon é uma ferramenta que irá automatizar o processo de desenvolvimento.
Se utiliza-lo não será necessário reiniciar manualmente o servidor a cada modificação.


```bash
npm install -g nodemon
```
Execultar (definido no script - package.JSON)
```bash
npm run dev
```
Parar 
```bash
ctrl + c
```

