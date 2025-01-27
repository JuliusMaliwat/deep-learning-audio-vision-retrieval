# Deep Learning for Audio, Vision & Image Retrieval

## 1. System Requirements

### Language
- Python

### Platform
- Google Colab (Recommended)
- Local Environment (Optional)

### Libraries
- Install dependencies via `requirements.txt` (for local execution only)

## 2. Project Structure

```
deep-learning-audio-vision-retrieval/
│── notebooks/
│   ├── environmental_sound_classification/
│   │   ├── 01_overview_and_preprocessing_ml.ipynb  # Data overview & preprocessing
│   │   ├── 02_training_and_evaluation_ml.ipynb  # Traditional ML training & evaluation
│   │   ├── 03_preprocessing_for_dl.ipynb  # Preprocessing for deep learning
│   │   ├── 04_training_and_evaluation_dl.ipynb  # Deep learning training & evaluation
│   ├── low_light_object_detection/
│   │   ├── 01_overview.ipynb  # Problem statement & dataset exploration
│   │   ├── 02_preprocessing.ipynb  # CLAHE-based preprocessing
│   │   ├── 03_training.ipynb  # YOLOv8 model fine-tuning
│   │   ├── 04_test_evaluation.ipynb  # Model testing & performance evaluation
│   ├── vehicle_image_retrieval/
│   │   ├── 01_overview.ipynb  # Introduction to image retrieval
│   │   ├── 02_feature_extraction.ipynb  # Feature extraction with EfficientNetB0
│   │   ├── 03_retrieval.ipynb  # Training & evaluation of retrieval models
│
│── demos/
│   ├── environmental_sound_classification/
│   │   ├── demo.ipynb  # Interactive demo for sound classification
│   │   ├── demo_environmental_sound_classification.mp4  # Video demo
│   ├── low_light_object_detection/
│   │   ├── demo.ipynb  # Interactive demo for object detection
│   │   ├── demo_low_light_object_detection.mp4  # Video demo
│   ├── vehicle_image_retrieval/
│   │   ├── demo.ipynb  # Interactive demo for retrieval
│   │   ├── demo_vehicle_image_retrieval.mp4  # Video demo
│
│── requirements.txt  # List of dependencies (for local execution only)
│── dsim_presentation.pdf  # Final presentation
│── README.md  # Project documentation
```

## 3. How to Run

### Google Colab (Recommended)
1. Open the desired notebook from the `notebooks/` folder.
2. Run all cells sequentially.
3. The necessary data and dependencies are handled inside the notebooks.

### Running Interactive Demos
1. Open the desired demo notebook from the `demos/` folder.
2. Run all cells to interact with the trained model.
3. Demos use **Gradio** for real-time visualization.

### Local Execution
1. Clone the repository or download the project folder.
   ```sh
   git clone https://github.com/JuliusMaliwat/deep-learning-audio-vision-retrieval.git
   cd deep-learning-audio-vision-retrieval
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the notebooks in Jupyter:
   ```sh
   jupyter notebook
   ```
4. Execute the required notebook step by step.


## 4. Data and Model Storage (Google Drive)

**Note:** Due to size constraints, trained models and processed datasets are **not included in the GitHub repository**. They can be accessed and downloaded from Google Drive:
- **Google Drive Repository:** [Deep Learning for Audio, Vision & Image Retrieval](https://drive.google.com/drive/folders/1u9bm2QU0I4cCt_H9jx1qW2AEnIE_AO1A?usp=sharing)

### Google Drive Structure
- **Trained Models:** Stored in the `models/` directory
- **Extracted Features & Embeddings:** Available in the `data/` directory
- **Preprocessed Datasets:** Also located in the `data/` directory


## 5. Notes

- **Raw datasets** are loaded via API calls within the notebooks and are not stored locally.
- Notebooks are **structured for independent execution**.
- Some experiments require a **GPU** for optimal performance.
- The `requirements.txt` file was generated from Google Colab and may contain extra dependencies.
- Ensure **internet connectivity** for proper dataset retrieval and execution.
- **Demo notebooks** are in the `demos/` folder, along with recorded video demonstrations.


