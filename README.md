# Анализ временных финансовых рядов

| Название файла/директории | Содержание файла |
|----:|:----------|
| Анализ временных финансовых рядов.ipynb | Ноутбук с реализацией проекта|
| df_raw_last.csv | Датафрейм с данными по акциям|
| complete_df.csv | Обработанный датафрейм, на основе которого проводится анализ|

## Описание 

Поиск интересных закономерностей во временных рядах.    
Используются характеристики дня: 'TRADEDATE', 'MONTH_NAME', 'DAY_NAME', 'WEEKEND', 'MONTH_END'. Котировки акций: 'GAZP', 'SBER', 'SBERP', 'LKOH', 'YNDX', 'GMKN', 'NVTK', 'TCSG', 'ROSN', 'POLY', 'PLZL', 'ALRS', 'MGNT', 'TATN', 'CHMF', 'NLMK', 'SNGS', 'FIVE', 'MTSS', 'MOEX', 'VTBR', 'SNGSP', 'MAIL', 'PIKK', 'IRAO', 'PHOR', 'MAGN', 'RUAL', 'AFKS', 'TRNFP', 'HYDR', 'RTKM', 'DSKY', 'AFLT', 'TATNP', 'POGR', 'CBOM', 'FEES', 'LSRG'. 
Проанализировав данные Мосбиржи о ценах закрытия акций после 2015 года, можно сказать, что:

1. В начале года в среднем акции падают в цене, а в конце года - дорожают;
2. Цены некоторых акций сильно зависят друг от друга. Так, сильнее всего зависимы цены акций Газпрома, Сбербанка России, Лукойла, Яндекса, Норильского никеля, Новатэка, Московского кредитного банка, также ВТБ и Магнита, Магнитогорского металлургического комбината и Северстали, Детского мира и Московской биржи, Магнита и "Татнефти" имени В.Д. Шашина.
3. Акции Сбербанка, Газпрома и Яндекса сильно коррелируют между собой.

## Документация

* [Документация по работе с Python](https://www.python.org/)
* [Документация по работе с библиотекой Numpy](https://numpy.org/doc/)
* [Документация по работе с библиотекой Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
* [Документация по работе с библиотекой Seaborn](https://seaborn.pydata.org/)
* [Документация по работе с библиотекой Math](https://docs.python.org/3/library/math.html)
* [Документация по работе с библиотекой Matplotlib](https://matplotlib.org/stable/index.html)

## Зависимости

Рабочие версии библиотек прописаны в файле "requirements.txt"

Для настройки необходимых пакетов python для скрипта введите в командной строке:

> pip install -r "requirements.txt"
 

## :shipit: Контакты
**Telegram** @niii_chel_angelo    
**ВКонтакте**[niii_popova](https://vk.com/niii_popova)    
**Email** PopovaNinaM@yandex.ru
