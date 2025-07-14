# 🧠 FiftyOne Researcher Playground

👋 *By researchers, for researchers.*

[![FiftyOne Researcher Playground Slides](assets/slides.png)](https://link.voxel51.com/by-for-researchers)

*Click the image above to view the presentation slides*

This repository provides a hands-on Jupyter Notebook that demonstrates a **complete, research-grade computer vision workflow** using [FiftyOne](https://voxel51.com/fiftyone/). It is designed for transparency, reproducibility, and flexibility—empowering you to:

- **Load and explore diverse datasets:** images, video, and point clouds
- **Perform core ML tasks:** classification, object detection, and more
- **Visualize embeddings:** with UMAP and CLIP for interactive data exploration
- **Benchmark models:** run and compare state-of-the-art detectors (Faster R-CNN, RT-DETR, YOLOv11n) on COCO and other datasets
- **Evaluate with robust metrics:** precision, recall, F1-score, mAP, and per-class analysis
- **Integrate powerful plugins:** for bias detection, VLM efficiency, VQA, outlier detection, and more
- **Produce publication-ready outputs:** including LaTeX tables and detailed reports

✅ **Purpose:** Help researchers improve dataset quality, measure and compare model performance, and experiment with cutting-edge tools in a reproducible, extensible environment.

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AdonaiVera/fiftyone-researcher-playground
cd fiftyone-researcher-playground
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```
Or, install directly from the notebook cells for the latest plugin versions.


## 📓 Usage

Open the notebook:

```bash
jupyter lab demo.ipynb
```
or
```bash
jupyter notebook demo.ipynb
```

Run each cell step by step. The notebook is modular—feel free to skip to the sections most relevant to your research.


## 🧩 Plugins & Integrations

This project demonstrates advanced research plugins, including:

- **Sparse Concepts (SpLiCE):** Find dataset biases and decompose core concepts
- **Visual Question Answering (Janus Pro VQA):** Ask questions about your data
- **Validate VLM Efficiency:** Analyze visual-language model performance

## 🎯 Model Evaluation & Research Outputs

The notebook shows how to:

- Apply multiple detection models to the same dataset
- Compute and compare metrics: **accuracy, precision, recall, F1-score, mAP**
- Generate per-class and aggregate reports
- Produce LaTeX tables for direct inclusion in research papers

## 📈 Example Research Workflow

1. **Load datasets** (images, video, point clouds, Hugging Face Hub)
2. **Visualize and explore** with embeddings and interactive dashboards
3. **Apply and compare models** (Faster R-CNN, RT-DETR, YOLOv11n)
4. **Evaluate results** with robust metrics and ablation studies
5. **Integrate plugins** for bias, quality, and advanced analysis
6. **Export results** for publication or further research

## 👥 Contributors

This workshop was developed and maintained by:

- [Adonai Vera](https://github.com/AdonaiVera) 
- [Paula Ramos](https://github.com/paularamo) 

We welcome more contributors! If you have ideas for new plugins, research workflows, or improvements, please open an issue or pull request.

## 💬 Community & Support

- [FiftyOne Documentation](https://docs.voxel51.com/)
- [FiftyOne Discord Community](https://community.voxel51.com/)
- [Voxel51 GitHub](https://github.com/voxel51/fiftyone)

We welcome more contributors to extend support for new Research! 
