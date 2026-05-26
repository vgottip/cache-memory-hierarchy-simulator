# Cache and Memory Hierarchy Simulator

A cache and memory hierarchy simulator built in C for analyzing the behavior of L1 and L2 cache configurations in a microprocessor architecture environment.

## Overview

This project implements a flexible L1 + L2 cache hierarchy simulator that evaluates how different cache parameters affect performance, area, and energy. The simulator was used with microbenchmarks such as `gcc` to study the impact of cache size, block size, associativity, and prefetching on overall memory system behavior.

## Features

- L1 and L2 cache hierarchy simulation
- Configurable cache size, block size, and associativity
- Cache hit and miss tracking
- Prefetching support
- Performance, area, and energy analysis
- Microbenchmark-based evaluation

## Build

Compile the simulator using:

```bash
make
