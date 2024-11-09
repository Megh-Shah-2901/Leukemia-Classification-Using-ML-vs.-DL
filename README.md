
# Leukemia Classification Using ML vs. DL

This project compares machine learning and deep learning approaches for classifying leukemia images. The deep learning model uses ResNet34 as a feature extractor, while traditional machine learning classifiers (e.g., SVM, Logistic Regression) are also applied to the feature data to evaluate performance.

## Project Structure

- **Importing Libraries**: Loads the required packages like `torch`, `torchvision`, and `scikit-learn` for model training and evaluation.
- **Data Loading and Preprocessing**: Transforms and standardizes the images, creating custom datasets for training and validation.
- **Feature Extraction**: Uses ResNet34 for feature extraction from images, which feeds into both ML and DL classifiers.
- **ML and DL Model Training**: Implements machine learning models alongside a neural network classifier for comparative analysis.
- **Evaluation**: Calculates and tracks performance metrics for both ML and DL approaches.

## Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt
```

## Dataset Setup

### Downloading the Dataset from Kaggle

Since this project was initially developed on Kaggle, where the dataset is readily available, you’ll need to download the dataset for running it locally.


#### Manual Download

1. Go to the Kaggle website and log in to your account.
2. Navigate to the dataset page [Leukemia Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification/data), and download the dataset as a ZIP file manually.
3. Unzip the downloaded dataset and place it in the data directory specified in the notebook. Update the data path in the notebook if necessary.

## Usage

1. Clone the repository.
2. Place the dataset in the correct directory as mentioned above.
3. Open the Jupyter notebook `leukemia-classification-ml-vs-dl.ipynb` and run cells sequentially to execute the pipeline.

## Results

After training, the notebook outputs key metrics such as accuracy and loss for each model type, enabling a comparative analysis of ML and DL techniques for leukemia classification.

---

### License

MIT License. See [LICENSE](LICENSE) for details.
