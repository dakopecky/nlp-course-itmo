## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#4
### [Google Colab notebook](https://colab.research.google.com/drive/1d_Z66wi4qzf3lDi2ulPCHQnVgS9AT9rn?usp=sharing)
### Задание 4 - 10 баллов

Исходный набор данных - [Fake and real news dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

- Реализовать классификацию двумя моделями: CNN, LSTM - **6 баллов = 3 + 3**
- Сравнить качество обученных моделей **1 балл**
- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**

Примеры: [Using Convolution Neural Networks to Classify Text in PyTorch](https://tzuruey.medium.com/using-convolution-neural-networks-to-classify-text-in-pytorch-3b626a42c3ca), [LSTM in Pytorch](https://wandb.ai/sauravmaheshkar/LSTM-PyTorch/reports/Using-LSTM-in-PyTorch-A-Tutorial-With-Examples--VmlldzoxMDA2NTA5)

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

- **[PyTorch](https://github.com/pytorch/pytorch)**: An open-source machine learning library for Python, used for a range of tasks including deep learning. (License: Custom License).
  - **License and Copyright**: Refer to [`/licenses/PyTorch_LICENSE`](./licenses/PyTorch_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Jupyter Notebook](https://github.com/jupyter/notebook)**: Open-source web application to help build and share code. (License: Modified BSD License).
  - **License and Copyright**: Refer to [`/licenses/Jupyter_LICENSE`](./licenses/Jupyter_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Python 3.10](https://www.python.org/downloads/release/python-3100/)**: The programming language used for this project.

Please refer to the [`licenses`](./licenses) directory for the complete license files of these dependencies.
