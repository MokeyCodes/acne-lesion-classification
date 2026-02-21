## Acne Classification Model


## Repo Structure
acne-ml/
├── README.md
├── requirements.txt  (or environment.yml)
├── .gitignore
├── configs/
│   ├── baseline.yaml
│   └── resnet50_finetune.yaml
├── data/              # gitignored (except maybe a tiny sample)
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_final_results.ipynb
├── src/
│   ├── data/
│   │   ├── datamodule.py   (or dataset.py)
│   │   └── transforms.py
│   ├── models/
│   │   ├── baseline_lr.py
│   │   ├── small_cnn.py
│   │   └── resnet50.py
│   ├── train.py
│   └── evaluate.py
└── outputs/            # gitignored (models/plots/metrics)