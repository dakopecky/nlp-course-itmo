## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#3
### [Google Colab notebook](https://colab.research.google.com/drive/1_6OG_ISWEm9Wancsw_sG4_vWE-L2MAK7?usp=sharing)
### Задание 3 - 10 баллов

- Загрузить набор данных [Spam Or Not Spam](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset) (или любой другой, какой вам нравится)
- Обучить модели и сравнить различные способы векторизации с помощью внутренней оценки (intrinsic):
  - Word2Vec SkipGram / CBOW (параметр sg в `gensim.models.word2vec.Word2Vec`) - **3 балла**
  - fastText (можно взять в gensim, или в fasttext как на семинаре) - **2 балла**
- Обучить на полученных векторах модели LogisticRegression и сравнить качество на отложенной выборке - **2 балла**

- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**

Примечания:

- Для получения более качественных эмбеддингов стоит предварительно сделать предобработку корпуса - отсеять стоп-слова, провести нормализацию и тп. Предобработка рассматривалась в первой лекции/семинаре
- В данном случае под intrinsic оценкой подразумевается просто использование методов `most_similar`, `doesnt_match`. Однако, если есть желание, можно измерить косинусное расстояние между отдельными парами слов и проверить, есть ли корреляция с корпусами для intrinsic-оценки, которые обсуждались на семинаре

## Dependencies and Licenses

This project makes use of the following libraries:

- **[Pandas](https://github.com/pandas-dev/pandas)**: Data manipulation and analysis library. (License: BSD-3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/Pandas_LICENSE`](./licenses/Pandas_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[tqdm](https://github.com/tqdm/tqdm)**: A fast, extensible progress bar library. (License: MIT License).
  - **License and Copyright**: Refer to [`/licenses/tqdm_LICENSE`](./licenses/tqdm_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**: Machine learning library featuring various algorithms, tools for working with data. (License: BSD License).
  - **License and Copyright**: Refer to [`/licenses/scikit-learn_LICENSE`](./licenses/scikit-learn_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[nltk](https://github.com/nltk/nltk)**: Natural Language Toolkit. (License: Apache License 2.0).
  - **License and Copyright**: Refer to [`/licenses/nltk_LICENSE`](./licenses/nltk_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[NumPy](https://github.com/numpy/numpy)**: Library for numerical computations. (License: BSD-3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/NumPy_LICENSE`](./licenses/NumPy_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Gensim](https://github.com/RaRe-Technologies/gensim)**: Library for topic modelling and document similarity. (License: LGPL-2.1 License).
  - **License and Copyright**: Refer to [`/licenses/Gensim_LICENSE`](./licenses/Gensim_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Jupyter Notebook](https://github.com/jupyter/notebook)**: Open-source web application to help build and share code. (License: Modified BSD License).
  - **License and Copyright**: Refer to [`/licenses/Jupyter_LICENSE`](./licenses/Jupyter_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Python 3.10](https://www.python.org/downloads/release/python-3100/)**: The programming language used for this project.

Please refer to the [`licenses`](./licenses) directory for the complete license files of these dependencies.
