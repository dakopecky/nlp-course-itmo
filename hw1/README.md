## ITMO University Deep Learning and NLP course homework repository
### Author: Daniel Kopecky (282306)

## LAB#1
### [Google Colab notebook](https://colab.research.google.com/drive/1CMqZEMt3Q4N23joDoTEdi5qKXEKkDaX9?usp=sharing)
### Задание 1 - 10 баллов

- Загрузить набор данных по выбору с помощью библиотеки Corus - **1 балл**
- Провести релевантную предобработку выбранного датасета: - **6 баллов**
  - Нормализация
  - Токенизация
  - Удаление стоп-слов
  - Лемматизация/стемминг

- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/) - **1 балл**

Инструменты для решения задач предобработки – NLTK, Gensim, Natasha, pymystem, pymorphy2…

Для сдачи ДЗ - приложите ссылку на PR (Pull Request) из ветки hw_1 в ветку main в вашем приватном репозитории на github.com

## Dependencies and Licenses

This project makes use of the following libraries:

- **NLTK**: Natural Language Toolkit for natural language processing. (License: Apache License 2.0).
    - **License and Copyright**: Refer to `/licenses/NLTK_LICENSE.txt`
    - **State of Changes**: No changes were made to the original code.

- **preprocessor**: A Python library for preprocessing text data. (License: GNU GPL v3).
    - **License and Copyright**: Refer to `/licenses/preprocessor_LICENSE.md`
    - **State of Changes**: No changes were made to the original code.

- **Corus**: A collection of Russian NLP datasets. (License: MIT License).
    - **License and Copyright**: Refer to `/licenses/Corus_LICENSE.txt`
    - **State of Changes**: No changes were made to the original code.

- **Pymorphy2**: Morphological analyzer and generator for the Russian language. (License: MIT License).
    - **License and Copyright**: Refer to `/licenses/Pymorphy2_LICENSE.txt`
    - **State of Changes**: No changes were made to the original code.

- **Jupyter Notebook**: Open-source web application to help build and share code. (License: BSD License).
  - **License and Copyright**: Refer to `/licenses/Jupyter_LICENSE.txt`
  - **State of Changes**: No changes were made to the original code.

- **Python 3.10**: The programming language used for this project.

Please refer to the `licenses` directory for the complete license files of these dependencies.
