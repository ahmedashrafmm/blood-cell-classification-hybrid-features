[blood_cells_project_readme.md](https://github.com/user-attachments/files/28397022/blood_cells_project_readme.md)
# Blood Cells Image Processing Project

## Overview
This project focuses on applying fundamental image processing techniques to blood cell images using Python. The notebook demonstrates different preprocessing, enhancement, filtering, and analysis operations commonly used in medical imaging and computer vision.

The project was implemented in Google Colab and uses several Python libraries for image manipulation and visualization.

---

## Features

- Load and process blood cell images
- Convert images to grayscale
- Apply contrast stretching
- Perform manual histogram equalization
- Add salt-and-pepper noise
- Apply median filtering for noise removal
- Visualize images before and after processing
- Save processed images automatically

---

## Technologies & Libraries Used

- Python
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- OpenCV
- Google Colab
- OS module

---

## Project Structure

```bash
Blood_Cells_Project/
│
├── Blood_Cells_Project.ipynb   # Main notebook
├── dataset/                    # Original blood cell images
├── processed_images/           # Output processed images
└── README.md                   # Project documentation
```

---

## Image Processing Techniques

### 1. Grayscale Conversion
Converts RGB blood cell images into grayscale images for easier processing and analysis.

### 2. Contrast Stretching
Enhances image contrast by expanding the intensity range.

### 3. Histogram Equalization
Improves image visibility by redistributing pixel intensity values.

### 4. Salt-and-Pepper Noise
Artificial noise added to test filtering and restoration techniques.

### 5. Median Filtering
Removes noise while preserving edges and important image details.

---

## How to Run

### Option 1 — Google Colab
1. Upload the notebook to Google Colab.
2. Mount Google Drive.
3. Update dataset paths if necessary.
4. Run all notebook cells.

### Option 2 — Local Machine
1. Clone the repository:

```bash
git clone https://github.com/your-username/blood-cells-project.git
```

2. Install required libraries:

```bash
pip install numpy matplotlib pillow opencv-python
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run the notebook cells sequentially.

---

## Sample Output

The project generates processed blood cell images demonstrating:

- Enhanced contrast
- Equalized histograms
- Noise addition effects
- Noise removal using filters

---

## Learning Objectives

This project helps in understanding:

- Basic digital image processing concepts
- Medical image preprocessing techniques
- Noise handling and filtering
- Histogram operations
- Practical implementation of image enhancement algorithms

---

## Future Improvements

- Add blood cell classification using Machine Learning
- Integrate Deep Learning models
- Improve segmentation techniques
- Build a GUI for easier interaction
- Support larger medical imaging datasets

---

## Author

Ahmed Ashraf

Computer Engineering Student interested in:
- Artificial Intelligence
- Computer Vision
- Medical Imaging
- Machine Learning

---

## License

This project is for educational and academic purposes.

