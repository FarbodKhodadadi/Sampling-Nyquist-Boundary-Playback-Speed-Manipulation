
# Signal Processing: Sampling, Nyquist Boundary, and Playback Speed Manipulation

This repository contains my implementation of **Computer Assignment 2** from the *Signals and Systems* course (Spring 2025).  
The project explores core concepts in digital signal processing using MATLAB, focusing on **audio sampling, Nyquist boundary analysis, and playback speed manipulation** through different methods.

---

## 📚 Project Overview
The project is divided into three main parts:

1. **Introduction to MATLAB Sound I/O**
   - Importing, normalizing, and exporting audio signals
   - Converting stereo audio to mono
   - Working with MATLAB’s `audioread`, `sound`, and `audiowrite` functions

2. **Down-Sampling and Nyquist Boundary**
   - Reducing sampling rate systematically
   - Verifying Nyquist theorem through audio quality degradation
   - Comparing Fourier transforms of original vs. down-sampled signals

3. **Manipulating Playback Speed**
   - Playback frequency modification
   - Down-sampling without changing Fs
   - Frame dropping with different frame sizes
   - **Overlap-and-Add (OLA) method** with Hann and alternative windows

---

## 🛠️ Tools & Technologies
- **MATLAB (R2024a or later)**  
- Signal Processing Toolbox (optional for visualization)

---

## 🚀 Features Implemented
- Custom audio track recording and preprocessing
- Automated down-sampling script with flexible ratios
- Playback speed adjustment using four different strategies
- Frame-based processing with variable frame lengths
- Implementation of Overlap-and-Add with Hann window smoothing
- Fourier transform analysis and comparison plots

---

## 📂 Repository Structure

