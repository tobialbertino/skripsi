# Skripsi CNN

on this page:
- [enviroment](#enviroment)
- [dataset](#dataset)
- [structure folder](#structure-folder)
- [used file](#used-file)
- [Model File](#output-model)

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
  - BreakHis-3.ipynb (use transfer learning RestNet50v2)
  - BreakHis-4.ipynb (use transfer learning DenseNet)

for other files will be generated in the code especially the preprocess section, you can ignore other structures, or can be understood during the code process,
- other folder at the root level is used for convenience in using the image generator data

## used file

in this project, the files used are only some of the ones I have listed in this repository, other than that they are for trial and error or experimental. The files you need to pay attention to are:
- /src/BreakHis-3-RestNet50V2-HP-fineTune-FIX-v2.ipynb 
- /src/BreakHis-4-DenseNet121-HP-fineTune-FIX.ipynb 

## Output model

Because the size of the model output from the transfer learning results is quite large, I use OneDrive IPb to upload the model results, the model can be accessed at the following link:  
[**Output Model link OneDrive**](https://appsipbacid-my.sharepoint.com/:f:/g/personal/muhamad_tobiaja232_apps_ipb_ac_id/EprpGn2mHMBHlHqsoP-TOA0B02LHNwdZeujJ4Aezl04kBA?e=I3tyYs)  
and the model used is from the following directory:
- output/restnet/restnet50v2_model__HP_fineTune_FIX-v2.h5 
- output/denseNet/denseNet_HP.h5 