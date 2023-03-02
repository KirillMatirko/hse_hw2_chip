## hse_hw2_chip

Ссылка на колаб: https://colab.research.google.com/drive/1IeNfboSjSjuAnO4kJHw-NHtT5wmqkB9-?usp=sharing

### 1. Отчёты FASTQC

#### Первая реплика ENCFF751QVC (не пришлось подрезать).

![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF751QVC_basic_stat.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF751QVC_per_base_seq_quality.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF751QVC_per_base_seq_content.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF751QVC_per_seq_gc_content.png)

#### Вторая реплика ENCFF087XFX. Пришлось подрезать, потому что нехороший Per Base Sequaence Score (первая картинка). Подрезал как в примере из колаба.

![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF087XFX_per_base_seq_quality.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF087XFX_trimmed_basic_stat.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF087XFX_trimmed_per_base_seq_quality.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF087XFX_trimmed_per_base_seq_content.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF087XFX_trimmed_per_seq_gc_content.png)

#### Контроль ENCFF902MPL (не пришлось подрезать).

![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF902MPL_basic_stat.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF902MPL_per_base_seq_quality.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF902MPL_per_base_seq_content.png)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/pics/ENCFF902MPL_per_seq_gc_content.png)


### 2. Таблица со статистикой (выравнивание на 14 хромосому)

| Образец | Общее число чтений | Кол-во и процент выровненных чтений (уникально или нет) | Кол-во и процент уникально выровненных чтений | Кол-во и процент невыровненных чтений |
|:----------:|:-------:|:----------------:|:----------------:|:----------------:|
| ENCFF751QVC | 39913402 | 4143396 (10.38%) | 1651123 (4.14%) | 34118883 (85.48%) |
| ENCFF087XFX_trimmed | 37402268 | 3330025 (8.90%) | 1501553 (4.01%) | 32570690 (87.08%) |
| ENCFF902MPL | 38682658 | 5290786 (13.68%) | 1719623 (4.45%) | 31672249 (81.88%) |

### 3. Диаграммы Венна

![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/data/ENCFF751QVC_venn1.pdf)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/data/ENCFF751QVC_venn2.pdf)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/data/ENCFF087XFX_trimmed_venn1.pdf)
![](https://github.com/KirillMatirko/hse_hw2_chip/blob/main/data/ENCFF087XFX_trimmed_venn2.pdf)

