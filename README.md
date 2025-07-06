# 🧠 FiftyOne Researcher Playground
👋 *By researchers, for researchers.*

This repository contains a Jupyter Notebook demonstrating how to:

- Load diverse datasets: **images**, **video**, **point clouds**
- Perform core machine learning tasks: **classification**, **object detection**
- Integrate powerful plugins to:
  - Detect image quality issues
  - Find duplicate images
  - Perform semantic document search
  - Ask visual questions about your data
  - Detect outliers
  - Analyze sparse concepts and potential biases *(by Adonai)*
  - Validate visual-language model (VLM) performance *(by Adonai)*
  - Explore solutions with VoxelGPT *(by Adonai)*
- Evaluate models with built-in metrics

✅ Designed to help researchers improve dataset quality, measure model performance, and experiment with cutting-edge tools.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AdonaiVera/fiftyone-researcher-to-researcher
cd fiftyone-researcher-playground
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📓 Notebook

Open the notebook:

```bash
jupyter lab fiftyone_researcher_playground.ipynb
```

or

```bash
jupyter notebook fiftyone_researcher_playground.ipynb
```

Run each cell step by step.

---

## 🧩 Plugins Included

This project demonstrates the following plugins:

* Image Quality Issues
* Image Deduplication
* Semantic Document Search
* Visual Question Answering
* Outlier Detection
* Sparse Concepts *(Find Bias)*
* Validate VLM Efficiency *(Very cool)*
* VoxelGPT *(Advanced querying)*

> **Tip:** Activate plugins from the FiftyOne App sidebar after launching a session.

---

## 🎯 Evaluation Metrics

The notebook shows how to compute:

* **Classification Accuracy**
* **Detection mAP**

These metrics help validate your models and datasets.

---

## 🛠️ Contributing

Pull requests and plugin ideas are welcome!

---

## 📝 License

MIT License

````

---

## 📄 `requirements.txt`

Here’s a clean list:

```text
fiftyone
# For 3D/point cloud support
fiftyone[3d]
# (Optional) If you want Jupyter Lab
jupyterlab
````

---

## 🪄 Quick Setup Script (Optional)

If you prefer, you can also **copy-paste this script** to set everything up quickly:

```bash
# Clone repo
git clone https://github.com/YOUR_USERNAME/fiftyone-researcher-playground.git
cd fiftyone-researcher-playground

# Create a virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter lab demo.ipynb
```

