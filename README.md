# :chess_pawn: Chess System in Java :coffee:

## Como jogar :video_game:

1. Abra um _terminal_ (**[Git Bash](https://gitforwindows.org/)** é o recomendado, pois é colorido)
2. Entre no diretório **/bin** do projeto, no meu caso `C:\temp\ws-eclipse\chess-system\bin`
3. Após entrar no diretório, digite `Java application/Program` para rodar a aplicação (obs: estou utilizando o Java SE 8)
4. O resultado esperado será esse, conforme o **1° Tela Inicial** exibe abaixo:

| 1° Tela Inicial  | 2° Selecione a peça origem (Source)  | 3° Selecione a peça destino (Target)  | 4° Peça movida, turno/player trocado  |
|---|---|---|---|
| ![imagem1](https://user-images.githubusercontent.com/81187261/151685458-e94b7255-a708-4314-83f0-00975c843366.png)  | ![imagem2](https://user-images.githubusercontent.com/81187261/151685488-aa6d5bb4-9029-4ae8-92b4-3fbdc1f70133.png)  | ![imagem3](https://user-images.githubusercontent.com/81187261/151685493-b9391d13-c34d-4b6b-8d22-69b78ed486e7.png)  | ![imagem4](https://user-images.githubusercontent.com/81187261/151685500-6767d4ca-e38c-469a-b241-5bc01a8ac2ce.png)  |

5. **Observações:** :pencil:
+ Peças: Peão, Torre, Cavalo, Bispo, Rainha e Rei

| Pawn(Peão) | Rook(Torre) |  Knight(Cavalo) | Bishop(Bispo)  |  Queen(Rainha) | King(Rei)  |
|---|---|---|---|---|---|
| **P** | **R** | **N** | **B** | **Q** | **K** |

+ A mecânica do jogo é baseada em **linhas**(1, 2, 3, 4, 5, 6, 7, 8) e **colunas**(a, b, c, d, e, f, g, h)
+ Para **escolher** uma peça é necessário selecionar _primeiramente_ a **coluna** e logo em seguida(sem espaços) selecionar a **linha**, exemplo: **c2**
+ Em **Captured pieces** o jogo armazena as peças capturadas.
+ O **Turn** exibe o turno(rodada) em que o jogo está.
+ **Waiting player** exibe qual é o jogador a jogar a próxima peça.
+ **Source** é a origem, ou seja, a peça no qual o jogador irá jogar.
+ **Target** é o destino, ou seja, o local no qual o jogador irá mover a peça.
+ O jogo possui sistema de **Check** e **CheckMate**
+ Alguns movimentos especiais:
  - Castling(Roque)
  - En Passant
  - Promotion(Promoção)
