Genius Game
Descrição
Este é um projeto que recria o clássico jogo de memória "Genius" utilizando um Arduino Uno. O jogo desafia os jogadores a repetir sequências de luzes e sons geradas aleatoriamente, aumentando a dificuldade a cada rodada.

Link do Projeto no Tinkercad
Você pode visualizar e interagir com o projeto no Tinkercad clicando aqui.

Foto do Projeto

Componentes Usados
1 Protoboard
4 LEDs (Vermelho, Azul, Verde, Amarelo)
4 Botões
4 Resistores
1 Buzzer
1 Arduino Uno
16 Fios Jumpers
Código
O código do projeto está incluído neste repositório no arquivo genius_game.ino. Ele é responsável por controlar os LEDs, botões e o buzzer para replicar a funcionalidade do jogo Genius.

Como Montar
Conecte os 4 LEDs ao protoboard e ligue cada um a um pino digital do Arduino (pinos 2, 4, 6, e 8).
Conecte os 4 botões ao protoboard e ligue cada um a um pino digital do Arduino com resistores pull-down (pinos 3, 5, 7, e 9).
Conecte o buzzer ao protoboard e ligue-o ao pino digital 13 do Arduino.
Use os fios jumpers para fazer as conexões necessárias entre o protoboard e o Arduino.
Funcionamento do Jogo
Ao iniciar, o jogo gera uma sequência aleatória de tons e luzes.
O jogador deve repetir a sequência pressionando os botões correspondentes.
A cada rodada, a sequência aumenta em um tom/luz adicional.
Se o jogador errar a sequência, o jogo é reiniciado.
Instalação
Baixe e instale a IDE do Arduino.
Clone este repositório ou faça o download do arquivo ZIP e extraia-o.
Abra o arquivo genius_game.ino na IDE do Arduino.
Conecte o Arduino ao computador e faça o upload do código.
Contribuição
Sinta-se à vontade para contribuir com melhorias para o projeto. Para isso:

Faça um fork do repositório.
Crie uma nova branch com a sua feature (git checkout -b minha-feature).
Faça commit das suas alterações (git commit -m 'Adicionei uma nova feature').
Faça push para a branch (git push origin minha-feature).
Abra um Pull Request.
Licença
Este projeto está licenciado sob a MIT License.
