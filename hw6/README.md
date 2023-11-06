## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#6
### [Google Colab notebook](https://colab.research.google.com/drive/1LrzGyg3M9DA_liZqHuTeK-Zl5Hgwl7Wk?usp=sharing)
### Задание 6 - 10 баллов

- Изучить [главу 3. Fine-tuning a pretrained model туториалов HuggingFace](https://huggingface.co/learn/nlp-course/chapter3/1)
- Выбрать модель архитектуры BERT/GPT в HuggingFace hub для решения задач Text Classification / Text Generation
- Выбрать набор данных для конкретной задачи из HuggingFace Datasets
- Дообучить выбранную модель - **5 баллов**
- Сравнить качество до и после дообучения с учетом метрик, специфичных для выбранной задачи - **2 балла**
- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**

## Dependencies and Licenses

This project makes use of the following libraries:

- **[Pandas](https://github.com/pandas-dev/pandas)**: Data manipulation and analysis library. (License: BSD-3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/Pandas_LICENSE`](./licenses/Pandas_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**: Machine learning library featuring various algorithms, tools for working with data. (License: BSD License).
  - **License and Copyright**: Refer to [`/licenses/scikit-learn_LICENSE`](./licenses/scikit-learn_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[NumPy](https://github.com/numpy/numpy)**: Library for numerical computations. (License: BSD-3-Clause License).
  - **License and Copyright**: Refer to [`/licenses/NumPy_LICENSE`](./licenses/NumPy_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[datasets](https://github.com/huggingface/datasets)**: A library for easily loading and sharing datasets for machine learning tasks. (License: Apache License 2.0).
  - **License and Copyright**: Refer to [`/licenses/datasets_LICENSE`](./licenses/datasets_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[transformers](https://github.com/huggingface/transformers)**: A library for natural language understanding (NLU) and natural language generation (NLG) with state-of-the-art models. (License: Apache License 2.0).
  - **License and Copyright**: Refer to [`/licenses/transformers_LICENSE`](./licenses/transformers_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[accelerate](https://github.com/huggingface/accelerate)**: A library for easy distributed training and inference in PyTorch. (License: Apache License 2.0).
  - **License and Copyright**: Refer to [`/licenses/accelerate_LICENSE`](./licenses/accelerate_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Jupyter Notebook](https://github.com/jupyter/notebook)**: Open-source web application to help build and share code. (License: Modified BSD License).
  - **License and Copyright**: Refer to [`/licenses/Jupyter_LICENSE`](./licenses/Jupyter_LICENSE)
  - **State of Changes**: No changes were made to the original code.

- **[Python 3.10](https://www.python.org/downloads/release/python-3100/)**: The programming language used for this project.

Please refer to the [`licenses`](./licenses) directory for the complete license files of these dependencies.
