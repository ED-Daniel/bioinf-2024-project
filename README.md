# Отчет о Entamoeba Nuttalli
Итоговый групповой проект по биоинформатике по исслодования амеб (моя Entamoeba nutalli)

## Entamoeba Nuttalli
Entamoeba nuttalli — это вид паразитической амебы, близкий родственный Entamoeba histolytica, паразитирующий у приматов и вызывающий схожие кишечные заболевания. <br>

Длина генома Entamoeba nuttalli составляет около 20 миллионов пар оснований, что помогает исследовать механизмы патогенности и адаптации к паразитическому образу жизни. <br>

У Entamoeba nuttalli обнаружены эпигенетические модификации, такие как ацетилирование и метилирование гистонов, важные для регуляции генетической активности. <br>

Модификации ДНК, включающие метилирование цитозина, и ферменты, ответственные за это, помогают регулировать генетическую активность амебы в ответ на изменения в окружающей среде. <br>

У Entamoeba nuttalli присутствуют гистоны H3, H4, H2A и H2B с уникальными последовательностями, специфичными для рода Entamoeba.


## Отчетные файлы
- Файл генома в папке [genome](./genome/)
- 3 файла находятся в папке [report](./report/)
- В [common](./common/) находятся файлы для общей части проекта

## Тетрадки
Определение квадруплексов: https://colab.research.google.com/drive/1gF63XPlJnFlIhVMfIwNvNo3IvJml5XeT?usp=sharing <br>
ZDNABERT: https://colab.research.google.com/drive/1lBE1pLN4O4cCwmP8jhUu_tVp3vtupNKL?usp=sharing <br>
HMMer: https://colab.research.google.com/drive/1B0AqfnmUHM3_kubN7z9DZljReB7Z7BAc?usp=sharing <br>

## Таблички
|Проверяемое семейство|Название гена|
|:-----------:|:----:|
|Pkinase|ENU1_062640|
|DnaJ|ENU1_148830|
|Acetyltransf_1|ENU1_174980|
|Chromo|ENU1_101900|
|PHD|ENU1_018820|
|TUDOR|ENU1_128240|
|Cullin|ENU1_005600|
|PF00856|ENU1_084960|
|PF02373|-|
|Kelch_1|ENU1_082730|


|Участок|Число квадруплексов|Доля квадруплексов|Число предсказаний Zhun|Доля предсказаний Zhun|Число предсказаний ZDNABERT|Доля предсказаний ZDNABERT|
|:------:|:--:|:--:|:--:|:--:|:--:|:--:|
|Exons | 0 | 0.00% | 227 | 61.18% | 0 | 0.00% |
|Introns | 0 | 0.00% | 1 | 0.27% | 0 | 0.00% |
|Promoters (1000 up from TSS) | 0 | 0.00% | 78 | 21.02% | 0 | 0.00% |
|Downstream (200 bp) | 0 | 0.00% | 9 | 2.43% | 0 | 0.00% | 
|Intergenic | 0 | 0.00% | 144 | 38.81% | 8 | 100.00% |

### Пометка
У меня не нашлось квадруплексов по регулярке, поэтому файл quadr.bed пустой и данных о числе квадрупелксов нет
