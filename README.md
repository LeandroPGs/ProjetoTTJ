<div align="center">
  <h1 align="center">
    ProjetoTTJ
  </h1>
</div>

## Introdução

TTJ trata-se de jogo de tabuleiro baseado no jogo Cappuccino que comporta até 4 jogadores no qual o objetivo é empilhar o maior número de peças possíveis até o ponto em que não seja possível realizar mais jogadas e, ao final, vence aquele que conseguir mais pilhas com o maior número de peças. O projeto é desenvolvido na linguagem C para a conclusão da cadeira de Laboratório de Algoritmos e Estruturas de Dados para o bacharelado em Ciências da Computação pela UFCA.

## Regras do Jogo

O tabuleiro inicialmente dispõe da mesma quantidade de peças de cada cor que representa um jogador. Em cada jogada, o jogador seleciona uma peça de sua cor e verifica ao seu redor - área de 8 - se há alguma peça disponível; caso positivo, a pilha/peça atual é empilhada sobre a aquela selecionada, e o espaço desta é dado como vazio.  Outro detalhe importante é que cada jogada só pode acontecer caso a pilha de destino seja menor ou igual a pilha do jogador. O jogo acaba no momento em que não seja mais possível realizar jogadas.

Cada jogador tem é apresentado por uma cor ___Azul, vermelho, amarelo e branco___.

## Configurações de Jogo

É possível jogar de 2 a 4 pessoas com tabuleiros de 25 (5x5) a 100 (10x10) peças:

| Tabuleiro/Jogadores | 2 | 3 | 4 |
| --- | --- | --- | --- |
| 5 × 5 (25) | 12/1 | 8/1 | 6/1 |
| 6 × 6 (36) | 18 | 12 | 9 |
| 7 × 7 (49) | 24/1 | 16/1 | 12/1 |
| 8 × 8 (64) | 32 | 21/1 | 16 |
| 9 × 9 (81) | 40/1 | 27 | 20/1 |
| 10 × 10 (100) | 50 | 33/1 | 25 |
