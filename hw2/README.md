## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#2
### [Google Colab notebook](https://colab.research.google.com/drive/1eCHB3vza31MeJ4UZmUZox4_7-5TLm869?usp=sharing)
### Задание 2 - 10 баллов

- Загрузить набор данных [Spam Or Not Spam](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset)
- Попробовать и сравнить различные способы векторизации: **3 балла**
  - `sklearn.feature_extraction.text.CountVectorizer`
  - `sklearn.feature_extraction.text.TfidfVectorizer`
- Обучить на полученных векторах модели, с использованием кросс-валидации и подбором гиперпараметров: **3 балла**
  - `sklearn.tree.DecisionTreeClassifier`
  - `sklearn.linear_model.LogisticRegression`
  - Naive Bayes
- Сравнить качество обученных моделей на отложенной выборке - **1 балл**

- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**

## Dependencies and Licenses

This project makes use of the following libraries:

- **Pandas**: Data manipulation and analysis library. (License: BSD-3-Clause License).
  - **License and Copyright**: Refer to `/licenses/Pandas_LICENSE`
  - **State of Changes**: No changes were made to the original code.

- **tqdm**: A fast, extensible progress bar library. (License: MIT License).
  - **License and Copyright**: Refer to `/licenses/tqdm_LICENSE`
  - **State of Changes**: No changes were made to the original code.

- **scikit-learn**: Machine learning library featuring various algorithms, tools for working with data. (License: BSD License).
  - **License and Copyright**: Refer to `/licenses/scikit-learn_LICENSE`
  - **State of Changes**: No changes were made to the original code.

- **Jupyter Notebook**: Open-source web application to help build and share code. (License: Modified BSD License).
  - **License and Copyright**: Refer to `/licenses/Jupyter_LICENSE`
  - **State of Changes**: No changes were made to the original code.

- **Python 3.10**: The programming language used for this project.

Please refer to the `licenses` directory for the complete license files of these dependencies.
