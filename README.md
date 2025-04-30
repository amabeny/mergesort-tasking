# mergesort-tasking

## Overview

This project implements a **parallel merge sort** algorithm in C++ using `std::thread`. It uses a configurable threshold to determine when to switch between sequential and parallel sorting. This project is benchmarked on the Centaurus cluster to demonstrate speedup with parallelism.

## Files

- `mergesort_seq.cpp`: Sequential merge sort implementation
- `mergesort_parallel.cpp`: Parallel merge sort using `std::thread`
- `Makefile`: For compiling both versions
- `bench_results.txt`: Timing results

## How to Compile

```bash
make clean
make
