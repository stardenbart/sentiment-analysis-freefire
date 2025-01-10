# Sentiment Analysis for Free Fire App Comments

This project performs sentiment analysis on user comments of the Free Fire application from the Google Play Store. The analysis leverages a Bidirectional Long Short-Term Memory (BI-LSTM) model to classify user sentiments as positive, neutral, or negative.

## Features
- Extract comments from Google Play Store.
- Preprocess text data (e.g., cleaning, tokenization, stopword removal).
- Train and evaluate a BI-LSTM model.
- Visualize sentiment distribution.

## Dataset
The dataset used for this project is located in the file `dataset_sentimentAnalysis_ff.xlsx`. It consists of labeled comments from the Free Fire application.

## Dependencies
To run the code, ensure you have the following libraries installed:
```bash
pip install pandas numpy tensorflow keras scikit-learn matplotlib seaborn nltk openpyxl
```

### Key Libraries
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations.
- **tensorflow & keras**: Model building and deep learning framework.
- **scikit-learn**: Preprocessing and evaluation metrics.
- **matplotlib & seaborn**: Data visualization.
- **nltk**: Natural language processing.
- **openpyxl**: Handling Excel files.

## Folder Structure
```plaintext
.
├── sentimentAnalysisFreeFire.ipynb  # Main notebook with the code.
├── dataset_sentimentAnalysis_ff.xlsx # Dataset used for training and testing.
├── README.md  # Project documentation.
```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install the required libraries (as listed above).
3. Open the `sentimentAnalysisFreeFire.ipynb` file in Jupyter Notebook or any compatible editor.
4. Follow the instructions in the notebook to preprocess the data, train the model, and evaluate the results.

## BI-LSTM Model Architecture
- **Embedding Layer**: Converts tokens to dense vectors of fixed size.
- **Bidirectional LSTM Layer**: Captures context from both past and future.
- **Dense Layer**: Fully connected layer for classification.

## Results
Evaluation metrics and visualizations are provided in the notebook for:
- Accuracy
- Precision
- Recall
- F1 Score

## Future Enhancements
- Integrate with real-time comment scraping from the Play Store.
- Experiment with other advanced models (e.g., transformers).
- Perform hyperparameter tuning for better results.

## Author
Abdullah Farauk/Stardenbart
