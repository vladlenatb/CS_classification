# CS_classification
Solution - cs_classification_end.ipynb

Start in GoogleColab or delete mounting with GoogleDrive in cs_classification_end.ipynb

Основные моменты решения: 

Тестовая выборка из train.csv увеличина в 2 раза, отзеркаливанием положений команд (первая,вторая) и who_won

Показатели игроков kill_death_difference подсчитаны где был 0, но была информация по смертям и убийствам

Показатели игроков преобразованы в агрегированные командные, нормализованы

Показатели команды kill_death и kill_round отброшены

Найдены оптимальные значения классификаторов на кросс-валидации


  Файлы prediction_1.csv, prediction_2.csv, prediction_3.csv - ПРОГНОЗЫ ДЛЯ test.csv
