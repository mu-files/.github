## About

Welcome to our code repository. mu-files LLC is a software development organization specializing in custom software infrastructure, libraries, and desktop utilities for image-processing tasks.

All packages here are released under the **BSD 3-Clause License**.

---

## Organization of the code

The software focuses heavily on **RAW image infrastructure, time-lapse compilation, and astrophotography data pipelines**.

| Repository / Module | Target Audience | Primary Focus |
| :--- | :--- | :--- |
| [**`mufusion`**](https://github.com/mu-files/mufusion/tree/main/mufusion) | Developers & Engineers | A lazy, fused image compute graph with a NumPy interface. Chains optimized image-processing primitives into native code, and works alongside NumPy and OpenCV. `pip install mufusion` |
| [**`muraw`**](https://github.com/mu-files/mufusion/tree/main/muraw) | Developers & Engineers | A Python library and CLI built on `mufusion`, providing a comprehensive API for native Adobe DNG manipulation, custom RAW rendering pipelines, and parallel batch processing. `pip install muraw` |
| [**`mu-dng-converter`**](https://github.com/mu-files/mufusion/tree/main/mu-dng-converter) | Astrophotographers & Editors | A lightweight, cross-platform desktop application. Transcodes and processes DNGs (compression, metadata operations), renders DNG sequences into MP4 videos or image sequences (ideal for timelapse footage), and converts astronomical FITS files to DNGs. Both source code and [built installer packages](https://github.com/mu-files/mufusion/releases) are available. |
| [**`muraspi`**](https://github.com/mu-files/mufusion/tree/main/muraspi) | Raspberry Pi camera users | Example code and benchmarks for Raspberry Pi setups. Includes scripts to capture raw frames from ZWO ASI or Raspberry Pi HQ Camera cameras directly to DNG, and performance benchmarks against PiDNG. |

---

## Licensing & Usage Terms

- **License**: [BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause). See each repository's `LICENSE` file for the full text.

---

## Feedback & Contributions

If this looks useful to you, your feedback, bug reports, and feature requests are incredibly valuable. Please feel free to open an issue!
