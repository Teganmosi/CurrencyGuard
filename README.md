# CurrencyGuard

**CurrencyGuard** is a deep learning-powered tool for detecting counterfeit currency. Using pre-trained models—**VGG16**, **InceptionV3**, **ResNet50**, and **MobileNetV2**—it classifies currency images as **fake** or **genuine** with high accuracy. The project includes robust data augmentation, class balancing, and detailed evaluation metrics. A **Gradio**-based web interface (`app.py`) lets users upload images for instant predictions, making it practical for real-world use. Optimized for Google Colab with Google Drive integration, it's accessible for both training and deployment.

## Features
- **Multi-Model Detection**: Compare VGG16, InceptionV3, ResNet50, and MobileNetV2 for fake/genuine classification.
- **Advanced Preprocessing**: Data augmentation with rotation, zoom, flip, and brightness adjustments.
- **Class Balancing**: Uses class weights to handle imbalanced datasets.
- **Comprehensive Evaluation**: Accuracy, classification reports, and confusion matrices for each model.
- **Gradio Interface**: Upload currency images and get predictions with confidence scores.
- **Colab-Friendly**: Seamless integration with Google Drive for dataset access.

## Getting Started

### Prerequisites
- **Google Colab Account**: For GPU-accelerated training.
- **Google Drive**: Store dataset in `/content/drive/MyDrive/train` and `/content/drive/MyDrive/test`.
- **Python 3.8+**: For local setup or running the Gradio app.
- **Dataset**: Currency images labeled as fake or genuine.
- **Dependencies**: Listed in `requirements.txt`.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/CurrencyGuard.git
   cd CurrencyGuard

## Set Up a Virtual Environment (optional, for local setup):
    ```bash
    
      python -m venv venv
      source venv/bin/activate  # On Windows: venv\Scripts\activate

### Install Dependencies:
    ```bash
    pip install -r requirements.txt


## Using the Gradio App
Run the App:
    ```bash
          
      python app.py


Launches a web interface at http://localhost:7860 (or a public URL in Colab).


Contributing:

Contributions are welcome! To contribute:
Fork the repository.

Create a branch: git checkout -b feature-name.

Commit changes: git commit -m "Add feature".

Push and open a pull request.

Report issues at Issues.
License
This project is licensed under the MIT License (LICENSE).
Contact
For questions or feedback, open an issue or email obinalabi"gmail.com.



