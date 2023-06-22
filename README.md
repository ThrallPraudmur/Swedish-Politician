## Определение политически-активных групп Швеции, их географии и политических симпатий
### Оглавление
1. Описание проекта
2. Краткая информация о данных
3. Этапы работы над проектом
4. Результаты и выводы

### 1. Описание проекта
Задачей проекта является определение портрета шведского политика и сегментирование политического поля Швеции. Результаты анализа потенциально позволят лучше подготовиться к следующему выборному циклу, определиться со стратегией по взаимодействию с разными слоями общества и выявить основные линии его разделения.

### 2. Краткая информация о данных
Данные берём с сайта Государственной избирательной комиссии Швеции, Valmyndigheten, WWW.VAL.SE </br> 
Необходимая информация выгружена в прилагаемый здесь файл kandidaturer.csv

### 3. Этапы работы над проектом
* Выделение признака Профессии методом feature engineering
* Определение основных зависимостей с помощью ХИ-теста
* Определение дополнительных корреляций путём проведения разведывательного анализа
* Определение оптимальной ML-модели кластеризации
* Анализ и интерпретация полученных результатов кластеризации

### 4. Результаты и выводы
* В рамках работы над проектом были оценены основные зависимости между признаками путём проведени ХИ-теста, а также выявляны дополнительные корреляции между признаками при дальнейшем исследовании
* Были опробованы различные алгоритмы понижения размерности
* Были протестированы и опробованы различные модели кластеризации, в конечном счёте был сделан выбор в пользу KMeans. Было оценено и определено оптимально количество кластеров, семь
* Полученные кластеры были проанализированы, а партии получили соответствующие рекомендации. Было признано большое влияние внешних событий. Их жёсткая трактовка и доминирование мужчин в шведской политике позвляет чрезвычайно быстро  позволяет популистам попадать в Парламент напрямую, минуя привычные механизмы работы демократии. В первую очередь изменить свою стратегию следует Зелёной партии и Левой партии, которых ранее потенциально устраивал свой кусок пирога при уверенной победе социал-демократов на выборах. Но эти времена уже прошли. 
* Были определены потенциально колеблющиеся страты общества, среди которых, в первую очередь, в глаза бросаются студенты, преимущественно медицинских факультетов. Город Лунд можно считать своеобразным "осиным гнездом" нового правого Правительства, в зависимости от симпатий. Другими активными политическими игроками оказались пенсионеры и инженеры.
