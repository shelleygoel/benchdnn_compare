# Compare benchdnn output

This is a python script to compare benhdnn runs from different commits of MKLDNN. 

### What limitations can this script solve?
  - User has to spend time importing data in excel from different benchdnn runs.
  - User has to manually checkout each commit and run benchdnn, for e.x when investigating performance regression.

### Prerequisites

- Python 2.7.5
- Intel MKLDNN

## Limitations
- setup environment (num of threads, KMP_AFFINITY) before running benchdnn_compare.

## Usage (run benchdnn and compare)

`python benchdnn_compare.py build_run=True commits=[<>,<>,...] batch=<> raw_log_dir=<> `

build_run=True option enables:
- for each commit build MKLNDNN
- uses Intel MKLDNN directions for building MKLDNN.
- for each commit 

## Usage (compare runs)
`python benchdnn_compare.py raw_log_dir=<>`



