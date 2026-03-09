---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
toc: true
toc_label: "Projects"
toc_icon: "flask"
---

## Featured Project

### Hyperspectral Image Classification with FPGA Acceleration

**Goal**: End-to-end demonstration of hardware-software co-design for real-time spectral analysis.

| | |
|---|---|
| **Status** | 🔄 In Progress |
| **Repo** | [github.com/yfd6433162](https://github.com/yfd6433162) *(coming soon)* |
| **Tech Stack** | Python · NumPy · Scikit-learn · Intel HLS · Verilog |

#### System Architecture

```
Raw Hyperspectral Cube
        │
        ▼
[Python] Spectral Preprocessing
   • Calibration & normalization
   • Dimensionality reduction (PCA/UMAP)
        │
        ▼
[Python → FPGA] Classification Engine
   • Bottleneck analysis
   • HLS implementation of hot path
        │
        ▼
[FPGA] Real-time Inference
   • < 1ms per spectral pixel
   • Output: class map overlay
```

#### Development Phases

- ✅ **Phase 1**: Python baseline implementation
  - Hyperspectral dataset loading and preprocessing
  - SVM / Random Forest / CNN classification benchmarks
- 🔄 **Phase 2**: Bottleneck analysis & HLS prototyping
  - Profiling to identify compute-bound operations
  - Intel oneAPI HLS implementation
- 📋 **Phase 3**: FPGA integration & verification
- 📋 **Phase 4**: GitHub publication with English README + demo

---

## Background Projects

### FPGA-Accelerated Laser Microscopy *(Master's Research, University of Tokyo)*

Real-time image acquisition and processing for laser scanning microscopy using Intel FPGA.

- Custom camera interface (parallel bus, LVDS)
- Real-time histogram generation for focus feedback
- Integration with imaging flow cytometry pipeline

**Outcome**: Enabled 10× faster acquisition vs. software-only approach.

---

### Hyperspectral Imaging System *(Industry, 2020–2023)*

Full-stack development of a production hyperspectral imaging system.

- Optical design consultation → sensor selection → firmware → data pipeline → ML analysis
- Python-based spectral library with automated reporting
- Deployed in industrial inspection context

*(Source code: internal; architecture overview available on request)*

---

## Skills Demonstrated

| Skill | Evidence |
|-------|----------|
| FPGA design (Verilog, HLS) | Master's research + 3 years industry + Published book |
| Hyperspectral imaging | 5+ years, production systems |
| Python / ML engineering | End-to-end pipelines, TensorFlow/PyTorch |
| Technical writing | 100+ copies sold |
| System design | Camera → FPGA → Output, full stack |

[About Me →](/portfolio/about/){: .btn .btn--primary}
[My Book →](/portfolio/book-en/){: .btn .btn--info}

## Featured Project

### Hyperspectral Image Classification with FPGA Acceleration

**Goal**: End-to-end demonstration of hardware-software co-design for real-time spectral analysis.

| | |
|---|---|
| **Status** | 🔄 In Progress |
| **Repo** | [github.com/yfd6433162](https://github.com/yfd6433162) *(coming soon)* |
| **Tech Stack** | Python · NumPy · Scikit-learn · Intel HLS · Verilog |

#### System Architecture

Raw Hyperspectral Cube
│
▼
[Python] Spectral Preprocessing
• Calibration & normalization
• Dimensionality reduction (PCA/UMAP)
│
▼
[Python → FPGA] Classification Engine
• Bottleneck analysis
• HLS implementation of hot path
│
▼
[FPGA] Real-time Inference
• < 1ms per spectral pixel
• Output: class map overlay

#### Development Phases

- ✅ **Phase 1**: Python baseline implementation
  - Hyperspectral dataset loading and preprocessing
  - SVM / Random Forest / CNN classification benchmarks
- 🔄 **Phase 2**: Bottleneck analysis & HLS prototyping
  - Profiling to identify compute-bound operations
  - Intel oneAPI HLS implementation
- 📋 **Phase 3**: FPGA integration & verification
- 📋 **Phase 4**: GitHub publication with English README + demo

---

## Background Projects

### FPGA-Accelerated Laser Microscopy *(Master's Research, University of Tokyo)*

Real-time image acquisition and processing for laser scanning microscopy using Intel FPGA.

- Custom camera interface (parallel bus, LVDS)
- Real-time histogram generation for focus feedback
- Integration with imaging flow cytometry pipeline

**Outcome**: Enabled 10× faster acquisition vs. software-only approach.

---

### Hyperspectral Imaging System *(Industry, 2020–2023)*

Full-stack development of a production hyperspectral imaging system.

- Optical design consultation → sensor selection → firmware → data pipeline → ML analysis
- Python-based spectral library with automated reporting
- Deployed in industrial inspection context

*(Source code: internal; architecture overview available on request)*

---

## Skills Demonstrated

| Skill | Evidence |
|-------|----------|
| FPGA design (Verilog, HLS) | Master's research + 3 years industry + Published book |
| Hyperspectral imaging | 5+ years, production systems |
| Python / ML engineering | End-to-end pipelines, TensorFlow/PyTorch |
| Technical writing | 100+ copies sold |
| System design | Camera → FPGA → Output, full stack |

[About Me →](/portfolio/about/){: .btn .btn--primary}
[My Book →](/portfolio/book-en/){: .btn .btn--info}