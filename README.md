#Combinatorial Decision Making and Optimization - The Present Wrapping Problem (PWP)
### Marco Buiani & Daniele Verì

**Instructions for launching:**

### CP in MiniZinc [report](cp/report.pdf)

run `cp_solver.mzn` from the Minizinc IDE,
.dzn converted instances are provided inside the `cp/instances/` folder

### SMT in Z3:  [report](smt/report.pdf)
. `python3 smt/src/smt_solver.py smt/instances/<instance.txt>` produces output to the terminal

. `python3 smt/src/smt_solver.py smt/instances/<instance.txt> -o` creates output file in the same folder as input

. `python3 smt/src/smt_solver.py smt/instances/<instance.txt> --allow_rotations` allows rotation of each present

. `python3 smt/src/smt_solver.py smt/instances/<instance.txt> -v` produces a png image of the solution (requires python pillow)


### SAT in Z3:  [report](sat/report.pdf)
. `python3 sat/src/sat_solver.py sat/instances/<instance.txt>` produces output to the terminal
