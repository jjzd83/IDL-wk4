## How to Run

To replicate the results, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/jjzd83/IDL-wk4.git](https://github.com/jjzd83/IDL-wk4.git)
    cd IDL-wk4
    ```

2.  **Set up the environment:**
    Ensure you have the required Python libraries installed. You can install them using pip:
    ```bash
    pip install pandas numpy tensorflow nltk scikit-learn matplotlib seaborn
    ```
    You will also need to download the NLTK data:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

3.  **Download the data:**
    Download the `train.csv`, `test.csv`, and `sample_submission.csv` files from the [Kaggle competition page](https://www.kaggle.com/c/nlp-getting-started/data) and place them in a relevant data directory. You will also need the pre-trained FastText embeddings (`wiki-news-300d-1M.vec`).

4.  **Run the Jupyter Notebook:**
    Open and run the `classifying-disaster-tweets.ipynb` notebook. The notebook is structured to run end-to-end. The `INTERACTIVE_SESSION` flag at the top of the notebook can be set to `False` to skip the time-consuming model training and discovery steps if you only wish to review the code structure.
