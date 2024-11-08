# Real-Time Frequency Spectrum Analysis of Live Audio Signal

This project captures live audio input from the microphone, processes it in real-time using Fourier Transform, and visualizes its frequency spectrum. It demonstrates basic real-time data processing, transformation, and visualization concepts, which can be relevant to data engineering.

## Project Overview

### Aim

To analyze the frequency spectrum of a live audio signal in real-time using Python, showcasing fundamental skills in data capture, transformation, and visualization.

### Introduction

Real-time data handling is a valuable skill in data engineering, especially for streaming applications and monitoring tasks. In this project, live audio data is captured through a microphone, processed to extract frequency information, and visualized in real-time. Although it’s focused on audio data, the project highlights skills like continuous data capture and transformation, which are essential in data engineering workflows.

### Implementation Details

- **Libraries Used**:
  - `pyaudio`: for audio data capture in real-time, simulating a live data stream
  - `numpy`: for numerical operations, including Fourier Transform for frequency analysis
  - `matplotlib`: for visualizing time-domain and frequency-domain data in real-time

- **Audio Parameters**:
  - **Sampling Rate**: 44,100 Hz (standard audio sampling rate)
  - **Channels**: Mono (1 channel)
  - **Chunk Size**: 2048 samples (processed per frame)

### Code Workflow

1. **Audio Capture**: The microphone captures real-time audio data.
2. **Data Transformation**: Each audio frame is converted into integer values and processed using Fourier Transform to extract frequency components.
3. **Real-Time Visualization**: Two plots display:
   - Time-domain signal, representing the audio waveform.
   - Frequency-domain spectrum, showing the magnitude of different frequency components in the signal.

### Results and Analysis

- **Real-Time Audio Visualization**: Shows the waveform and frequency spectrum of the audio as you speak into the microphone.
- **Interactive Feedback**: Allows you to see how changes in sound (like volume or pitch) affect the visualized signal in both time and frequency domains.

## Conclusion

This project demonstrates the basics of capturing, transforming, and visualizing real-time data. While focused on audio, it introduces data handling concepts that can be valuable in data engineering, such as working with live data streams, performing real-time transformations, and visualizing dynamic data.

---

### Requirements

- **Python 3.x**
- `pyaudio` library (Install with `pip install pyaudio`)
- `numpy` library (Install with `pip install numpy`)
- `matplotlib` library (Install with `pip install matplotlib`)

### Running the Project

1. Clone the repository and install the required libraries.
2. Run the script to start capturing audio data in real-time.
3. Observe the plots and watch how the time-domain and frequency-domain signals change with your voice.

---


