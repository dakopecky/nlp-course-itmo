## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#5
### [Google Colab notebook](https://colab.research.google.com/drive/1_Fg8HFJLH_3p_-SkHQE3Xsc5a_Eh5Pm8?usp=sharing)
### Задание 5 - 20 баллов

- Загрузить набор данных Lenta.ru с помощью пакета Corus
- Обучить LDA модель, постараться подобрать адекватные параметры (num_topics, passes, alpha, iterations…) - **4 балла**
- Визуализировать результаты работы LDA с помощью pyLDAvis - **2 балла**
- Посчитать внутренние метрики обученных моделей LDA (с разными параметрами) и сравнить, соответствует ли метрика визуальному качеству работы моделей - **2 балла**
- Обучить модель BigARTM, использовать не менее двух регуляризаторов, оценить качество с помощью метрик - **5 баллов**
- Реализовать визуализацию топиков BigARTM через pyLDAvis - **4 балла**

- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**

Примечание: подбирать параметры теметической модели можно также, как и для любой другой модели - на кроссвалидации, ориентируясь на метрики качества

## Dependencies and Licenses

This project makes use of the following libraries:

- **[Corus](https://github.com/natasha/corus)**: A collection of Russian NLP datasets. (License: MIT License).
  - **License and Copyright**: Refer to [`/licenses/Corus_LICENSE`](./licenses/Corus_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[tqdm](https://github.com/tqdm/tqdm)**: A fast, extensible progress bar library. (License: MIT License).
  - **License and Copyright**: Refer to [`/licenses/tqdm_LICENSE`](./licenses/tqdm_LICENSE)
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

- **[Pymorphy2](https://github.com/pymorphy2/pymorphy2)**: Morphological analyzer and generator for the Russian language. (License: MIT License).
  - **License and Copyright**: Refer to [`/licenses/Pymorphy2_LICENSE`](./licenses/Pymorphy2_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[BigARTM](https://github.com/bigartm/bigartm)**: Fast topic modeling platform. (License: License: BSD 3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/BigARTM_LICENSE`](./licenses/BigARTM_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[pyLDAvis](https://github.com/bmabey/pyLDAvis)**: Python library for interactive topic model visualization. (License: BSD 3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/pyLDAvis_LICENSE`](./licenses/pyLDAvis_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Jupyter Notebook](https://github.com/jupyter/notebook)**: Open-source web application to help build and share code. (License: Modified BSD License).
  - **License and Copyright**: Refer to [`/licenses/Jupyter_LICENSE`](./licenses/Jupyter_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Python 3.10](https://www.python.org/downloads/release/python-3100/)**: The programming language used for this project.

Please refer to the [`licenses`](./licenses) directory for the complete license files of these dependencies.
