
Sentiment Analysis with TextBlob (Beginner Friendly Project)

This is a simple and beginner-friendly project that uses **Natural Language Processing (NLP)** to detect the sentiment of a sentence (Positive, Negative, or Neutral) using the `TextBlob` library in Python.

---

Project Files

- `Sentiment_Analysis_TextBlob_Project.ipynb`: Jupyter notebook containing all steps of the sentiment analysis project.
- `README.md`: This file, containing project overview and usage instructions.

---

Features

- Minimal code (less than 30 lines!)
- Works inside Jupyter Notebook
- Uses `TextBlob`, a lightweight NLP tool
- Accepts both sample and custom input text

---

Requirements

- Python 3.x
- Jupyter Notebook
- TextBlob

To install dependencies, run the following commands inside your notebook:

```python
import sys
!{sys.executable} -m pip install textblob
!{sys.executable} -m textblob.download_corpora
```

---

How to Run

1. Open the notebook `Sentiment_Analysis_TextBlob_Project.ipynb` in Jupyter.
2. Run the cells one by one.
3. Try the predefined sentences or input your own text to test.

---

Example Output

```
Sentence: I love programming!
Sentiment: Positive 😊

Sentence: This is the worst movie ever.
Sentiment: Negative 😠

Sentence: I have no strong feelings about this product.
Sentiment: Neutral 😐
```

---

🤖 Built With

- [Python](https://www.python.org/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)

---

Author

Made with ❤️ by Praveer Ranjan Singh

---

License

This project is open-source and free to use for educational purposes.
