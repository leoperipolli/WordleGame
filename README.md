# Termo (Wordle in Portuguese)

Final project for the Programming Languages I course. A Java version of Wordle, played in Portuguese.

## What it does

- Picks a random five-letter word from a Portuguese dictionary (`dicionario.txt`).
- Gives the player 6 tries and checks that each guess is a real word.
- Marks each letter: `V` right position, `A` in the word but in the wrong position, `-` not in the word.
- Ignores accents and cedilla, so `AÇÃO` and `ACAO` count as the same word.

## Stack

Java, with Swing (`JOptionPane`) dialogs for input and output.

## Structure

- `Termo.java`: entry point.
- `Process.java`: reads the dictionary, draws the word and normalizes accents.
- `Verify.java`: game loop and letter checking.
- `ConstructorsTermo.java`: holds the drawn word and the player's guess.
