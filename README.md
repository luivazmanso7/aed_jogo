jogo educativo feito por alunos da Cesar school utilizando lista encadeada.
---

# Descubra o Animal

**Descubra o Animal** é um jogo de perguntas e respostas onde os jogadores devem adivinhar o animal baseado em dicas fornecidas. O jogo é baseado em um sistema de ecossistemas e níveis de dificuldade, proporcionando uma experiência divertida e educativa.

## Funcionalidades

- **Ecossistemas Diversos:** Escolha entre diferentes ecossistemas como Deserto, Oceano, Floresta, Neve e Montanha.
- **Níveis de Dificuldade:** Jogue em níveis de dificuldade Fácil ou Difícil.
- **Modo de Dois Jogadores:** Desafie um amigo em um jogo competitivo.
- **Sistema de Pontuação:** Pontos são atribuídos com base no número de acertos.

## Requisitos

- **Sistema Operacional:** Linux, Windows, macOS
- **Compilador C:** GCC ou similar

## Compilação e Execução

Para compilar e executar o jogo, siga os passos abaixo:

1. **Clone o Repositório:**

   ```sh
   git clone https://github.com/seuusuario/descubra-o-animal.git
   cd descobre-o-animal
   ```

2. **Compile o Código:**

   ```sh
   gcc -o descubra-o-animal descubra-o-animal.c
   ```

3. **Execute o Jogo:**

   ```sh
   ./descubra-o-animal
   ```

## Como Jogar

1. **Início do Jogo:**
   - Ao iniciar o jogo, insira o nome dos jogadores.

2. **Escolha do Ecossistema e Dificuldade:**
   - O jogador da vez seleciona um ecossistema (Deserto, Oceano, Floresta, Neve, ou Montanha).
   - Em seguida, escolha o nível de dificuldade (Fácil ou Difícil).

3. **Responda às Dicas:**
   - O jogo fornecerá dicas sobre um animal específico. Tente adivinhar o nome do animal com base nas dicas fornecidas.
   - O jogador tem até 4 dicas para adivinhar corretamente.

4. **Pontuação e Rodadas:**
   - Cada acerto concede pontos ao jogador.
   - O jogo alterna entre os jogadores a cada rodada.
   - O jogo continua até que ambos os jogadores tenham jogado uma vez.

5. **Final do Jogo:**
   - Ao final das rodadas, o jogo exibe o placar final e declara o vencedor.
   - Você pode optar por jogar novamente ou encerrar o jogo.


## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

