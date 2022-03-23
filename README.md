# Chess-in-C

I've found a long script in C (C++) where I've implemented (many years ago) the game of chess from scratch (e.g. definition of the chessboard, the pieces, the moves) and I felt like sharing it. I was given many important suggestions and hints, and, if I remember correctly, behind many parts of the code there was the invisible and wise hand of Ivano Salvo. 

It is possible to play a game by compiling the program. There is no graphic, though, and only the list of mouves is produced. Ofcourse nowdays, with AI and all, the programming techniques used in implementing the game of chess are different and more advanced, but I think it can be a good idea to see how things can be done from scratch.

To compile the program (in a command line) write `g++ colore.cpp scacchiera.cpp pezzi.cpp scacchi.cpp -o chess` (generates the “chess” executable), and use the previously compiled libraries to play.

### What's in here?

- all the scrpits that are needed to implement the game of chess (e.g. `Casella.cpp` implement the cells in the chessboard and `casella.h` is the related library)
- all the libraries needed to execute the scripte
- an example of a game (i.e. a text file with all the moves you can try)
- an executable file `scacchi` you can (hopefully) use to play directly without compiling every script and library

### Instructions

For each move you have to specify the starting position of the piece you want to move followed by the arriving position. For example the move `e2e4` means that the pawn that is currently in position `e2` will be moved in position `e4`.
