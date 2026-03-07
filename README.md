# RegexToDFA - Academic Project

A C++ application that parses a Regular Expression and converts it into a Deterministic Finite Automaton (DFA) using a Syntax Tree. 

## Features

- **Read Regex**: Directly from `input.txt` or via standard console input.
- **Postfix Notation**: Converts and displays the regular expression in postfix format.
- **Syntax Tree**: Builds and prints the syntax tree of the regular expression.
- **DFA Generation**: Constructs the Deterministic Finite Automaton and displays its states, alphabet, transitions, initial state, and final states.
- **Save to File**: Exports the resulting DFA details into an `output.txt` file.
- **Word Verification**: Tests whether specific words are accepted by the generated DFA.

## Usage

1. **Input**: Place your regular expression in `input.txt`. If the file is missing or empty, the application will prompt you to enter the expression manually in the console.
2. **Menu Options**:
   - `1`: Show the postfix notation of the expression.
   - `2`: Show the Syntax Tree.
   - `3`: Show the DFA (Deterministic Finite Automaton).
   - `4`: Save the DFA configuration to `output.txt`.
   - `5`: Verify entered words against the DFA (type `stop` to exit verification mode, or `_` for the empty word).
   - `0`: Exit the application.
