# EMG-Muscle-Activity-Detection
Python-based EMG signal processing for muscle relaxation and contraction detection
# EMG Muscle Activity Detection

## Project Overview

This project develops a Python-based EMG signal-processing system to distinguish between muscle relaxation and muscle contraction.

## Tools Used

* Python
* NumPy
* Pandas
* Matplotlib
* Google Colab

## Signal Processing

The simulated EMG signal is processed using:

1. Raw EMG signal generation
2. Full-wave rectification
3. RMS envelope analysis
4. Threshold-based activity detection

## Results

The RMS envelope increases during muscle contraction and remains lower during muscle relaxation.

The system detects the expected pattern:

**Rest → Contraction → Rest → Contraction → Rest**

## Conclusion

RMS-based EMG analysis successfully distinguishes between simulated muscle relaxation and contraction. The project demonstrates a simple signal-processing approach for detecting muscle activity.
