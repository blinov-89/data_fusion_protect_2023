# data_fusion_protect_2023
Data Fusion Contest 2023 — Task 2 Защита


## [Data Fusion Contest 2023](https://ods.ai/tracks/data-fusion-2023-competitions)

[Задача Защита](https://ods.ai/tracks/data-fusion-2023-competitions/competitions/data-fusion2023-defence)

В задаче Защита — нужно научиться защищать свои модели от заранее оговоренного вида атак.

![image](https://user-images.githubusercontent.com/61515881/221497419-3a764ef3-2e41-4161-af00-50f07b900d62.png)

Решение на задачу защита, его нужно отправлять в формате .zip, который состоит из 4 файлов:

– metadata.json – какой образ взять и как запустить скрипт 

– model.py – скрипт, который сделает предикт. На вход имя .csv файла для предикта и имя выходного .csv файла с результатом работы 

– nn_bins.pickle nn_weights.ckpt – файлы, необходимые для работы бейзлайна

Метрика соревнования — Mean Harm ROC-AUC. Это среднее гармоническое ROC-AUC на исходных данных и на атакованных. Метрика сочетает в себе компромисс между повышением защищенности модели и потенциальным снижением ее качества. 

Mean Harm ROC-AUC: 0,710165
