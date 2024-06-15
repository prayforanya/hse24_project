# hse24_project

## Entamoeba invadens

Простейшее, обитающее в пищеварительном тракте многих травоядных рептилий. 
Жизненный цикл энтамебы состоит из двух стадий: трофозоиты и неделящиеся многоядерные цисты.
Геном схож с геномом E.histolytica. Геном содержит много повторов и 50% сборки приходится на scaffold’ы. Предсказанные функции крупнейших семейств генов (протеинкиназы, фосфатазы,РНК-связывающие белки и др.) подчеркивают важность подвижности и передачи сигналов для выживания организма.  
Также E. invadens содержит представителей семейств генов, содержащие домен Myb, которые регулируются во время инвазии в толстую кишку и образования абсцесса печени. 
У E. invadens присутсвует связь между развитием цисты и ацетилированием гистона H4.

## Тетрадки
Определение квадруплексов: https://colab.research.google.com/drive/1JtLIcXimRo70PdOrP4234iTRwQmLroQz?usp=sharing <br>
ZHUNT : https://colab.research.google.com/drive/152Q7Rq6DZ6yF_TDfgUyigSUZ3aC2j0RF?usp=sharing <br>
ZDNABERT: https://colab.research.google.com/drive/1hcbODA_mzsm-B8YuZs_jYwsSZ7rygy9G?usp=sharing <br>
HMMer: https://colab.research.google.com/drive/1wwvElKoQRKy63RXTSntXW_1yxDihaMik?usp=sharing <br>


## Табличка
|Проверяемое семейство|Название гена|
|:------:|:--:|
|TUDOR |  EIN_405260 |
|Chromo | EIN_094130 | 
|WD40  | EIN_047780 |
|zf-rbx1 | EIN_377170 |
|CPSF_A |EIN_430670 |
|Cullin | EIN_495430|
|PHD | EIN_428060|
|DnaJ | EIN_052270 |
|Acetyltransf_1| EIN_095120|
|Pkinase | EIN_175500|
|HAT | crooked neck protein|


## Табличка
|Участок|Число квадруплексов|Доля квадруплексов|Число предсказаний Zhun|Доля предсказаний Zhun|Число предсказаний ZDNABERT|Доля предсказаний ZDNABERT|
|:------:|:--:|:--:|:--:|:--:|:--:|:--:|
|Exons | 19 | 19.58% | 12498 | 75.35% | 489 | 88.9% |
|Introns | 0 | 0.00% | 113 | 0.7% | 1 | 0.18% |
|Promoters (1000 up from TSS) | 13 | 13.4% | 4460 | 26.89% | 153 | 27.8% |
|Downstream (200 bp) | 0 | 0.00% | 660 | 3.97% | 16 | 2.9% | 
|Intergenic | 78 | 80.41% | 4146 | 24.99% | 53 | 9.63% |

Результаты с количеством участков, попавших в промотеры больше чем в межгенное. Такое может быть, если расстояние между генами меньше 1000bp, то есть не совсем корректно рассматривать такое окно для Upstream.
Также структуры предсказанные z-hunt и z-dnabert в основном попадают в экзоны, поэтому можно сделать вывод о том, что они влияют на транскрипцию.  
