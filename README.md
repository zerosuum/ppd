# Praktikum Penambangan Data

Repository ini digunakan untuk menyimpan dataset dan berkas pendukung Praktikum Penambangan Data.

## Dataset

### CC GENERAL

Dataset `CC GENERAL.csv` digunakan pada Praktikum Pertemuan 6.

- **Dataset:** CC GENERAL
- **Jumlah data:** 8.950 baris
- **Jumlah fitur:** 18 kolom
- **Sumber asli:** [Credit Card Dataset for Clustering - Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)
- **File repository:** [`datasets/CC GENERAL.csv`](datasets/CC%20GENERAL.csv)
- **Raw dataset:** [CC GENERAL.csv](https://raw.githubusercontent.com/zerosuum/ppd-praktikum/main/datasets/CC%20GENERAL.csv)

Dataset pada repository ini disimpan untuk mendukung proses praktikum dan memungkinkan data diakses langsung dari notebook menggunakan raw URL GitHub.

## Struktur Repository

```text
ppd-praktikum/
├── datasets/
│   └── CC GENERAL.csv
└── README.md
```

## Penggunaan

Dataset dapat dibaca langsung menggunakan pandas:

```python
import pandas as pd

url = "https://raw.githubusercontent.com/zerosuum/ppd-praktikum/main/datasets/CC%20GENERAL.csv"
df = pd.read_csv(url)

df.head()
```