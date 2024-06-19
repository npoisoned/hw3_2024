# hw4_2024
https://colab.research.google.com/drive/15GtHd18KNOgDzQyBCi2c3F3W0IA-ryxM?usp=sharing
### Таблица гистоновых меток и соответствующих файлов

| Гистоновая метка | Имя файла         |
|------------------|-------------------|
| H2az             | K562_H2az.bam     |
| H3k27ac          | K562_H3k27ac.bam  |
| H3k27me3         | K562_H3k27me3.bam |
| H3k36me3         | K562_H3k36me3.bam |
| H3k4me1          | K562_H3k4me1.bam  |
| H3k4me2          | K562_H3k4me2.bam  |
| H3k4me3          | K562_H3k4me3.bam  |
| H3k79me2         | K562_H3k79me2.bam |
| H3k9ac           | K562_H3k9ac.bam   |
| H3k9me1          | K562_H3k9me1.bam  |

### Картинки из выдачи ChromHMM

Emission
<img width="311" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/b9639e69-979d-43e3-af92-7670c682110d">

Overlap
<img width="359" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/d9a8659e-7b10-4312-b172-652a164f5b45">

Transition
<img width="340" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/7864aa9a-4499-4e2c-a8cc-cef40066a9e2">

RefSeqTSS
<img width="518" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/19aabcb0-ba82-4fbd-a1c7-ef6fe9c6e256">

RefSeqTES
<img width="523" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/c4ec5cae-150e-4ba7-9bac-f6e4cfa02502">


### Скриншоты из UCSC Genome Browser
<img width="896" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/c1f20860-f61f-4a77-91ba-a87baded4578">
<img width="894" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/64347ddd-84cb-4834-b2a5-dc4b30e76bac">
### Таблица с названиями эпигенетических типов

| Номер эпигенетического типа | Присвоенное название | Характерная метка | Другие свойства                                                                      |
|-----------------------------|----------------------|-------------------|--------------------------------------------------------------------------------------|
| 1                           | Transcribed          | H3K36me3, H3K27ac | Попадает на гены. Слабый сигнал                                                      |
| 2                           | Heterochromatin      | -                 | Самый частовстречающийся тип в геноме.  Нет  четкой корреляции с определенной меткой |
| 3                           | Transcriptional      | H3K36m3           | Попадает на ген, сильный сигнал                                                      |
| 4                           | Transcriptional      | H3K79m2           | Сильный сигнал                                                                       |
| 5                           | Promoter             | H3K27ac, H3K4m*   | Сильный сигнал                                                                       |
| 6                           | Repressed            | -                 | Слабый сигнал                                                                        |
| 7                           | Enchancer            | H3K4m*, H2AFZ     | Сильный сигнал                                                                       |
| 8                           | Enchancer            | H2AFZ             | Может как попадать, так и не попадать на ген. Сигнал сильный                         |
| 9                           | Promoter             | H3K4m*            | В начале генов. Сигнал средний                                                       |
| 10                          | Enchancer            | Почти все         | Сильный сигнал                                                                       |

### Результат бонусного задания
<img width="999" alt="image" src="https://github.com/npoisoned/hw4_2024/assets/90446751/766ecd95-8610-456d-8541-9d9661b06fb0">
