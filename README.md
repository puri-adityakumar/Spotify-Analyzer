# Spotify Analyzer

This project implements a lyric matching system that takes a snippet of song lyrics as input and returns the most similar song(s) from the Spotify Million Song Dataset. The system leverages TF-IDF vectorization combined with cosine similarity and includes enhanced text preprocessing (cleaning, stopword removal, and stemming) to improve matching performance.

## Installation

### Setup

Clone the repository:

```bash
git clone https://github.com/puri-adityakumar/Spotify-Analyzer
cd Spotify-Analyzer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Dataset

Download the Spotify Million Song Dataset from [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/57651-spotify-songs/data) and place the CSV file in your desired directory. Update the `dataset_path` variable in the notebook accordingly.

## Usage

1. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
2. **Run the Cells Sequentially:**
   - Import necessary libraries.
   - Load and preprocess the dataset.
   - Apply TF-IDF vectorization.
   - Use cosine similarity to find matching songs.
3. **Test the System:**
   - Modify the `query_lyric` variable to test different lyric snippets.
   - Run the prediction functions to retrieve top-matching songs.

## License

This project is licensed under the MIT License.

