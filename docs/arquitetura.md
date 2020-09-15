# Arquitetura 

* As funções relacionadas ao gerencimaento das casas do jogo da velha ficarão no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "." para cada vazia; "X" para casa ocupada pelo 1o jogador; "O" para casa ocupada pelo 2o jogador

* A função inicializar() retornará um lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.