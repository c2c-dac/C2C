## C2C Readme

Welcome to the homepage of C2C!

There are three folders in the root folder. 

### Source Code
`src/` is the folder containing the source code of C2C. More specifically, there are four files:
- `c2ir.cpp`, is code for the frontend translation component in C2C.
- `ir2c.cpp`, is code for the backend translation component in C2C.
- `func.ll`, is code for gates' patterns.
- `c2cnf.cpp`, is code for the Tseitin encoding component in C2C.
### Benchmarks
`benchmarks/` is the folder containing all the miter circuits in our experiment. We used all circuits from HWMCC'12/15, ITC'99,
IWLS'05/22, and ISCAS'85/89. We also employed a set of arithmetic circuits. 
### Combination of C2C with Different SAT Solvers

`solvers/` is the folder containing the binary executable files of SAT solvers in our experiment, the binary executable files of C2C, and the implementations of combining C2C with the SAT solvers.

- `C2C+Kissat.py`, the implementations of combining C2C with [Kissat](https://github.com/arminbiere/kissat).
- `C2C+MiniSAT.py`, the implementations of combining C2C with [MiniSAT](https://github.com/niklasso/minisat).
- `C2C+CaDiCaL.py`, the implementations of combining C2C with [CaDiCaL](https://github.com/arminbiere/cadical).
- `C2C+MAB-DC.py`, the implementations of combining C2C with [Kissat_MAB-DC](https://github.com/Jinjin680/Kissat_MAB-DC).
- `C2C+Lingeling.py`, the implementations of combining C2C with [Lingeling](https://github.com/arminbiere/lingeling).
- `WORK.md`, the description of running the combination of C2C and SAT solvers.


Thanks!
