# Multi-Dimensional Visualization for AMPER project

**This Multi-Dimensional visualizatio** is a Python-based visualization tool developed for the **AMPER Project** (Atlas Multimédia Prosodique de l'Espace Roman). It provides a holistic assessment of prosodic factors and structural features of intonation from a geo-variational perspective. By avoiding discrete simplifications, the script allows for the simultaneous and global examination of melodic modulations ($f_0$), intensity values, and vocalic durations.

## How It Works
The pipeline translates three-dimensional prosodic data into a single, intuitive multidimensional space:
* **$f_0$ (Melody):** Represented by the base melodic curve.
* **Intensity:** Translated into **variable line thickness**; thicker segments indicate higher intensity.
* **Vocalic Duration:** Translated into **color intensity**; more intense/darker colors represent temporal contractions (faster speed), while softer/lighter colors indicate longer durations.

## Key Features
* **AMPER Database Integration:** Specifically designed to read and process standard `.txt` files available in the **BD-AMPER** database.
* **Comparative Superimposition:** Enables the comparison of multiple intonation patterns at a single glance. This is particularly useful for identifying convergences and divergences between different pragmatic functions, such as **declaratives (red)** and **interrogatives (blue)**.
* **Rhythmic-Intonational Diagnostics:** Helps researchers identify systematic accelerations, significant decelerations, and pre-pausal lengthening that might be missed in univariate plots.
* **Geo-Prosodic Documentation:** Supports the deep description of extensive intonational variation across the Romance language area without sacrificing generalizability.

---

## Requirements & Data
The tool is optimized for the data structures and research routines shared across the AMPER research network.

### Software
* **Python** environment.
* Standard libraries for data processing and graphic rendering (e.g., `Matplotlib`).

### Input Data
* **Standard AMPER `.txt` files:** The tool extracts intensity and vocalic interval durations directly from these files.

---

## Quick Start Guide

1. **Prepare Your Data:** Ensure your prosodic data is formatted as standard AMPER `.txt` files.
2. **Run the Script:** Load the Python routine to process the files and generate comparative graphics.
3. **Interpret the Visuals:**
    * Observe **line thickness** to locate energetic peaks.
    * Monitor **color intensity** to track speed; look for lighter colors to identify pre-pausal lengthening or specific movements in interrogative patterns.
4. **Compare Functions:** Superimpose different patterns to visualize how pragmatic functions (e.g., declarative vs. interrogative) differ across $f_0$, energy, and timing.

---

## Citation
If you use this tool in your research, please cite the presentation from the **CIDS 2026** congress:
> Lo Iacono, F., De Iacovo, V., & Romano, A. (2026). *Describir a variación da entoación de xeito global: unha nova forma de visualizar os datos do proxecto AMPER*. Congreso Internacional de Dialectoloxía e Sociolingüística (CIDS 2026), Santiago de Compostela.

---
**License:** Open source for the AMPER research community.
