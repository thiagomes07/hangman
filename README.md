# Jogo da Forca Online  

## Sobre o Projeto  
Este repositório contém um jogo da forca online baseado em **HTML**, **CSS** e **JavaScript**. O jogo permite partidas individuais e multiplayer, proporcionando uma experiência divertida e interativa.  

Este projeto é baseado em um repositório existente ([Joi-GN/jogo-da-forca-js](https://github.com/Joi-GN/jogo-da-forca-js)), o qual foi **forkado e testado** para validar se ele atende aos requisitos levantados no documento de requisitos. As tabelas de requisitos indicam claramente as funcionalidades implementadas e aquelas que não foram atendidas.  

## Objetivo da Atividade  
A atividade tem como objetivo aplicar conceitos de engenharia de software e controle de versão, incluindo:  
- Levantamento de requisitos para um sistema de software.  
- Utilização do **Git** para versionamento semântico.  
- Publicação do projeto no **GitHub Pages**.  

## Como Visualizar o Documento de Requisitos  
O levantamento de requisitos está disponível no arquivo [requirements.md](./requirements.md). Ele contém uma análise detalhada dos requisitos funcionais e não funcionais do sistema, além dos resultados dos testes realizados no jogo forkado para validar se atende a esses requisitos.  

## Estrutura de Pastas do Projeto  
A estrutura de diretórios do projeto é organizada da seguinte forma:  

```plaintext
C:.
│   README.md          -> Arquivo de documentação do projeto
│   requirements.md    -> Documento de requisitos do jogo da forca
│
└───hangmanWeb         -> Diretório com os arquivos do jogo
    │   index.html     
    │   style.css      
    │
    └───scripts
        buttons-functions.js  
        game-board.js         
        game-logic.js         
```  

## Como Jogar  
1. Acesse a [versão hospedada](https://joi-gn.github.io/jogo-da-forca-js/) do jogo através do **GitHub Pages**.  
2. Escolha uma categoria e tente adivinhar a palavra antes que suas tentativas acabem.  
3. Divirta-se e desafie seus amigos!  

## Desenvolvimento e Estruturação do Repositório  
Este repositório foi estruturado seguindo boas práticas de versionamento com **Git** e **GitHub Flow**, garantindo um fluxo organizado e rastreável das mudanças.  

### Diagrama do Fluxo de Branches  
```plaintext
 main
  │
  ├── develop (criada e limpa)
  │    │
  │    ├── feature/game-code (adiciona código do jogo)
  │    │    └── merge → develop
  │    │
  │    ├── docs/requirements (adiciona documentação de requisitos)
  │    │    └── merge → develop
  │    │
  │    └── merge → main (finaliza a estruturação)
  │
  └── 🚀 Repositório pronto!
```  

### Fluxo de Desenvolvimento  
O desenvolvimento seguiu estas etapas principais:  
1. **Criação da branch `develop`** para limpar o repositório e servir como base para desenvolvimento.  
    > **chore: initialize develop branch and clean repository**  
2. **Adição do novo README.md** na `develop` contendo a descrição do projeto.  
    > **docs: add initial README with project details**  
3. **Criação da branch `feature/game-code`** para adicionar os códigos do jogo da forca, depois mesclada na `develop`.  
    > **feat: add base Hangman game code**  
4. **Criação da branch `docs/requirements`** para adicionar a documentação de requisitos, depois mesclada na `develop`.  
    > **docs: add requirements documentation**  
5. **Mesclagem final** da `develop` na `main`, consolidando todas as mudanças.  

## Repositório  
O código-fonte e a documentação estão disponíveis em: **https://github.com/thiagomes07/hangman**  
