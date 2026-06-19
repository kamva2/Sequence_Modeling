# Grapheme-to-Phoneme Conversion using Encoder-Decoder LSTMs

This project implements sequence-to-sequence encoder-decoder architectures for Grapheme-to-Phoneme (G2P) conversion using PyTorch.

The project compares three sequence modelling approaches:

1. Bottleneck Encoder-Decoder
2. Fixed Context Vector Decoder
3. Attention-Based Decoder

The models are trained on the CMU Pronouncing Dictionary dataset (CMUdict).

---

## Key Concepts

- Sequence-to-Sequence Learning
- LSTMs from Scratch
- Encoder-Decoder Architectures
- Attention Mechanisms
- Cross-Attention
- Speech and Language Processing
- Grapheme-to-Phoneme Conversion

---

## Features

- Custom LSTM implementation (without nn.LSTM)
- Dot-product attention implementation
- Greedy decoding
- Hyperparameter tuning
- Phoneme Error Rate (PER) evaluation
- Attention heatmap visualisation

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Pandas

---

## Results

The attention-based encoder-decoder achieved the best performance by overcoming the hidden-state bottleneck problem.

Key findings:
- Attention improved convergence speed
- Lower Phoneme Error Rate (PER)
- Better handling of longer words
- Improved sequence alignment

---

## Repository Structure

- `notebooks/` → Main notebook
- `src/` → Model and training code
- `images/` → Generated plots and attention heatmaps
- `report/` → Assignment and final report

---

## Author
Kamva

```bash
