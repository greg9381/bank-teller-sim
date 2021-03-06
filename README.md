# Bank Teller Simulation

## Prerequites
* Python 2
* `scipy` library for Python
* `pytest` library for Python, to run tests

## Running the program
* Run `bash run_all.sh` to run the simulation with each combination of parameters that was examined for this project.
* To run the simulation with a lunch break length of 0.75 hours with 2 tellers, run `python bank_sim.py 0.75 2`.
* Add the `--verbose` flag to view debug information.

## Running tests
* Run `pytest` (or `python -m pytest`) from the root directory of this project.
* Plots generated by the tests will be saved to the `test_output` directory.

## Output description
* The `sim_output` directory has two subdirectories: `plots` and `statistics`.
* Each has information about two measures: the number of customers in line, and the customer waiting times.

### Text output
* Each text file contains the mean, median, and standard deviation for a measure.

### Plot output
* The two red rectangles represent the two rush periods (where the first rush period is also the lunch period for the tellers)
* Each blue rectangle represents the time when a teller was on their lunch break
