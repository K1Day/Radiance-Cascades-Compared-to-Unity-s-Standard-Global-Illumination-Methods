# Radiance Cascades Compared to Unity's Standard Global Illumination Methods

![Unity](https://img.shields.io/badge/Unity-6000.2.12f1-black?logo=unity)
![Pipeline](https://img.shields.io/badge/Pipeline-URP-blue)
![License](https://img.shields.io/badge/License-MIT-green)

Experimental materials for the DIGRA conference paper:
**"Comparative Evaluation of Real-Time Global Illumination Methods in Unity URP"**

## Overview

This project compares Radiance Cascades with Unity's standard global illumination
methods in the Universal Render Pipeline, measuring performance (FPS and frame time)
and visual quality.

## Repository Structure

| Folder | Description |
|--------|-------------|
| `data/` | Raw FPS and frame time datasets |
| `figures/` | Figures used in the paper |
| `Assets/` | Unity project files and test scenes |

## Requirements

- Unity 6000.2.12f1
- Universal Render Pipeline (URP)
- GPU with DirectX 11/12 support

## How to Reproduce

1. Install Unity 6000.2.12f1 via Unity Hub.
2. Clone this repository.
3. Open the project in Unity Hub.
4. Open the test scenes and record FPS and frame time.

## Test Environment

| Component | Model |
|-----------|-------|
| Engine | Unity 6000.2.12f1 (URP) |
| GPU | NVIDIA RTX 4060 Laptop GPU |
| CPU | Intel Core i7-13620H |

## Visual Comparison

Render videos are available in the
[YouTube Playlist](https://www.youtube.com/watch?v=daDjPJyB86o&list=PLaHv1eGKS6CyZF2IG05RV7KAHvvU5-xIQ).

## How to Cite

If you use these materials, please cite:

```bibtex
@inproceedings{gi_unity_urp,
  title     = {Comparative Evaluation of Real-Time Global Illumination Methods in Unity URP},
  author    = {Author Name},
  booktitle = {Proceedings of DIGRA},
  year      = {2026}
}
```

## Contact

For questions, please open an issue in this repository.

## License

This project is licensed under the MIT License.