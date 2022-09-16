# Skripsi CNN

on this page:
- [enviroment](#enviroment)
- [dataset](#dataset)
- [structure folder](#structure-folder)

## enviroment
- Tensorflow v2.9.1
- Python 3.10.6

## dataset
you can download the dataset from 
1. https://www.kaggle.com/datasets/ambarish/breakhis?datasetId=209316&sortBy=voteCount&select=Folds.csv or 
2. https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/

recommended bypassing kaggle for optimal download speed, and downloading the Folds.csv file if downloading from option 2, file Folds.csv can be downloaded on kaggle in option 1

## structure folder
- root
- BreaKHis_v1 (download first and extract here)
- Folds.csv (download first)
- src (folder where code to be executed)
  - output (folder model result saved)
  - BreakHis-1.ipynb (Praprocess mainly, run first. Read markdown notes)
  - BreakHis-2.ipynb (use transfer learning RestNet)
  - BreakHis-3.ipynb (use transfer learning DenseNet)

for other files will be generated in the code especially the preprocess section, you can ignore other structures, or can be understood during the code process,
- other folder at the root level is used for convenience in using the image generator data