# Polynomial-time-T-count-algo

This repository contains result files for a polynomial time T-count algorithm. This algorithm is described in the following paper:
" A polynomial time and space heuristic algorithm for T-count" by Michele Mosca and Priyanka Mukhopadhyay.
It is also available online at : https://arxiv.org/abs/2006.12440

There are a number of folders, the ones containing channel representation of untiaries are in the following two folders:

ChanRep : This contains the channel representation of Toffoli, Fredkin, Peres, Quantum Xor, negated Toffoli, 4-qubit Adder and two other 4 qubit unitaries.

ChanRep_rand: This folder contains the channel representation of random 2 and 3 qubit unitaries. The unitaries were randomly generated with certain number of T-gates.
The .txt files are names as chanQ_t_x.txt. Here Q is the number of qubits. t is the number of T-gates used to generate them. x is a serial number.
This folder also contains the files sdeQ_t_x.txt which show the Paulis used and change of sde for the unitaries in the corresponding chanQ_t_x.txt file.

Results: These contain the output for the unitaries with channel representation in ChanRep folder. The output files with prefix 'out' show more detail description of 
the number of nodes, etc in the tree (see description of the Algorithm). The ones with 'fin' just show some essential information.

Results_rand : These contain the output for the untiaries with channel representation in ChanRep_rand folder.
