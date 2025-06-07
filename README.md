**Quantum Implementation of Random Walks for Music Generation**

**Overview:**
This repository contains the full implementation of quantum-inspired algorithms for music generation based on Coined Quantum Walks and Szegedy Quantum Walks. The project is part of an M.Sc thesis focused on applying quantum random walk frameworks to generate polytonal, harmonically coherent musical sequences using Markovian dynamics encoded in musical graphs.

**Background and Motivation:**
Quantum walks extend classical random walks with quantum phenomena like superposition and interference, enabling novel generative processes. This project explores how these walks can be harnessed to generate music by modeling musical elements as stochastic processes on structured graphs, encoding modal harmony and rhythmic patterns.

**Contents**
1. **Coined Quantum Walk Implementation:**
Algorithms and code for generating music on graphs representing tuples of (chord, intensity, duration) using the coined quantum walk framework. Supports 3x3x3 and 5x5x5 tuple graphs with 8 nodes per musician.

2. **Szegedy Quantum Walk Implementation:**
Algorithms and code implementing the Szegedy quantum walk, constructed directly from classical transition matrices, applied to musical tuple graphs for quantum Markov chain music generation.

**Musical Graphs:**
Directed random graphs for four musicians, where each node is a tuple (chord, intensity, duration) based on modes derived from the F Major scale. Each musician is assigned a distinct mode to create polytonal but harmonically consistent music.

**MIDI Output:**
Scripts to convert quantum walk output sequences into MIDI files using music21. Different instruments are assigned per musician to enrich the harmonic texture.
