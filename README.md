## Acne Classification Model


## Repo Structure
```
acne-ml/
├── README.md
├── requirements.txt
├── .gitignore
├── configs/
│   ├── baseline.yaml
│   └── resnet50_finetune.yaml
├── data/            
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_final_results.ipynb
├── src/
│   ├── data/
│   │   ├── dataset.py
│   │   └── transforms.py
│   ├── models/
│   │   ├── baseline_lr.py
│   │   ├── small_cnn.py
│   │   └── resnet50.py
│   ├── train.py
│   └── evaluate.py
└── outputs/
```

hiii