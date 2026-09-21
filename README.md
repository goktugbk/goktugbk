# Göktuğ Berke Karataş

Computer engineering, graduating October 2026. I work on computer vision — mostly image
classification and retrieval, and the data plumbing that decides whether either one works.

Looking for a junior machine learning / AI engineering role.

---

## Projects

### 🌿 Plant Vision — species identification and disease detection
Retrieval-based plant identification built to run on the device: `photo → encoder → embedding →
ANN search → taxonomy`, with abstention when confidence is low. Adding a species is a database
insert, not a training run. Taxonomy changes run as hash-sealed transactions with rollback,
because a bad merge silently relabels thousands of images instead of crashing.

Architecture, decisions and roadmap → **https://github.com/goktugbk/plant-vision-core**
*(source closed)*
`Python` `PyTorch` `OpenCLIP / BioCLIP` `sqlite-vec` `pytest`

### 🩺 X-Ray Disease Classification
Nine-class lung disease classification from chest X-rays. Fine-tuned YOLOv8l-cls on a
6,782-image dataset; **99.0% top-1 on a held-out 681-image test split** never used for model
selection. Streamlit interface for predictions, plus a feedback loop that collects wrong
predictions and retrains on the corrected samples.

**https://github.com/goktugbk/yolov8-xray-classification**
`Python` `YOLOv8` `Ultralytics` `OpenCV` `Streamlit`

### 🛒 E-Commerce Web Application
**https://github.com/goktugbk/ecommerce-web-app**
`Next.js` `Prisma`

---

## Tech

**Machine learning** — PyTorch, YOLOv8 / Ultralytics, OpenCLIP, OpenCV, NumPy
**Data** — SQLite, sqlite-vec, PostgreSQL, Prisma
**Web** — Python, JavaScript, Node.js, Next.js, Streamlit
**Tooling** — pytest, ruff, Git

---

## Contact

- **Email** — goktugberkekaratas@gmail.com
- **LinkedIn** — https://www.linkedin.com/in/goktug-berke-karatas/
