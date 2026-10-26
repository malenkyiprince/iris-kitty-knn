# ୨୧ ─── iris kitty knn ─── ୨୧

```text
       /\_/\
      (｡•ᴗ•｡) ♡
       > 🎀 <
```

♡ knn на iris. квіточки пораховано.

## ♡ що тут

- knn із 5 сусідами.
- accuracy, tp, fp, fn, tn.
- precision, recall та f1 для кожного класу.

метрики — вручну, без `sklearn.metrics`.

## ♡ запуск

1. встанови бібліотеки:

```bash
python -m pip install -r requirements.txt
```

2. відкрий ноутбук:

```bash
jupyter notebook iris_knn.ipynb
```

3. натисни **Run All**.

## ♡ результат

30 із 30 правильних прогнозів. accuracy = 1.0.

| клас | tp | fp | fn | tn | precision | recall | f1 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| setosa | 10 | 0 | 0 | 20 | 1.0 | 1.0 | 1.0 |
| versicolor | 9 | 0 | 0 | 21 | 1.0 | 1.0 | 1.0 |
| virginica | 11 | 0 | 0 | 19 | 1.0 | 1.0 | 1.0 |

це результат на 30 тестових квітках: `test_size=0.2`, `random_state=42`.

୨୧ ─── квіточки можуть відпочити ♡ ─── ୨୧
