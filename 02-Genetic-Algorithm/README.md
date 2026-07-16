# Melody Reconstruction using Genetic Algorithm

This project was developed as part of an Artificial Intelligence course at the University of Tehran.

The project demonstrates how a Genetic Algorithm (GA) can reconstruct a target melody by evolving sequences of musical frequencies. A melody is first extracted from an audio file using Fast Fourier Transform (FFT), and then the GA gradually evolves candidate solutions until they closely match the target frequency sequence.

---

## Topics Covered

- Genetic Algorithms
- Evolutionary Optimization
- FFT-based Audio Analysis
- Melody Frequency Extraction
- Tournament Selection
- Single-Point Crossover
- Random Mutation
- Elitism
- Fitness Evaluation
- Audio Synthesis
- Data Visualization

---

## Genetic Algorithm Components

- Population Initialization
- Fitness Function (Mean Absolute Error)
- Tournament Selection
- Single-Point Crossover
- Random Mutation
- Elitism Strategy
- Best Fitness Tracking

---

## Libraries

- Python
- NumPy
- Matplotlib
- Librosa
- SciPy
- SoundFile

---

## Features

- Extracts note frequencies from `.wav` audio files using FFT
- Evolves melodies using a Genetic Algorithm
- Visualizes generated melody against the target melody
- Synthesizes the evolved melody into playable audio
- Generates both clean and enhanced audio with harmonics, vibrato, and echo effects

---

## Dataset

Target melodies are provided as `.wav` files, including:

- Fur Elise
- Harry Potter
- Game of Thrones
- Interstellar
- Bella Ciao
- Mario Theme
- Pink Panther
- Swan Lake
- Squid Game

---

## Results

The Genetic Algorithm progressively improves the generated melody over hundreds of generations by minimizing the frequency error between the candidate chromosome and the target melody.

The final chromosome can be converted back into an audio file, allowing the reconstructed melody to be listened to and compared with the original.

---

## Skills Practiced

- Evolutionary Computing
- Genetic Algorithms
- Audio Signal Processing
- FFT
- Optimization
- NumPy
- Scientific Computing
- Data Visualization

---

## Repository Structure

```
02-Genetic-Algorithm
│
├── Genetic_Algorithm_Melody.ipynb
├── musics/
├── generated_audio/
└── README.md
```
