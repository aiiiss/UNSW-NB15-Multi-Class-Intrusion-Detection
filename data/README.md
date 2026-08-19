# Data

Dataset **UNSW-NB15** tidak disertakan di repositori ini (ukuran besar dan tunduk pada ketentuan penyedia aslinya).

## Cara memperoleh

1. Buka halaman resmi dataset: <https://research.unsw.edu.au/projects/unsw-nb15-dataset>
2. Unduh folder **Training and Testing Sets** yang berisi:
   - `UNSW_NB15_training-set.csv` (175.341 baris, 45 kolom)
   - `UNSW_NB15_testing-set.csv` (82.332 baris, 45 kolom)
3. Letakkan keduanya di `data/raw/`:

```
data/
└── raw/
    ├── UNSW_NB15_training-set.csv
    └── UNSW_NB15_testing-set.csv
```

4. Pada notebook, atur `DATA_DIR` agar menunjuk ke `data/raw/`.

Folder `data/raw/` sudah masuk `.gitignore`, jadi file CSV tidak akan ikut ter-commit.

## Sitasi

Moustafa, N. & Slay, J. (2015). *UNSW-NB15: a comprehensive data set for network intrusion detection systems.* Military Communications and Information Systems Conference (MilCIS).
