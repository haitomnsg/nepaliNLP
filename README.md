# NLP Pipeline — Nepali News Classification (np20ng)

An NLP pipeline for classifying Nepali news articles using the **np20ng Nepali News Classification Dataset**. The project covers text preprocessing, feature extraction (TF-IDF), model training (Naïve Bayes, SVM), evaluation, and visualization (word clouds, confusion matrices).

---

## Project Structure

```
NLP/
├── dataset/
│   ├── np20ng.csv            # The dataset (~1.1 GB, 200K+ articles)
│   └── aboutDataset.md       # Dataset documentation
├── reference/
│   └── NLP.ipynb             # Reference notebook
├── NLP_np20ng.ipynb          # Main notebook — the one to run
└── README.md                 # This file
```

---

## Environment Setup

### 1. Create the Conda Environment

```bash
conda create -n nlp_env python=3.10 -y
```

### 2. Activate the Environment

```bash
conda activate nlp_env
```

### 3. Install Required Packages

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud jupyter
```

> **Note:** No NLTK data downloads are required. The notebook uses a custom list of Nepali stopwords instead of NLTK's built-in stopword corpus.

---

## How to Run

1. **Navigate to the project directory:**

   ```bash
   cd d:\Subjects\AdvanceMachineLearning\NLP
   ```

2. **Activate the conda environment:**

   ```bash
   conda activate nlp_env
   ```

3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

4. **Open `NLP_np20ng.ipynb`** from the Jupyter file browser.

5. **Run all cells sequentially** using `Shift + Enter`, or use **Cell → Run All** from the menu bar.

---

## Important Notes

- **SVM Training Time:** Training the SVM classifier on the full 200K+ record dataset can take a significant amount of time. A sampling option is provided (commented out) in the notebook if you need faster iteration.

- **Nepali Word Cloud Font:** For the Word Cloud to render Nepali (Devanagari) text correctly, you may need to install a Devanagari-compatible font such as [Noto Sans Devanagari](https://fonts.google.com/noto/specimen/Noto+Sans+Devanagari) from Google Fonts. Without it, the word cloud may display placeholder characters.

- **Dataset Size:** The dataset file (`np20ng.csv`) is approximately **1.1 GB**. Loading it may take some time depending on your system's available RAM.
