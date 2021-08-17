## Laboratorio-Final-Projeto-
## O controle será realizado para o sistema de elevadores.
## Requisitos
## Requisitos Funcionais
### RF01 - O sistema de elevadores deverá acender a luz do elevador quando a porta for aberta.
### RF02 - O sistema de elevadores deverá acender a luz do elevador quando a porta for fechada.
### RF03 - O sistema de elevadores deverá apagar a luz do elevador em repouso.
### RF04 - O sistema de elevadores deverá acender a luz do botão acionado internamente.
### RF05 - O sistema de elevadores deverá utilizar os três elevadores como independentes.
### RF06 - O sistema de elevadores deverá utilizar a UART como meio de comunicação para o controle.
### RF07 - O sistema de elevadores deverá priorizar os andares mais altos em situação de múltiplos acionamentos de botões.
### RF08 - O sistema de elevadores deverá manter os três elevadores no andar térreo caso nenhum botão externo for ativado.
### RF09 - O sistema de elevadores deverá manter as portas fechadas em movimento.
### RF10 - O sistema de elevadores deverá parar no andar requisitado na altura correta.
### RF11 - O sistema de elevadores deverá priorizar os acionamentos dos botões internos em relação aos externos.
### RF12 - O sistema de elevadores deverá parar quando a altura for superior a do último andar.
### RF13 - O sistema de elevadores deverá parar quando a altura for inferior a do primeiro andar.
### RF14 - O sistema de elevadores deverá abrir as portas ao chegar no andar desejado.
### RF15 - O sistema de elevadores deverá manter as portas abertas por 4 segundos para então atender os outros acionamentos.

## Requisitos Não-Funcionais
### RNF01 - O sistema de elevadores deverá utilizar o kit de desenvolvimento Ek-TM4C1294XL.
### RNF02 - O sistema de elevadores deverá apresentar um tempo máximo de 200 ms para o atendimento de um comando.
### RNF01 - O sistema de elevadores deverá apresentar um tempo máximo de 100 ms para a movimentação do elevador requisitado.


## Restrições
### R 01 - O sistema de elevadores deverá possuir uma fila de mensagem para cada elevador.
