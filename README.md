Fork of tic-tac-toe by gdevine-ucsc.

This program utilizes the ImGui library to display a game of tic-tac-toe to the user.

There is an AI that will play against the player. The player will be the X while the AI will use the O

## Design Process ##
  The starter code had a lot of comments to help paint a picture of what I needed to do, so I followed those while also reading through
  the starter code classes to understand what the code does as well as what it returns and what that item could be used for

  For the AI implementation, I used the negamax method along with alpha-beta tree pruning to reduce the amount of recursion.
  I referenced the pseudocode shown on the Wikipedia article for negamax with alpha-beta tree pruning example
  https://en.wikipedia.org/wiki/Negamax
  and I also referenced the implementation shown by Professor Graeme Devine at UCSC for their CMPM 123: Advanced Programming class.

## Tools Used ##
  Coded using VsCode using CMake with use of the ImGui library
