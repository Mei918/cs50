# CS50 Final Project — Blood Cell Detection and Segmentation | Zongmei Gao (2025)

## 📌 Video Demo
YouTube Link: https://youtu.be/4GePsKTmTuQ?si=Tz8NtsOn1RvphrQ5  

This video demonstrates the features, workflow, and outcomes of my final project for CS50x 2025.

---

## 🧠 Project Description

Blood cell analysis is crucial in clinical diagnostics for identifying blood-related diseases such as anemia, leukemia, malaria, and infections. In this project, I developed a deep learning–based image processing tool that detects and segments blood cells from microscopic images.

The system processes input images, applies preprocessing, loads annotation masks, and overlays segmentation results using color-coded visualization. It uses computer vision and image-based dataset handling to show clear results for white blood cells, red blood cells, and platelets.

This is *not* intended for medical use — it is strictly a **learning and demonstration** project for CS50.

---

## 🚀 Features

- Load microscopic blood cell images and binary segmentation masks
- Automatic preprocessing and safe file reading
- Visual overlay using OpenCV and NumPy
- Dataset split management (train/val/test)
- Color-coded mask visualization for easy interpretation
- Runs entirely in Python (Colab-compatible)

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `app.py` (or notebook) | Main application code |
| `utils.py` (if used) | Helper functions (image load, mask overlay, visualization) |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

> If using Google Colab, project code is provided within the `.ipynb` notebook.

---

## 🛠️ Technologies Used

- Python 3
- Google Colab / Jupyter Notebook
- NumPy
- OpenCV
- PIL / Pillow
- Matplotlib
- KaggleHub Dataset Loader (optional)

---

## 📥 Dataset

- Dataset: **BCCD — Blood Cell Count and Detection Dataset**
- Source: Kaggle
- Used for image–mask pairing, segmentation, and visualization

---

## ▶️ How to Run the Project

1. Clone or download this project.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run in Python or open in Google Colab:
   ```bash
   python app.py
   ```
4. Output images will display or be saved depending on configuration.

---

## 🧪 Example Output

The visualization overlays a red segmentation mask on top of the original microscopic image, highlighting detected blood cells.

---

## 🔮 Possible Future Improvements

- Train a full U-Net or Mask-R-CNN model
- Add cell classification (RBC / WBC / Platelets)
- Add an interactive web UI (Flask / Streamlit)
- Implement live inference using webcam feed

---

## 🙏 Acknowledgments

- Harvard CS50 staff and community
- BCCD dataset authors and contributors
- Open-source developers who maintain core libraries

> **This project was created for educational purposes as part of CS50x 2025.**
