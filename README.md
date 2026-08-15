# ML Work

Machine learning coursework from CSE4502 — regression, classification, deep learning, and NLP on real-world datasets.

## Projects

| Project | Description | Artifacts |
|---------|-------------|-----------|
| [NYC Airbnb 2019](nyc-airbnb-2019/) | Predict nightly listing prices from location, room type, availability, and review features | notebook + `AB_NYC_2019_1.csv` |
| [Letter Recognition](letter-recognition/) | Classify 26 capital letters (A–Z) from 16 pixel-statistic features using ensemble methods | notebook + `letter-recognition.data.csv` |
| [Fashion-MNIST Classification](fashion-mnist-classification/) | Classical ML, MLP + PCA, and CNN approaches on 28×28 clothing images | notebook |
| [MNIST Semi-Supervised (100 Labels)](mnist-semi-supervised/) | Autoencoder + k-means clustering with only 100 labeled training examples | notebook |
| [CelebA Gender Classification](celeb-a-gender-classification/) | Binary image classification with CNN from scratch and VGG16 transfer learning | notebook + [PDF report](celeb-a-gender-classification/CelebA_Gender_Classification.pdf) |
| [IMDB Sentiment Analysis](imdb-sentiment-analysis/) | Movie review sentiment with GloVe embeddings and LSTM + Conv1D architecture | notebook + [PDF report](imdb-sentiment-analysis/IMDB_Sentiment_Analysis.pdf) |

Deep learning projects (CelebA, IMDB) include exported PDF reports with full outputs so results are viewable without downloading large image or text corpora.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter tensorflow
```

Open a project notebook in Jupyter and run from the top. Tabular projects include their data file in the same folder.
