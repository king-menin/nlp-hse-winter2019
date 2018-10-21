# nlp-hse-autumn2018
Практический курс в рамках программы "Text Mining" специализации "Современный анализ данных, глубокое обучение и приложения". Читается в Высшей Школе Экономики, https://cs.hse.ru/dpo/datapp#pagetop

Емельянов Антон

email: login-const@mail.ru

telegram: @king_menin

|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (27 октября)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ. Sequence labeling  | Регулярные выражения, лемматизация, POS-тэггинг, морфологический анализ. | Генерация текста по шаблону. Извлечение телефонных номеров из текста.   


## 27 октября

Данные к занятию лежат в папке: [git:sem1](https://github.com/king-menin/nlp-course/tree/master/sem%201)

[Лекция 1. Часть 1. Введение](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/lecture%201.%20part%201.%20intro.pdf), [Лекция 1. Часть 2. Морфологический анализ](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/lecture%201.%20part%202.%20morphology.pdf), [ноутбук с семинара](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/sem1.ipynb), [домашнее задание](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/hw1.ipynb).


#### Необходимые библиотеки для занятия    
Обычно <b>ставятся автоматически</b> при установке jupyter notebook:
<ul>
<li><i>numpy</i> - для работы с массивами

```!pip3 install numpy```
</li>
<li><i>sklearn</i> - блиблиотека для работы с данными, содержит большинство алгоритмов машинного обучения</li>

```!pip3 install sklearn```

</li>
<li><i>pandas</i> - библиотека для удобной работы с данными как с DataFrame

```!pip3 install pandas```
</li>
<li><i>matplotlib</i> - библиотека для визуализации

```!pip3 install matplotlib```
</li>
</ul>

Обычно <b>не ставятся автоматически</b> при установке jupyter notebook:
<ul>
<li><i>rusenttokenize</i> - для разбиения текста на предложения (русский язык)

```!pip3 install rusenttokenize```
</li>
<li><i>nltk</i> - фреймворк для обработки ЕЯ

```!pip3 install nltk```

Также необходимо выполнить следующие команды, чтобы загрузить данные:

```import nltk```

```nltk.download('treebank')```

```nltk.download('stopwords')```

```nltk.download('punkt')```

<li><i>python-crfsuite</i> - для использования CRF</li>

```!pip3 install python-crfsuite```
</li>
<li><i>pymorphy2</i> - морфологический анализатор русского языка

```!pip3 install pymorphy2```
</li>
</ul>



## Рекомендуемые ресурсы
### На английском

* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

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