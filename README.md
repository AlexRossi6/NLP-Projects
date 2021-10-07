# Combinatorial Decision Making and Optimization - The Present Wrapping Problem (PWP)
## Alex Rossi & Pietro Obbiso


### CP instructions:

run CP/src/CP.mzn or CP/src/CP_rotation.mzn from Minizinc and use the instances located in CP/src/input_mzn/....mzn

### SMT instructions
run the python notebook located in SMT/src/SMT.ipynb; choose the instances to solve in the second cell by changing the first row: inputs/....txt 

### Output check
For checking the correctness of the results run in the terminal the file plot_result.py by indicating the argument --solution_file with the path of the out text file.

out file with rotated pieces from minizinc are already rotated in the text file while out file from smt have a boolean next to the dimensions of each piece and the plot_result code takes care of rotating them.
