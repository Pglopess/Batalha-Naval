# Batalha Naval

Batalha Naval é um jogo simples de tabuleiro baseado no clássico jogo de guerra naval. O jogador enfrenta o computador em uma batalha onde o objetivo é afundar todos os navios inimigos antes que seus próprios navios sejam destruídos.

## Funcionalidades
- Tabuleiro de 5x5 para cada jogador (jogador e computador).
- Posicionamento aleatório de navios para ambos os jogadores.
- Três tipos de embarcações:
  - Porta-aviões (4 unidades)
  - Destroyers (5 unidades)
  - Submarinos (6 unidades)
- O jogador e o computador se alternam realizando disparos até que todos os navios de um dos jogadores sejam destruídos.
- Interface simples em console.

## Como Jogar
1. O jogo solicitará que você insira seu nome.
2. O menu inicial permitirá que você escolha entre:
   - `1. Jogar` - Inicia uma nova partida.
   - `2. Sair` - Sai do jogo.
3. Durante o jogo:
   - O jogador insere as coordenadas do tiro (linha e coluna).
   - O computador também realiza disparos aleatórios.
   - O tabuleiro é atualizado a cada rodada.
4. O jogo termina quando todos os navios de um dos jogadores forem destruídos.

## Como Executar
1. Certifique-se de ter o [Java](https://www.java.com/pt-BR/) instalado na sua máquina.
2. Baixe ou clone este repositório.
3. Compile e execute o jogo com os seguintes comandos no terminal:
   ```sh
   javac jogo/BatalhaNaval.java
   java jogo.BatalhaNaval
   ```

## Exemplo de Saída no Console
```
Digite o nome do jogador: Pedro
Pedro, Seja bem-vindo(a) ao jogo da Batalha Naval - Menu:
1. Jogar
2. Sair
Escolha uma opcao (1 ou 2): 1

Tabuleiro do Jogador:
   A B C D E
1  ~ ~ P ~ ~
2  D ~ ~ S ~
3  ~ D ~ ~ P
4  S ~ ~ D ~
5  ~ ~ ~ P ~

Tabuleiro do Computador:
   A B C D E
1  ~ ~ ~ ~ ~
2  ~ ~ ~ ~ ~
3  ~ ~ ~ ~ ~
4  ~ ~ ~ ~ ~
5  ~ ~ ~ ~ ~

Pedro, insira as coordenadas do tiro:
Linha (1 a 5): 3
Coluna (A a E): C
Pedro, voce acertou um objeto do computador!
```

## Tecnologias Utilizadas
- **Java** - Linguagem de programação principal
- **Scanner** - Para entrada de dados do jogador
- **Random** - Para gerar posições aleatórias para os navios

## Melhorias Futuras
- Expandir o tabuleiro para tamanhos maiores.
- Permitir diferentes dificuldades para o computador.
- Adicionar um histórico de partidas e estatísticas.
- Criar uma interface gráfica para melhor experiência do usuário.

## Autor
Desenvolvido por **Pedro Gustavo Thomas**.

[GitHub](https://github.com/Pglopess) | [LinkedIn](https://www.linkedin.com/in/pedro-gustavo-thomas-5935392b7/)

