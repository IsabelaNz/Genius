<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Genius Game</title>
</head>
<body>

    <h1>Genius Game</h1>

    <h2>Descrição</h2>
    <p>Este é um projeto que recria o clássico jogo de memória "Genius" utilizando um Arduino Uno. O jogo desafia os jogadores a repetir sequências de luzes e sons geradas aleatoriamente, aumentando a dificuldade a cada rodada.</p>

    <h2>Link do Projeto no Tinkercad</h2>
    <p>Você pode visualizar e interagir com o projeto no Tinkercad <a href="https://www.tinkercad.com" target="_blank">clicando aqui</a>.</p>

    <h2>Foto do Projeto</h2>
    <p><img src="link-para-a-imagem-do-projeto-no-github" alt="Genius Game"></p>

    <h2>Componentes Usados</h2>
    <ul>
        <li>1 Protoboard</li>
        <li>4 LEDs (Vermelho, Azul, Verde, Amarelo)</li>
        <li>4 Botões</li>
        <li>4 Resistores</li>
        <li>1 Buzzer</li>
        <li>1 Arduino Uno</li>
        <li>16 Fios Jumpers</li>
    </ul>

    <h2>Código</h2>
    <p>O código do projeto está incluído neste repositório no arquivo <code>genius_game.ino</code>. Ele é responsável por controlar os LEDs, botões e o buzzer para replicar a funcionalidade do jogo Genius.</p>

    <h2>Como Montar</h2>
    <ol>
        <li>Conecte os 4 LEDs ao protoboard e ligue cada um a um pino digital do Arduino (pinos 2, 4, 6, e 8).</li>
        <li>Conecte os 4 botões ao protoboard e ligue cada um a um pino digital do Arduino com resistores pull-down (pinos 3, 5, 7, e 9).</li>
        <li>Conecte o buzzer ao protoboard e ligue-o ao pino digital 13 do Arduino.</li>
        <li>Use os fios jumpers para fazer as conexões necessárias entre o protoboard e o Arduino.</li>
    </ol>

    <h2>Funcionamento do Jogo</h2>
    <ol>
        <li>Ao iniciar, o jogo gera uma sequência aleatória de tons e luzes.</li>
        <li>O jogador deve repetir a sequência pressionando os botões correspondentes.</li>
        <li>A cada rodada, a sequência aumenta em um tom/luz adicional.</li>
        <li>Se o jogador errar a sequência, o jogo é reiniciado.</li>
    </ol>

    <h2>Instalação</h2>
    <ol>
        <li>Baixe e instale a <a href="https://www.arduino.cc/en/software" target="_blank">IDE do Arduino</a>.</li>
        <li>Clone este repositório ou faça o download do arquivo ZIP e extraia-o.</li>
        <li>Abra o arquivo <code>genius_game.ino</code> na IDE do Arduino.</li>
        <li>Conecte o Arduino ao computador e faça o upload do código.</li>
    </ol>

    <h2>Contribuição</h2>
    <p>Sinta-se à vontade para contribuir com melhorias para o projeto. Para isso:</p>
    <ol>
        <li>Faça um fork do repositório.</li>
        <li>Crie uma nova branch com a sua feature (<code>git checkout -b minha-feature</code>).</li>
        <li>Faça commit das suas alterações (<code>git commit -m 'Adicionei uma nova feature'</code>).</li>
        <li>Faça push para a branch (<code>git push origin minha-feature</code>).</li>
        <li>Abra um Pull Request.</li>
    </ol>

    <h2>Licença</h2>
    <p>Este projeto está licenciado sob a <a href="LICENSE">MIT License</a>.</p>

</body>
</html>
