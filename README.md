# Hate Speech Detection

## Overview
This project aims to detect hate speech in text using machine learning techniques. It classifies tweets as either hate speech or non-hate speech based on their content.

## Dataset
- **Dataset Name**: `twitter.csv`
- **Source**: A dataset containing tweets labeled as hate speech or not.
- **Attributes**:
  - `id`: Unique identifier for each tweet
  - `text`: The actual tweet content
  - `label`: 0 (Non-hate speech) / 1 (Hate speech)

## Technologies Used
- Python
- Scikit-Learn
- NLTK (Natural Language Toolkit)
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Installation
To run this project, install the required libraries:
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detection.git
   cd hate-speech-detection
   ```
2. Place `twitter.csv` in the project directory.
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook hate_speech_detection.ipynb
   ```

## Model Used
- **Vectorization**: CountVectorizer (from Scikit-Learn)
- **Classification Algorithm**: Decision Tree Classifier
- **Evaluation Metrics**: Accuracy Score, Confusion Matrix

## Results
- Achieved a certain level of accuracy (mention your accuracy score here).
- Visualization of confusion matrix and data distribution.

## Contributing
Feel free to open issues or submit pull requests if you would like to improve the project.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any inquiries, reach out via [your email] or [your GitHub profile].

