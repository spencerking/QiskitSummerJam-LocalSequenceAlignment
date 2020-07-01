# QiskitSummerJam-LocalSequenceAlignment

Our goal is to implement the Quantum Pattern Recognition (QPR) algorithm described in the paper [Quantum Pattern Recognition for Local Sequence Alignment](https://ieeexplore.ieee.org/document/8269076) by Konstantinos Prousalis and Nikos Konofaos.

## Approach

1. Generate a substitution matrix of matches and non-matches using the classical Smith-Waterman algorithm.
2. Transform the matrix H such that the diagonals become horizontal or vertical lines (Encode the array such that is can become the input to the quantum algorithm).
3. Apply BB (Black Box, binomial classifier).
4. Apply QFT.
5. Measure and execute.
6. Classically apply pattern localization to verify the result (dot matrix algorithm).

## Dependencies

Built with the most recent versions of Qiskit and numpy (as of June 30, 2020).

## Team Members

[Spencer King](https://github.com/spencerking)

[Mingi Ryu](https://github.com/mingir2)
