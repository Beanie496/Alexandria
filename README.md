## Features
* Engine
  * Bitboard representation
  * Zobrist hashing
* Search
  * Negamax framework
  * Aspiration Window
  * Alpha-Beta pruning
  * PVS
  * Quiescence search
  * Transposition Table
  * Repetition detection
  * killer move, history, Countermove heuristic
  * MVV-LVA move ordering
  * Null-move pruning
  * Razoring
  * Late-move reduction
* Evaluation
  * NNUE Evaluation (Big thanks to Luecx)
  * HCE based on material evaluation and a piece square table (legacy and not subject to ulterior development)



## Things i tried that didn't work
* Search
  * SEE
  * Promotion moves ordering

## Acknowledgements
This project would not have been possible without the following people
* BluefeverSoftware for his Vice chess engine from which i learnt the basic structure and functionality of a chess engine
* CodeMonkeyKing for his bbc chess engine from which i learnt how bitboards work and several refined search techniques
* The whole Stockfish Discord server and Disservin in particular for the sharing of code and the avaliability in answering questions
* A giant thanks to Luecx that helped me immensely in the process of setting up the NNUE and gave me some training data generated by Koivisto
* Lucex (again) and Jay Honnold for the wonderlud CudAD trainer that was used to train the NNUE https://github.com/Luecx/CudAD
