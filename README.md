# 🌊 Underwater Image Color Enhancement using PSO (Python)

## 📌 Project Overview

This project enhances underwater images using **Particle Swarm Optimization (PSO)**. Underwater photos often suffer from color distortion, low contrast, and poor visibility due to light absorption and scattering. This project applies optimization techniques to automatically improve image quality.

The implementation is done in **Python**, using image processing and optimization libraries.

---

## 🚀 Features

* Enhances underwater image colors automatically
* Improves brightness and contrast
* Uses Particle Swarm Optimization for parameter tuning
* Works on multiple images in batch
* Stores enhanced outputs in results folder
* Easy to run and modify

---

## 🧠 Algorithm Used: Particle Swarm Optimization (PSO)

PSO is a population-based optimization technique inspired by bird flocking behavior.

In this project:

* Each particle represents enhancement parameters
* Fitness function evaluates image quality
* Particles update positions to find best enhancement
* Final optimized parameters improve image clarity

---

## 📂 Project Structure

```
Underwater-image-color-enhancement-with-PSO/
│
├── main.py              # Main execution file
├── PSO.py               # PSO algorithm implementation
├── utility.py           # Image processing functions
├── requirements.txt     # Required Python libraries
├── images/              # Input underwater images
├── results/             # Enhanced output images
└── NUCE_flowchart.png   # Workflow diagram
```

---

## 🛠️ Requirements

Install required libraries using:

```
pip install -r requirements.txt
```

Common libraries used:

* numpy
* opencv-python
* matplotlib
* scikit-image

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone <repository-link>
cd Underwater-image-color-enhancement-with-PSO
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Add underwater images to **images/** folder

4. Run the program

```
python main.py
```

5. Enhanced images will be saved in **results/** folder.

---

## 📊 Sample Results

The project includes sample input images and their enhanced outputs inside the results folder.

Enhancement improves:

* Color balance
* Contrast
* Sharpness
* Visibility of underwater objects

---

## 💡 Applications

* Marine research
* Underwater robotics
* Ocean exploration
* Archaeology imaging
* Photography enhancement

---

## 🔧 Future Improvements

* Real-time video enhancement
* Deep learning based enhancement
* GUI interface using Tkinter or Streamlit
* Integration with underwater drones
* Evaluation metrics like PSNR, SSIM

---

## 👩‍💻 Author

**Shaik Asma**
CSE Graduate | AI Enthusiast

---

## ⭐ If You Like This Project

Give it a star on GitHub and share with others! 😊
