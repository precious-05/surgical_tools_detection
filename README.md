## SURGICAL TOOLS DETECTION

A deep learning project for detecting and classifying surgical instruments in medical video frames using computer vision and neural networks.

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="36" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="36" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" width="36" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" alt="OpenCV" width="36" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="NumPy" width="36" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="36" />
</p>

---

## Video Demo

[Watch the demo video](https://github.com/user-attachments/assets/1fa79738-1b55-4f4b-8b87-00cb5ae7fa92)

## About

This project implements an automated system to detect and identify surgical tools in operating room videos. The system uses advanced deep learning techniques to recognize various surgical instruments in real-time, which can assist in surgical documentation, training, and safety monitoring.

## Features

- Real-time detection of surgical instruments in video frames
- Multi-class classification of different surgical tools
- Deep learning model trained on surgical video datasets
- Frame-by-frame analysis and tracking
- High accuracy detection pipeline
- Easy-to-use Jupyter notebook interface

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Core programming language |
| PyTorch | Deep learning framework |
| OpenCV | Computer vision and video processing |
| Jupyter Notebook | Interactive development and analysis |
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |

## Project Structure

**Surgical_Tools_Detection.ipynb** - Main notebook containing the complete pipeline:
- Data loading and preprocessing
- Model architecture and training
- Inference on video frames
- Results visualization and evaluation

**README.md** - Project documentation

## Methodology

### 1. Data Preparation
- Load and preprocess surgical video frames
- Normalize images and prepare dataset splits

### 2. Model Training
- Design and train deep learning architecture
- Optimize hyperparameters
- Validate model performance

### 3. Inference
- Apply trained model to test video frames
- Generate predictions with confidence scores
- Post-process and filter results

### 4. Evaluation
- Calculate performance metrics
- Visualize detection results
- Create comparative analysis

## Requirements

- Python 3.8 or higher
- PyTorch and torchvision
- OpenCV (cv2)
- NumPy
- Pandas
- Jupyter Notebook
- CUDA capable GPU (recommended for faster training)

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/precious-05/surgical_tools_detection.git
   ```

2. Navigate to the project directory:
   ```
   cd surgical_tools_detection
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:
   ```
   jupyter notebook Surgical_Tools_Detection.ipynb
   ```

5. Run all cells to train the model and generate predictions

## Key Results

The model successfully detects and classifies surgical instruments with high accuracy on test video frames. Visual outputs show bounding boxes around detected tools with confidence scores.

## Applications

- Operating Room Monitoring - Real-time tracking of surgical instrument usage
- Surgical Training - Educational tool for surgical residents
- Documentation - Automated logging of procedures and instrument usage
- Safety Systems - Detection of missing or misplaced instruments
- Research - Analysis of surgical technique and efficiency

## Future Improvements

- Expand to more surgical instrument categories
- Implement real-time video stream processing
- Deploy as REST API service
- Add temporal tracking across video sequences
- Optimize model for edge devices and mobile deployment

## Author

precious-05

## Repository

[https://github.com/precious-05/surgical_tools_detection](https://github.com/precious-05/surgical_tools_detection)

## License

This project is open source and available for educational and research purposes.

## Disclaimer

This project is intended for educational and research purposes. For clinical or medical applications, ensure proper validation, testing, and compliance with relevant medical device regulations and standards.
