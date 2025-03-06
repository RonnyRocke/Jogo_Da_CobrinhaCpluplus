Jogo da Cobrinha (Snake Game)

Este é um jogo simples da cobrinha (Snake) implementado em C++ que roda no terminal. O objetivo do jogo é controlar a cobrinha, comendo as frutas que aparecem na tela, e fazendo a cobrinha crescer a cada fruta comida. O jogo termina se a cobrinha colidir com a própria cauda ou com as bordas.

DEMONSTRAÇÃO: 
ffmpeg -i input.gif -filter_complex "[0]setpts=0.5*PTS" output.gif

![snake](https://github.com/user-attachments/assets/b56d33d3-471d-49ec-824e-8c3a1be7a5c4)



Requisitos:

    C++11 ou superior
    Sistema operacional com suporte ao comando clear para limpar a tela (no Linux, por exemplo).

Funcionalidades

    Movimentação da cobrinha utilizando as teclas:
        W: Para cima
        A: Para esquerda
        S: Para baixo
        D: Para direita
    A cobrinha começa com um tamanho pequeno e vai crescendo à medida que come as frutas.
    O jogo termina quando a cobrinha colide com sua própria cauda ou pressiona a tecla X.
    A pontuação aumenta conforme a cobrinha come as frutas, e é exibida no final do jogo.

Como jogar

    Compile e execute o código.
    Use as teclas W, A, S, D para controlar a direção da cobrinha.
    Coma as frutas (representadas pelo caractere "F") para aumentar seu tamanho e sua pontuação.
    Evite que a cobrinha colida com a própria cauda ou com as bordas do mapa.

Como rodar o jogo

Para compilar e executar o código no terminal, siga os passos:

    Compile o código:

g++ -o snake_game snake_game.cpp

Execute o jogo:

    ./snake_game

Licença

Este projeto está licenciado sob a MIT License.
