# Partition Space Map (PSM)

A low-dimensional visualization framework for exploring the partition space of complex networks.

## Overview

The **Partition Space Map** provides a two-dimensional representation of all possible partitions of a network, enabling researchers to visualize, diagnose, and compare community detection algorithms. Rather than focusing on finding a single optimal partition, this framework characterizes the entire solution landscape.

## Key Features

- **Canonical partition labeling** using Restricted Growth Sequences (RGS)
- **Two-dimensional projection** onto the (L, Q) plane:
  - **L**: Structural level (Σ|Cₖ|²)
  - **Q**: Newman-Girvan modularity
- **Topology-independent bounds**: Upper and lower modularity envelopes computed directly from the network's deviation matrix
- **Algorithm-agnostic**: Compare outputs from different community detection methods in a unified framework
- **Exact enumeration** for small networks, sampling-based exploration for larger ones

## Installation

### Requirements

- Python 3.8+
- NumPy
- pandas
- igraph-python
- matplotlib (for visualization)
- NetworkX (optional, for LFR benchmark generation)

 
