# Experiments with OpenMP

This repository houses multiple implementations of various algorithms in OpenMP.

- [Experiments with OpenMP](#experiments-with-openmp)
  - [Overview](#overview)
  - [Results](#results)
    - [Reduce v1](#reduce-v1)
    - [Reduce v2](#reduce-v2)
    - [Numerical Integration](#numerical-integration)
    - [Prefix Sum](#prefix-sum)
    - [Merge Sort](#merge-sort)
    - [Bubble Sort](#bubble-sort)
    - [Longest Common Subsequence](#longest-common-subsequence)

## Overview

This repository contains multiple subfolders -

- `reduce_v1` - a program that computes the sum of an array in parallel using the OpenMP for loop construct
- `reduce_v2` - a program that computes the sum of an array in parallel using the OpenMP tasking constructs
- `numint` - a program that computes the numerical integration of an array in parallel using OpenMP
- `prefixsm` - a program that computes the prefix sum of an array in parallel using OpenMP
- `mergesort` - a program that sorts an array in parallel using the merge sort technique via OpenMP
- `lcs` - an OpenMP program that computes the longest common subsequence of an array in parallel
- `bubblesort` a parallel version of bubble sort using OpenMP

## Results

### Reduce v1

![Plot](reduce_v1/plots/reduce_plots-1.png)
![Plot](reduce_v1/plots/reduce_plots-2.png)
![Plot](reduce_v1/plots/reduce_plots-3.png)

### Reduce v2

![Plot](reduce_v2/plots/reduce_plots-1.png)

### Numerical Integration

![Plot](numint/plots/numint_plots-01.png)
![Plot](numint/plots/numint_plots-02.png)
![Plot](numint/plots/numint_plots-03.png)
![Plot](numint/plots/numint_plots-04.png)
![Plot](numint/plots/numint_plots-05.png)
![Plot](numint/plots/numint_plots-06.png)
![Plot](numint/plots/numint_plots-07.png)
![Plot](numint/plots/numint_plots-08.png)
![Plot](numint/plots/numint_plots-09.png)
![Plot](numint/plots/numint_plots-10.png)


### Prefix Sum

![Plot](prefixsum/plots/prefixsum_speedup_n-1.png)

### Merge Sort

![Plot](mergesort/plots/mergesort_speedup_n-1.png)

### Bubble Sort

![Plot](bubblesort/plots/bubblesort_speedup_n-1.png)

### Longest Common Subsequence

![Plot](lcs/plots/lcs_speedup_thread-01.png)
![Plot](lcs/plots/lcs_speedup_thread-02.png)
![Plot](lcs/plots/lcs_speedup_thread-03.png)
![Plot](lcs/plots/lcs_speedup_thread-04.png)
![Plot](lcs/plots/lcs_speedup_thread-05.png)
![Plot](lcs/plots/lcs_speedup_thread-06.png)
![Plot](lcs/plots/lcs_speedup_thread-07.png)
![Plot](lcs/plots/lcs_speedup_thread-08.png)
![Plot](lcs/plots/lcs_speedup_thread-09.png)
![Plot](lcs/plots/lcs_speedup_thread-10.png)
![Plot](lcs/plots/lcs_speedup_thread-11.png)
![Plot](lcs/plots/lcs_speedup_thread-12.png)
![Plot](lcs/plots/lcs_speedup_thread-13.png)
![Plot](lcs/plots/lcs_speedup_thread-14.png)
![Plot](lcs/plots/lcs_speedup_thread-15.png)
![Plot](lcs/plots/lcs_speedup_thread-16.png)
![Plot](lcs/plots/lcs_speedup_thread-17.png)
![Plot](lcs/plots/lcs_speedup_thread-18.png)

