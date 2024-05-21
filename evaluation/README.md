# Evaluation of Vision Transformer models

## k-NN evaluation

Evaluation of Flowers 102 dataset using K-NN classification on the frozen features.

### KNN Classifier Results

| Model   |            | 10-NN        | 20-NN        | 100-N       | 200-N       |
|---------|------------|--------------|--------------|-------------|-------------|
| dino    | Top 1      | 69.8044  | 70.1711  | 68.5819 | 68.2151 |
|         | Top 5      | 85.6968  | 88.3863  | 88.8753| 88.8753|
| ibot    | Top 1      | 76.1613  | 76.7726  | 76.5281 | 75.6723 |
|         | Top 5      | 91.5647  | 92.0537      | 92.7872 | 92.4205    |
| attmask | Top 1      | 74.0831 | 74.2053 |	72.1271 |	71.6381 |
|         | Top 5      | 88.6308 |	90.4645 | 91.1980 |	90.8312 |

## Linear probing evaluation

Linear probing evaluation on Flowers-102 dataset through a supervised linear classifier on the frozen weights.

### Linear Classifier Results

| Model   | Acc@1  | Acc@5   | Train Loss |
|---------|--------|---------|------------|
| dino    | 72.494 | 90.587  | 1.176      |
| ibot    | 78.729 | 93.765  | 0.917      |
| attmask | 74.817 | 91.565  | 1.078      |


