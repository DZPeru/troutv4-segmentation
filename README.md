# Fish Segmentation, Fish labelled, Fish Dataset

Datasets of fish for deep learning. Do a pull request if you want to add one or create an issue.

## Models trained by the datasets

- YOLOv3: FISH9002 https://github.com/DZPeru/fishv3
- YOLOv4: FISH9002 https://github.com/DZPeru/fishv4
- YOLOv5: FISH9003 Coming soon...

# Datasets 

- All datasets available on: https://bit.ly/34xV7al Link to Google Drive ✔️

## Datasets Standardized

Thanks to Roboflow, we can export for different formats: 

- Powered by Roboflow (All images resized to 416x416): **JSON** (`COCO`, `CreateML`), **XML** (`Pascal VOC`), **TXT** (`YOLO Darknet`, `YOLO v3 Keras`, `YOLO v4 PyTorch`, `YOLO v5 PyTorch`), **CSV** (`Tensorflow Object Detection`, `RetinaNet Keras`, `Multiclass Classification`), **Others** (`Tensorflow TFRecord`).

- Powered by CVAT (All images original size): **JSON** (`COCO`, `Datumaro`), **XML** (`CVAT Image`, `CVAT Video`, `LabelMe`, `PASCAL VOC`), **TXT** (`MOT`, `YOLO`), **JPG,PNG** (`ImageNet`, `Segmentation Mask`), **Others** (`Tensorflow TFRecord`).

`Choose just one zip file for one model, select the zip file accord to your model.`

| Date       | Images     |  Classes | Download dataset & Code (TR70/VL20/TS10) |
| ---------- | ---------- | -------- | -------------------------------------    |
| 2020-12-15 | +3000      | +1       | [FISH9003 - Coming soon ...](#)          |
| 2020-12-11 | 723 (301)  | 1        | [FISH9002](https://bit.ly/34BvYeM) ✔️     |
| 2020-10-18 | 301        | 1        | [FISH9001](https://bit.ly/34BvYeM) ✔️     |

### Downloading and using dataset

Example code to use only with Roboflow [notebooks](https://models.roboflow.com/object-detection) to use the repo and locate correctly.


```
# Instead of doing:
!curl -L "ROBOFLOW LINK" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip
# Use:
!gdown --id "ID OF THE GOOGLE DRIVE ZIP" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip
```

## Resources [Update 2020-08-05]

Keywords to find these datasets: fish, trout

### List of resources: 

- 2020-08-25 [Kaggle](https://www.kaggle.com/datasets) 9
- 2020-12-15 [Google Images](https://www.google.com/imghp?hl=en) 1
- 2020-08-25 [Google Datasets](https://datasetsearch.research.google.com/) 0
- 2020-08-25 [Google BigQuery](https://cloud.google.com/bigquery/public-data/) 0
- 2020-08-25 [dataquest.io](www.dataquest.io) 0
- 2020-08-25 [Socrata](https://opendata.socrata.com/) 0
- 2020-08-25 [Data.gov](https://www.data.gov/) 0
- 2020-08-25 [data.world](https://data.world/datasets) 0
- 2020-08-25 [NOAA Fisheries](https://swfscdata.nmfs.noaa.gov/labeled-fishes-in-the-wild/) 1
- 2020-08-25 [Fish-Pak](https://data.mendeley.com/datasets/n3ydw29sbz/3) 1
- 2020-08-25 [Github](https://github.com) 1
- 2020-08-25 [FishBase](https://www.fishbase.de/) 1
- 2020-08-26 [CoCo Dataset](https://cocodataset.org/) 1

### List of datasets found

- 2020-08-25 FISH0015 https://drive.google.com/drive/u/0/folders/1VCEsrkksZqUffLnvqkAml5f9DZvhegRI (125MB) ✔️
- 2020-08-25 FISH0014 https://www.kaggle.com/ssfailearning/futurefish (351MB) ✔️
- 2020-08-25 FISH0013 https://www.kaggle.com/jasmeetkaur/fishdataset (3.0GB) ✔️
- 2020-08-25 FISH0012 https://www.kaggle.com/tomeryacov/fishfish (302MB) ✔️
- 2020-08-25 FISH0011 https://www.kaggle.com/linykc/fish-images-dataset (297KB) ❌
- 2020-08-25 FISH0010 https://www.kaggle.com/khaledelsayedibrahim/fishclassifyfinal (605MB) ✔️
- 2020-08-25 FISH0009 https://www.kaggle.com/jasmeetkaur/fishdatasetcleaned (1.1GB) ✔️
- 2020-08-25 FISH0008 https://www.kaggle.com/cmkmoorthy/aquariumfished (189MB) ✔️
- 2020-08-25 FISH0007 https://www.kaggle.com/amitneeman/fish-2 (309MB) ✔️
- 2020-08-25 FISH0006 https://www.kaggle.com/khaledelsayedibrahim/fishclassifierfinal (553MB) ✔️
- 2020-08-25 FISH0005 https://swfscdata.nmfs.noaa.gov/labeled-fishes-in-the-wild/ (433MB) ✔️
- 2020-08-25 FISH0004 https://data.mendeley.com/datasets/n3ydw29sbz/3 (3.2GB) ✔️
- 2020-08-25 FISH0003 https://apps.aims.gov.au/metadata/view/38c829d4-6b6d-44a1-9476-f9b0955ce0b8 () ✔️
- 2020-08-25 FISH0002 https://www.fishbase.de/photos/ThumbnailsSummary.php?Genus=Oncorhynchus&Species=mykiss (34MB) ✔️
- 2020-08-25 FISH0001 https://github.com/cocodataset/cocoapi (API Connection) ✔️
