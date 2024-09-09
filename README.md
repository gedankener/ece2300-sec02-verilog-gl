# Pair/Triple Detector Lab

This lab implements a pair/triple detector using gate-level Verilog.

## Files
- PairTripleDetectorGL.v: Main implementation of the pair/triple detector
- PairTripleDetectorGL-test.v: Systematic test bench
- PairTripleDetectorGL-adhoc.v: Ad-hoc test bench
- ece2300-stdlib.v: Standard library for the course
- PairTripleDetectorGL-test.sh: Shell script to automate testing

## Running Tests
To run all tests and generate waveforms, execute:
./PairTripleDetectorGL-test.sh
Copy
This will lint the design, compile the test bench, run all tests, and generate a VCD file for waveform viewing.