# Projeto de Jogo de Xadrez em Java (Curso DevSuperior)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DevSuperior](https://img.shields.io/badge/DevSuperior-Curso%20de%20Java-blue)](https://devsuperior.com.br/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-devsuperior-lightgrey?logo=github)](https://github.com/devsuperior)

Este repositório contém o código fonte do meu projeto de um jogo de xadrez desenvolvido em Java. Este projeto foi realizado como parte do curso de Java oferecido pela [DevSuperior](https://devsuperior.com.br/), uma plataforma de ensino de programação renomada. Através deste curso, tive a oportunidade de aplicar e aprofundar meus conhecimentos em programação orientada a objetos e lógica de programação na construção de uma aplicação complexa e desafiadora.

## Progresso e Funcionalidades Implementadas

O desenvolvimento deste jogo de xadrez foi uma jornada passo a passo, marcada por diversos commits que refletem a implementação gradual das funcionalidades. Abaixo, um resumo do progresso realizado (com base nos seus commits):

* **Fundamentos da Estrutura do Jogo:**
    * `First class: Position`  : Criação da classe inicial para representar as posições no tabuleiro de xadrez.
    * `Starting to implement Board and Piece`  : Primeiros passos na implementação das classes `Board` (Tabuleiro) e `Piece` (Peça).
    * `Chess layer and printing the board`  : Criação da camada específica para a lógica do xadrez e implementação da funcionalidade para imprimir o tabuleiro no console.
    * `placing pieces on the board`  : Implementação da lógica para posicionar as peças no tabuleiro no início do jogo.

* **Tratamento de Erros e Interface:**
    * `BoardingException and defensive programming`  : Implementação de tratamento de exceções específicas para o tabuleiro e aplicação de programação defensiva.
    * `ChessException and ChessPosition`  : Criação de classes para representar exceções específicas do jogo de xadrez e a posição no formato de xadrez.
    * `Little improvement in board printing`  : Pequenas melhorias na forma como o tabuleiro é exibido.
    * `Handling exceptions and clearing screen`  : Implementação de mecanismos para lidar com exceções e limpar a tela do console.

* **Movimentação das Peças:**
    * `moving pieces`  : Implementação da lógica básica para mover as peças no tabuleiro.
    * `Possible moves of a piece`  : Desenvolvimento da lógica para determinar os movimentos de uma peça genérica.
    * `Implementing possible moves of rook`  : Implementação específica dos movimentos da Torre.
    * `printing possible moves`  : Funcionalidade para exibir os movimentos de uma peça selecionada.

* **Controle do Jogo:**
    * `Switching player each turn`  : Implementação da lógica para alternar a vez entre os jogadores (Branco e Preto).
    * `Handling captured pieces`  : Mecanismo para rastrear e lidar com as peças capturadas durante o jogo.
    * `Piece move count`  : Rastreamento da contagem de movimentos de cada peça (para regras específicas).

* **Lógica de Xeque e Xeque-Mate:**
    * `Check logic`  : Implementação da lógica para verificar se um rei está em xeque.
    * `Checkmate logic`  : Implementação da lógica para determinar se um jogador está em xeque-mate e o jogo terminou.

* **Criação de Peças Específicas:**
    * `Create piece Pawn`  : Implementação da classe e da lógica de movimento do Peão.
    * `Create piece Bishop`  : Implementação da classe e da lógica de movimento do Bispo.
    * `Create piece Knight`  : Implementação da classe e da lógica de movimento do Cavalo.
    * `Create piece Queen and Pawn bugfix`  : Criação da Rainha e correção de um bug relacionado ao Peão.

* **Movimentos Especiais:**
    * `Special move castling`  : Implementação da regra do Roque.
    * `specialmove enpassant`  : Implementação da regra da captura En Passant.
    * `special move promotion`  : Implementação da regra da Promoção do Peão.
    * `Fix - better treatment to promotion`  : Melhorias no tratamento da Promoção.
    * `update left king position`  : Atualização da posição do rei esquerdo (para o Roque).

## Aprendizados

Este projeto de jogo de xadrez foi uma experiência de aprendizado incrivelmente valiosa. Através dele, pude:

* **Solidificar os conceitos de Programação Orientada a Objetos:** Aplicando herança, polimorfismo e encapsulamento na modelagem das peças e do tabuleiro.
* **Aprimorar a lógica de programação:** Desenvolvendo algoritmos para validar movimentos, verificar xeque e xeque-mate, e implementar regras especiais do xadrez.
* **Ganhar experiência no tratamento de exceções:** Garantindo a robustez da aplicação ao lidar com entradas inválidas e situações inesperadas.
* **Organizar um projeto complexo:** Estruturando o código em camadas (interface, tabuleiro, peças) para melhor organização e manutenção.


Agradeço à [DevSuperior](https://devsuperior.com.br/) por fornecer o conhecimento e a estrutura para realizar este projeto desafiador e gratificante. Este repositório é uma demonstração do meu aprendizado e da minha dedicação ao desenvolvimento em Java.
