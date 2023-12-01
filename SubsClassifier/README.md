# English language level determination in movies

## Project description

Development of an algorithm to determine the English language level according to the CEFR scale in movies using subtitle files for a language school.

## Data

There were 241 subtitle files available, as well as a file containing movie titles and annotations about the language level in them.

## Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, CatBoost, optuna, PyMuPDF (fitz), re, difflib, NLTK, SpaCy

## Overall conclusion

After creation of new features from the subtitle files, the balanced accuracy metric reached 83 even without text vectorization. The BERT transformer did not show high accuracy due to the small amount of data and significant class imbalance.

