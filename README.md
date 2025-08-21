# 🧵 AI-Fashion Lab @ NPUST, Taiwan

Welcome to the **AI-Fashion Lab**, based at the Department of Fashion Design & Management, **National Pingtung University of Science and Technology (NPUST), Taiwan** 🇹🇼.  
Our mission is to advance research at the intersection of **artificial intelligence and fashion**, fostering collaboration between students, interns, and faculty members.

---

## 🔬 Research Focus
- 👕 **Outfit Segmentation** — instance/semantic segmentation of garments  
- 🎨 **Color Understanding** — XKCD-based color clustering & calibration  
- 🤖 **Multimodal AI for Fashion** — combining vision, language, and design  
- 📸 **Real-world Benchmarking** — evaluating models across devices & lighting  

---

## 📂 Organization Structure
Repositories under this GitHub Organization are organized as follows:

| Repository Name                          | Description                                    |
|------------------------------------------|------------------------------------------------|
| `ai-fashion-lab-home`                    | Central hub with documentation & links        |
| `project-outfit-segmentation`            | YOLOv8-Segmentation of fashion outfits        |
| `project-color-detection`                | Dominant color detection with XKCD calibration|
| `datasets-fashion`                       | Scripts & metadata for fashion datasets       |
| `internship-2025-summer`                 | Reports, codes & results from interns (2025)  |
| `tools-evaluation`                       | Shared evaluation and visualization scripts   |

---

## 🛠️ Setup Guide

### 1. Clone a Repository
```bash
git clone https://github.com/ai-fashion-lab-npust/project-outfit-segmentation.git
cd project-outfit-segmentation
````

### 2. Create a Python Environment

We recommend using **conda** or **venv**:

```bash
conda create -n fashionlab python=3.10 -y
conda activate fashionlab
```

### 3. Install Dependencies

Each repository includes its own `requirements.txt`.
For example:

```bash
pip install -r requirements.txt
```

### 4. Dataset Access

* Some datasets are public (e.g., DeepFashion, COCO).
* Internal datasets are available upon request (NPUST account required).
* Place datasets under a standard directory:

```
data/
 ├── train/
 ├── val/
 └── test/
```

### 5. Running Experiments

Typical training command (example with YOLOv8):

```bash
yolo segment train data=train.yaml model=yolov8s-seg.pt epochs=50 imgsz=640
```

---

## 👥 Members

| Name                | Role            | GitHub Handle |
| ------------------- | --------------- | ------------- |
| Prof. Wei-Her Hsieh | Supervisor      | @weiher66             |
| Enock Isack         | Research Intern | @Enock02333   |
| ...                 | Contributors    | -             |

---

## 🤝 Contributing

We welcome contributions from **students, interns, and collaborators**.
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📜 License

All repositories are open-sourced under the **MIT License**, unless otherwise specified.

---

## 🌐 Website

AI Fashion Lab:
👉 [Website](https://ai4fashion.npust.edu.tw/))

