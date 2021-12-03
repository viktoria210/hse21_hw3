# hse21_hw3
Сравнение RNA-seq данных перепрограммированных и неперепрограммированных (контрольных) мышиных эмбриональных фибробластов (MEFs) и нахождение генов, которые наиболее сильно изменяют свою экспрессию в этом процессе.


## Ссылки на google colab ноутбуки

[python](https://colab.research.google.com/drive/1mrw_bp7FJ1vmOPdXt5bG8Dxe_JSfH8Ay?usp=sharing)

## Проверка качества чтений: сравнительная статистика из MultiQC

![multiqc_general_statistics](https://user-images.githubusercontent.com/60792064/144526184-3d8651ae-849e-4d85-8be2-ccced4273db5.png)

![fastqc_sequence_counts_plot](https://user-images.githubusercontent.com/60792064/144526266-a3520fe0-fba6-4266-8e87-f888a6dc3b7a.png)

![fastqc_per_base_sequence_quality_plot](https://user-images.githubusercontent.com/60792064/144526338-e2473f9f-32a6-4e68-9d63-2e1d3e8d4e5f.png)

![fastqc_per_sequence_quality_scores_plot](https://user-images.githubusercontent.com/60792064/144526371-2f37dfcd-d92b-4e0c-9ab5-f5502dfae8fe.png)

![per_base_sequence_content](https://user-images.githubusercontent.com/60792064/144526400-ef5aa05d-7a48-4dc6-a346-a495959c8ad5.png)

![fastqc_per_sequence_gc_content_plot](https://user-images.githubusercontent.com/60792064/144526441-a6ca0c76-5a0b-46f1-bc8a-66bc846f8476.png)

![fastqc_per_base_n_content_plot](https://user-images.githubusercontent.com/60792064/144526461-f4259c91-9cd7-4900-b914-a8056bc290cc.png)

![fastqc_sequence_duplication_levels_plot](https://user-images.githubusercontent.com/60792064/144526519-2d997172-08a1-43c0-a0b8-49c0298e41e1.png)

![fastqc_status_check_heatmap](https://user-images.githubusercontent.com/60792064/144526567-6fcfc0b5-1942-40fe-b6c8-04d27823db2b.png)

## Таблица со статистикой по каждому из 6-ти образцов

| ID образца | Тип образца |  Общее кол-во     | Кол-во и процент чтений,            |  Кол-во и процент уникально   |Общее кол-во чтений,   |
|            |             | исходных чтений   | которые были успешно                |  откартированных чтений       |которые попали на гены |                
| ID образца | Тип образца |  Общее кол-во исходных чтений   |Кол-во и процент чтений,которые были успешно откартированы на геном              |   Кол-во и процент уникально                откартированных чтений             |      Общее кол-во чтений,          которые попали на гены       |
|            |             |                   | (уникально)      |(не уникально)    |                               |                       |
|   :---:    |    :---:    |      :---:        |      :---:       |  :---:           |           :---:               |        :---:          |
| git status | git status  | git status        | git status       |                  | git status                    |                       |
| git diff   | git diff    | git diff          | git diff         |                  | git diff                      |                       |
