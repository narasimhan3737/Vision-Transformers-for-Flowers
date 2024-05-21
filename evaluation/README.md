## Evaluation

### k-NN evaluation

K-NN ImageNet evaluation on Flowers 102 dataset.

# KNN Classifier Results

| Model   |            | 10-NN        | 20-NN        | 100-N       | 200-N       |
|---------|------------|--------------|--------------|-------------|-------------|
| dino    | Top 1      | 69.80440098  | 70.17114914  | 68.58190709 | 68.21515892 |
|         | Top 5      | 85.69682152  | 88.38630807  | 88.87530562 | 88.87530562 |
| ibot    | Top 1      | 76.16136919  | 76.77261614  | 76.52811736 | 75.67237164 |
|         | Top 5      | 91.56479218  | 92.0537      | 92.78728606 | 92.42053    |
| attmask | Top 1      | 12.83618582  | 15.28117359  | 13.69193154 | 13.32518337 |
|         | Top 5      | 34.96332518  | 36.55256724  | 39.36430318 | 38.75305623 |

### Linear probing evaluation

Linear probing evaluation on Flowers-102 dataset.

# Linear Classifier Results

| Model   | Acc@1  | Acc@5   | Train Loss |
|---------|--------|---------|------------|
| dino    | 72.494 | 90.587  | 1.176      |
| ibot    | 78.729 | 93.765  | 0.917      |
| attmask | 74.817 | 91.565  | 1.078      |

## Run the Code

To execute the evaluation script, use the following command:

# dino
```bash
python main.py

# ibot
```bash
python main.py

# attmask
```bash
python main.py
