# Pupil Dilation Analysis in Spatial Emotion Detection Tasks

This project analyzes average pupil diameter and reaction times during cued and uncued trials across multiple spatial eccentricity groups and experimental blocks. The data comes from experimental conditions involving emotional face stimuli (Happy, Angry, Neutral) and spatial cues.

## 📁 Project Structure
─ D2-8_Q1.ipynb # Jupyter Notebook containing all analysis and plots
─ pupil_diameter_cued_plot.png # Plot: Average pupil diameter (Cued Trials)
─ pupil_diameter_uncued_plot.png # Plot: Average pupil diameter (Uncued Trials)
─ D2-8_ATP.pdf # Final report with interpretations and plots
─ D2-8/ # DATASET


## 📊 Overview

### Objectives:
1. Merge and process trial data across blocks (E1, E2, E3).
2. Compute and visualize:
   - Average pupil diameter over time for cued and uncued trials.
   - Reaction times across spatial locations and emotions.
3. Compare attentional and emotional modulation on pupil dynamics and behavior.

### Eccentricity Grouping:
- **Group 1**: ±4°
- **Group 2**: ±8°
- **Group 3**: 0°
- **Group 4**: ±16°

### Key Visualizations:
- **Line plots** showing average pupil diameter over time per group and experiment.
- **Bar plots** comparing reaction times across cue validity and emotions.

## 📈 Results Summary

### Pupil Diameter (Cued vs. Uncued):
- **Stronger dilation** observed in cued trials, especially post-250ms.
- **Group 2 and 4** show peak dilation (suggesting peripheral attentional effort).
- **Uncued trials** show delayed and reduced dilation, with greater variability.

### Reaction Time:
- **Cued trials** consistently yield **faster responses** across all eccentricities.
- **Neutral stimuli** under uncued conditions are the **slowest to detect**.
- **Happy stimuli** are detected the fastest when cued, hinting at emotional salience.

## 📚 Files

| File | Description |
|------|-------------|
| `D2-8_Q1.ipynb` | Code for processing data, computing averages, and plotting |
| `pupil_diameter_cued_plot.png` | Line plot for cued trials across eccentricities |
| `pupil_diameter_uncued_plot.png` | Line plot for uncued trials across eccentricities |
| `D2-8_ATP.pdf` | Summary report with detailed observations and interpretations |

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pupil-dilation-analysis.git
   cd pupil-dilation-analysis
2. Launch the notebook:
   jupyter notebook D2-8_Q1.ipynb
