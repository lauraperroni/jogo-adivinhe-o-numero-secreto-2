# Jogo de adivinhar um número


Pequeno projeto em Javascript feito no curso da Alura **["Lógica de programação: explore funções e listas
"](https://cursos.alura.com.br/course/logica-programacao-funcoes-listas)** durante minha participação como aluna no programa[ Geração Caldeira,](https://www.geracaocaldeira.org/) oferecido pelo [Instituto Caldeira.](https://institutocaldeira.org.br/)

<div align="center">
<img src="./img/guess.png" width="300" height="300"/>
</div>

Este projeto é um simples jogo de adivinhação de número, desenvolvido em JavaScript. O objetivo do jogo é adivinhar um número secreto gerado aleatoriamente pelo computador dentro de um intervalo predefinido. O jogo fornece dicas ao jogador, informando se o palpite é maior ou menor que o número secreto até que o número correto seja adivinhado.

**Funcionalidades**
---
* Gerar número secreto: O jogo gera um número secreto aleatório entre 1 e um valor máximo especificado.
* Palpites do jogador: O jogador insere palpites até adivinhar o número secreto.
* Dicas interativas: O jogo fornece dicas se o palpite é maior ou menor que o número secreto.
* Contador de tentativas: O jogo contabiliza o número de tentativas até o jogador acertar o número secreto.
* Mensagem de vitória: Exibe uma mensagem ao jogador quando ele acerta o número secreto, indicando o número de tentativas utilizadas.
* Números secretos que não se repetem ao longo do jogo
* Interface simples e elegante, com acessibilidade (text-to-speech)

**Como Executar**
---
1. Acesse o jogo [aqui](https://lauraperroni.github.io/logica-js-2/)
2. Você será levado a uma página com um input e dois botões.
3. O jogador deve inserir palpites até adivinhar corretamente o número secreto.
4. O jogo fornecerá feedback sobre se o palpite é maior ou menor que o número secreto, inclusive por audio falado.
5. Ao acertar o número, uma mensagem será exibida indicando o número de tentativas necessárias.
6. O jogo guarda todos os números já utilizados e ao usar todos os números de 1 até 10 (sem repeti-los) ele reinicia a lista de números usados para que você continue a jogar.

