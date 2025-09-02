# UC Berkeley CS 189/289A: Intro to Machine Learning (Fall 2025)

<p align="center"><img src="189_logo.png" alt="CS 189 Logo" width="50%"/></p>

Course materials and student resources for CS 189/289A.

- Course website: [eecs189.org/fa25](https://eecs189.org/fa25/)

## Repository Structure

- [lec](lec/): lecture demo notebooks
- [hw](hw/): homeworks
- [dis](dis/): discussion worksheets and notebooks

## Setup

- Install Python dependencies:
```bash
pip install -r requirements.txt
```

- Plotly image export (local runs only):
  - Default in this repo (`kaleido<1.0`): works without Chrome.
  - If you upgrade to `kaleido>=1.0`, install Chrome once:
```bash
kaleido_get_chrome
```
  - On Google Colab, no extra steps are needed; Plotly export works out of the box.
