  Кластеризация клиентов фешн-ритейлера
</h1>  
  
 
### 🛠️ Стек технологий:
<div id="tools", align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="Pandas" alt="Pandas" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="NumPy" alt="NumPy" height="40"/>&nbsp;
  <img src="https://seaborn.pydata.org/_images/logo-tall-lightbg.svg" title="Seaborn" alt="Seaborn" width="40" height="40"/>&nbsp;
  <img src="https://quintagroup.com/cms/python/images/scikit-learn-logo.png" title="Scikit learn" alt="Scikit learn" height="40"/>&nbsp;
</div>

## Содержание
- 🔌 [Описание данных]
- 🐥 [EDA]
- 🔨 [Предобработка данных]
- 😻 [Обучение модели]
- 📄 [Кластеризация клиентов]
- 📄 [Оцентка перетока клиентов]

- ❗️ [Заключение]

## Задача

Провести кластеризацию клиентов, для оценки состояния базы. Описать полученные кластеры, в чем их особенность, выделить кластер “топовых” клиентов, объяснить его “топовость”.

## Описание данных

- Данные о клиентах, собранные с начала 2021 по конец 2022 года с периодом в 2 месяца.

## EDA

- Пропусков и дубликатов в данных не обнаружено.

## Обработка данных

- Масштабирование численных признаков
- Выделение данных за последний отчетный период
  
## Обучение-модели

- Обучена модель K-means
- выделено 6 кластеров
- Выделены и описаны топовые клиенты.

## Проведена кластеризация клиентов по последнему и предпоследнему отчетномсу периодам

- Определены клиенты в оттоке и пред-оттоке
  
## Заключение

 <b>⚡ Ответы на поставленные в задаче вопросы:</b>
    <ul>
<li> на Декабрь 2022 в оттоке 28854 клиентов
<li> в пред-оттоке 115949
<li> 1625 топовых клиентов на последний отчетный период в среднем 
    <br> за прошедший год тратили около 235 тысяч,
    <br> за прошедний год разместили 11,5 заказов из 24 позиций 
    <br> за прошедший год возвращяли 1.4(13%) заказа, 
    <br> 36% топовых пользователей заказывают товары для обоих полов
    <br> <b>Пользуются сервисом 20 месяцев </b>
    <br> В первый период купили в 8,3 позиции
    <br> Последнюю покупку совершали 110 дней назад
<li> Большинство клиентов не сменило категории. Самый большой переток произошел из средних в малые клиенты.    
<li> Новых клиентов 14364
