# AI Labs
## Никулин Кристиан Ильич М8О-408Б-21

Лабораторные работы 6-8 по курсу "Методы, средства и технологии мультимедиа"

## Датасеты

- The Oxford-IIIT Pet Dataset - https://www.kaggle.com/datasets/tanlikesmath/the-oxfordiiit-pet-dataset/data

## Подведение итогов / сравнение результатов

Таблица с результатами работы каждого алгоритма.

### Метрики:

- Pixel Accuracy
- Mean IoU

## Результаты

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">Сверточные нейронные сети (CNN) - torchvision</td>
        <td>Классификация</td>
        <td>0.88</td>
        <td>0.90</td>
        <td>0.85</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.78</td>
        <td>0.81</td>
        <td>0.76</td>
    </tr>
    <tr>
        <td rowspan="2">UNet (segmentation_models.pytorch)</td>
        <td>Классификация</td>
        <td>0.92</td>
        <td>0.94</td>
        <td>0.88</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.7492 (UNet-ResNet34)</td>
        <td>0.7611 (UNet-ResNet34)</td>
        <td>0.80</td>
    </tr>
    <tr>
        <td rowspan="2">YOLO (Ultralytics)</td>
        <td>Классификация</td>
        <td>0.92</td>
        <td>0.95</td>
        <td>0.90</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.82</td>
        <td>0.85</td>
        <td>0.88</td>
    </tr>
</table>
