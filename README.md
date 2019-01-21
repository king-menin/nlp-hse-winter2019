# nlp-hse-winter2019
Практический курс в рамках программы "Text Mining" специализации "Современный анализ данных, глубокое обучение и приложения". Читается в Высшей Школе Экономики, https://cs.hse.ru/dpo/datapp#pagetop

Емельянов Антон

email: login-const@mail.ru

telegram: @king_menin

|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (21 января)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ. Sequence labeling  | Регулярные выражения, лемматизация, POS-тэггинг, морфологический анализ. | Генерация текста по шаблону. Извлечение телефонных номеров из текста.   
| занятие 2 (26 января)  | Вектора слов. Дистрибутивная семантика  | Вектора слов. Близость документов. | Диалог с поэтом   
| занятие 3 (29 января)  | Тематическое моделирование  | Применение тематического моделирования и визуализация коллекций. Классификация, fasttext.| Тематический анализ коллекции
| занятие 4 (2 февраля)  | Нейронные сети. | Классификация текстов с помощью нейронных сетей. | Извлечение именованных сущностей.
| занятие 5 (5 февраля)  | Языковые модели. | Языковые модели для классификации и генерации | Применение Elmo на imdb
| занятие 6 (9 февраля)  | Seq2Seq and attention. | Attention на tensorflow для NMT  | coming soon


## 13 декабря

Данные к занятию лежат в папке: [git:lecture 1. intro to nlp](lecture%201.%20intro%20to%20nlp)

[Лекция 1. Часть 1. Введение](lecture%201.%20intro%20to%20nlp/lecture%201.%20part%201.%20intro.pdf), [Лекция 1. Часть 2. Морфологический анализ](lecture%201.%20intro%20to%20nlp/lecture%201.%20part%202.%20morphology.pdf), [ноутбук с семинара](lecture%201.%20intro%20to%20nlp/sem1.ipynb)/[colab](https://drive.google.com/file/d/1NqFCXkCoD1b-RFkNX0EoX-hS-4qOtcB4/view?usp=sharing), [домашнее задание](hw1.ipynb).

Необходимые библиотеки Python описаны в начале [ноутбука с семинара](lecture%201.%20intro%20to%20nlp/sem1.ipynb).


## 18 декабря

Данные к занятию: в [папке](lecture%202.%20word%20vectors/), предобученная модель [тут](https://www.dropbox.com/s/0x7oxso6x93efzj/ru.tar.gz?dl=1)

[Лекция 2. Вектора слов](lecture%202.%20word%20vectors/word%20vectors.pdf), [ноутбук с семинара](lecture%202.%20word%20vectors/word_vectors.ipynb)/[colab](https://colab.research.google.com/drive/1BQ6urKFDc4N3SK_BEhDbLLskdLQT1n-O), [домашнее задание](hw2.ipynb).


## 20 декабря

Данные к занятию в [папке](lecture%203.%20topic%20modeling%20and%20classification) и на [google диске](https://drive.google.com/file/d/19e2fOFpykP4iWCCCxzlJraAilvnVb1m9/view)

[Лекция 3. Тематическое моделирование](lecture%203.%20topic%20modeling%20and%20classification/topic%20modeling.pdf), ноутбуки семинара - тематическое моделирование: [git](lecture%203.%20topic%20modeling%20and%20classification/topic_modeling.ipynb); [colab](https://colab.research.google.com/drive/18QKAqSRyHxueej6XBSNLcEgY9Fr7_kAO), fasttext классификация [git](lecture%203.%20topic%20modeling%20and%20classification/classification.ipynb); [colab](https://colab.research.google.com/drive/1I9qBSkgILoLl0fLtm7Mqrl6L3xBv3IOr) [домашнее задание](hw3.ipynb).

Необходимые библиотеки Python:
* nltk; после установки nltk необходимо из командной строки Python3 вызвать команды
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```
* pymorphy2
* matplotlib
* pandas
* sklearn
* pymystem3
* python-rake
* wordcloud
* gensim
* pyLDAvis
* fasttext (не путайте с fastText)


## 25 декабря

Данные к занятию лежат в папке: [ru.vec](https://www.dropbox.com/s/0x7oxso6x93efzj/ru.tar.gz), [articles_lemmatized_noSW.csv](https://www.dropbox.com/sh/513tgmhz2ollna5/AAB6W-J3zwKDxKHSUnhjaYINa?dl=0&preview=articles_lemmatized_noSW.csv)

[Лекция 4. Нейронные сети в анализе текстов.](lecture%204.%20neural%20networks%20in%20nlp/neural%20networks%20in%20nlp.pdf),  практика [git](lecture%204.%20neural%20networks%20in%20nlp/RU_FNN_CNN_and_RNN.ipynb); [colab](https://colab.research.google.com/drive/1_CiD5xTMSxXSLdxD3b89pl1jmysc0pet), [домашнее задание](hw4.ipynb)




## Рекомендуемые ресурсы
### На английском

* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [Курс nlp в яндексе](https://github.com/yandexdataschool/nlp_course)
* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)



## Литература

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.