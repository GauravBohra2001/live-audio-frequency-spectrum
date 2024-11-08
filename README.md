# Real-Time Frequency Spectrum Analysis of Live Audio Signal

This project captures a live audio signal, processes it in real-time, and visualizes its frequency spectrum using Fourier Transform. This example demonstrates real-time data streaming, transformation, and visualization, which are foundational skills in data engineering.

## Project Overview

### Aim

To analyze the frequency spectrum of a live audio signal in real-time using Python, showcasing skills relevant to streaming data processing.

### Introduction

In data engineering, real-time data processing is key for applications that require immediate insights or monitoring. This project captures live audio data through a microphone, converts the signal into integer values, and uses Fourier Transform to analyze and visualize frequency components in real-time. It mimics the handling of continuous data streams, similar to real-time data pipelines used in data engineering.

### Implementation Details

- **Libraries Used**:
  - `pyaudio`: for audio capture and streaming, emulating real-time data ingestion
  - `numpy`: for numerical transformations, similar to data transformations in data processing
  - `matplotlib`: for real-time visualization of data, analogous to monitoring dashboards

- **Audio Parameters**:
  - **Sampling Rate**: 44,100 Hz (standard audio sampling rate, similar to a data ingestion rate)
  - **Channels**: Mono (1 channel)
  - **Chunk Size**: 2048 samples (processed per frame, like a batch of streaming data)

### Explanation of Code

1. **Real-Time Data Capture**: Audio data is continuously ingested through a microphone, acting like a data stream.
2. **Data Transformation**: Audio samples are converted into integer format and processed using Fourier Transform, similar to real-time transformations in data engineering pipelines.
3. **Real-Time Visualization**: The time-domain signal and frequency spectrum are visualized in real-time, similar to monitoring real-time data streams on a dashboard.

### Results and Analysis

- **Signal Capture**: Successfully captured live audio signals.
- **Data Transformation**: Converted audio data for analysis.
- **Real-Time Plotting**: Visualized time-domain and frequency-domain data, emulating real-time monitoring.

## Conclusion

This project simulates a real-time data engineering pipeline, covering data ingestion, transformation, and visualization. The application of Fourier Transform demonstrates data transformation techniques, while Matplotlib allows for real-time monitoring, a crucial skill in data engineering.

---

### Requirements

- **Python 3.x**
- `pyaudio` library (Install with `pip install pyaudio`)
- `numpy` library (Install with `pip install numpy`)
- `matplotlib` library (Install with `pip install matplotlib`)

---

