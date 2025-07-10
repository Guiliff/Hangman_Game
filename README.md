# 🎯 Hangman Game - ![Linguagem C](https://img.shields.io/badge/feito%20em-C-blue.svg)

Um simples jogo da forca escrito em linguagem C, executado no terminal. O objetivo
é adivinhar corretamente uma palavra secreta, letra por letra, antes de atingir o limite de erros permitidos.

## 🚀 Como Jogar
1. **Clone ou copie o código** para sua máquina.
```bash
git clone https://https://github.com/Guiliff/Hangman_Game
cd Guessing_Game
```

2. **Compile o código** com o GCC no terminal:
```bash
gcc hangman.c -o hangman.out
./hangman.out
```

<div align="center">
  <img src="https://github.com/Guiliff/Hangman_Game/blob/main/assets/gcchangman.gif?raw=true" alt="Compilando o jogo" />
</div>

3. Comece a jogar:

- O jogo escolhe uma palavra secreta.
- Você deve digitar uma letra por vez.
- Acertos revelam letras na palavra.
- Erros são contabilizados com um limite de 6 tentativas.

<div align="center">
  <img src="https://github.com/Guiliff/Hangman_Game/blob/main/assets/hang.gif?raw=true" alt="Compilando o jogo" />
</div>

## 🧠 Lógica do Jogo
- A palavra secreta é definida no código.
 Cada letra digitada:
   - Se for correta, revela todas as ocorrências dessa letra.
   - Se for incorreta, soma um erro.
- O jogo termina quando:
   - A palavra é completada corretamente, ou
   - O jogador erra 6 vezes.
- O jogo ignora letras repetidas já adivinhadas.

## 🛠 Requisitos
- Compilador C (como o GCC) via terminal, ou
- IDE com suporte à linguagem C, como:
  - Visual Studio Code (com a extensão C/C++)
  - Code::Blocks
  - Dev-C++
---
Divirta-se e bons palpites!
