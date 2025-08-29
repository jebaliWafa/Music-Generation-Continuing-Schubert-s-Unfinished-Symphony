# Music Generation: Continuing Schubert’s Unfinished Symphony

This project aims to **complete Franz Schubert’s legendary “Unfinished Symphony” (Symphony No. 8 in B minor)** using AI-based music generation.  

Schubert composed only two movements of this symphony before his death in 1828, leaving it incomplete. The work has fascinated musicians and scholars ever since, and its **mystique was recently revisited in a Huawei event** showcasing AI in the arts — yet no attempt was made to fully generate the continuation of the symphony using deep learning. This project explores that possibility.

---

## Project Overview

We explore **two deep learning architectures** to generate musical sequences that could plausibly continue Schubert’s unfinished symphony:  

1. **LSTM Networks**:  
   - Sequential models trained on notes, offsets, and durations.  
   - Capture long-range dependencies in the music to generate coherent melodies.

2. **GANs (Generative Adversarial Networks)**:  
   - Generator-discriminator setup trained on piano roll representations of MIDI files.  
   - Produces realistic sequences by learning the distribution of musical patterns.


## Highlights

- **Seed-based Generation**: Uses the existing motifs and sequences from Schubert’s symphony to generate new music.  
- **Comparison of Architectures**: Evaluates LSTM vs. GAN performance for continuity and musical coherence.  
- **Output**: Generated MIDI files:
  - `generated_LSTM.mid` — LSTM-based continuation  
  - `generated_GAN.mid` — GAN-based continuation 
