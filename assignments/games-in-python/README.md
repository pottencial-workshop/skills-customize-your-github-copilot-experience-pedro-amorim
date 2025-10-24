
# 📘 Assignment: Hangman (Forca)

## 🎯 Objetivos 

Construir uma versão em linha de comando do jogo Hangman (Forca) em Python. Os estudantes vão praticar manipulação de strings, laços, condicionais e entrada do usuário enquanto implementam lógica de jogo e controle de estado.

## 📝 Tarefas

### 🛠️	Implementar o jogo Hangman

#### Description
Implemente um jogo Hangman em Python que rode no terminal. O jogo deve selecionar uma palavra aleatória de uma lista, aceitar palpites de letra do jogador, mostrar o estado atual da palavra com letras reveladas e sublinhados, e terminar quando o jogador adivinhar a palavra ou acabar as tentativas.

#### Requirements
Completed program should:

- Selecionar palavras aleatoriamente a partir de uma lista pré-definida
- Aceitar palpites de uma única letra por rodada e atualizar o progresso (ex.: "_ a _ _ m a n")
- Exibir letras já adivinhadas e evitar contagens duplicadas para o mesmo palpite
- Rastrear e mostrar o número de tentativas incorretas restantes
- Encerrar o jogo com mensagem de vitória quando a palavra for descoberta, ou mensagem de derrota quando as tentativas se esgotarem

Exemplo de saída (trecho):

```
Palavra: _ a _ _ m a n
Letras erradas: b, c
Tentativas restantes: 4
Digite uma letra: 
```

### 🛠️	Melhorias opcionais

#### Description
Opções para estender o projeto e ganhar pontos extras: adicionar categorias de palavras, salvar pontuações, ou criar uma interface simples com `tkinter`.

#### Requirements
Completed program should:

- Permitir escolher categoria (ex.: animais, objetos, tecnologia) ou modo aleatório
- Implementar um placar simples que registre vitórias/derrotas em um arquivo (opcional)
- (Opcional) Interface gráfica básica com `tkinter` mostrando estado do jogo e botões de entrada

