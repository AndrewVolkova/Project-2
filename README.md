# Проект 2. Анализ вакансий из сайта HeadHunter (Postgre, Plotly)

***
<b>Лирическое отступление, требующее быть озвучено сразу, а не где-то затеряно в тексте</b><br>
:cry:
```diff
- GitHub не позволяет увидеть сгенереные библиотекой plotly графики в Yupiter Notebook
```
:innocent: Но можно воспользоваться следующей ссылкой,  и утонуть в интеракивности подсказок прямо с браузера

[Просмотр Notebook с графиками](https://nbviewer.org/github/AndrewVolkova/Project-2/blob/e61fa952d10433ace45a3e1d94065c0621ee8de6/Project_2_Andrew_Volkov_DSPR_120.ipynb)

или скачать NoteBook локально к себе

***

## Оглавление  
[1. Описание проекта](https://github.com/AndrewVolkova/project-2/blob/master/README.md#Описание-проекта)  
[2. Решаемая задача?](https://github.com/AndrewVolkova/project-2/blob/master/README.md#Решаемая-задача)  
[3. Информация о данных](https://github.com/AndrewVolkova/project-2/blob/master/README.md#Информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/AndrewVolkova/project-2/blob/master/README.md#Этапы-работы-над-проектом)  
[5. Результаты и выводы](https://github.com/AndrewVolkova/project-2/blob/master/README.md#Результаты-и-выводы)    


### Описание проекта

Проект, относящийся к зачетному проекту под названием <b>"PROJECT-2. Анализ вакансий из HeadHunter"</b> блока 2-го. Подгрузка данных. <br>
Учебная платформа SkillFactory, Профессия Data Science.<br>

Задача проекта показать знания в следующих областях:
  * знакомство с данными,
  * предварительный анализ структуры данных,
  * анализ вакансий,
  * анализ работадателей,
  * предметнный анализ,
  
  <b>используя только:</b>

    * получение необходимых данных только посредством SQL (в нашем случае postgre)
    * Jupyter Notebook
    * Библиотеки для построения графиков на выбор (seaborn, matplotlib, plotly) 

 ### Решаемая задача

Представляем, что я устроился на работу в кадровое агентство, которое подбирает вакансии для IT-специалистов. Мой первый проект — создание модели машинного обучения, которая будет рекомендовать вакансии клиентам агентства, претендующим на позицию Data Scientist. Сначала мне необходимо понять, что из себя представляют данные и насколько они соответствуют целям проекта. В литературе эта часть работы над ML-проектом называется Data Understanding, или анализ данных.


[К оглавлению](#оглавление)

### Информация о данных

#### Структура базы данных

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/db_scheme.png alt="структура БД" style="width:748px;">

##### Таблица Vacancies

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/table_vacancies.png alt="таблица Вакансий" style="width:1165px;">


##### Таблица Areas

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/table_areas.png alt="таблица Регионов" style="width:1166px;">

##### Таблица Employers

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/table_employers.png alt="таблица Работодателей" style="width:1165px;">


##### Таблица Industries

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/table_industries.png alt="таблица Индустрий" style="width:1166px;">

##### Таблица Employers_Industries

<img src = https://github.com/AndrewVolkova/Project-2/blob/60cd17a5464dff159bea4be27dd3d0b61b072da2/db_structure/table_employers_industries.png alt="таблица Работадатель <> Индустрия" style="width:1167px;">

[К оглавлению](#оглавление)

### Этапы работы над проектом

1. Исследование структуры данных
2. Анализ вакансий, работодателей, предметный анализ
3. Дополнительный анализ (генерация графиков)
4. Финальное оформление проекта на GitHub

[К оглавлению](#оглавление)

### Результаты и выводы
* Все поставленные задачи выполнены с соблюдением всех поставленных условий
* Выводы подробно в комментариях в Notebooк после каждого раздела

[К оглавлению](#оглавление)