# SODA-Dataset
The SODA Dataset is a computer vision dataset containing aerial imagery of small objects captured at different altitudes.  The Small Objects from Different Altitude (SODA) Dataset contains 829 images and 6719 object annotations. The objects are annotated using polygons. 

## Download SODA Dataset
The SODA dataset can be donwloaded from [here](https://drive.google.com/drive/folders/1Xd-7oHogMidzH5NA3_Ng1sU75_w66mBg?usp=sharing).

#### [SODA_Dataset_Split_Altitudes_COCO.zip](https://drive.google.com/file/d/1FDHPxeEkI9II6IQKppnsVVXPg_wa0pHP/view?usp=drive_link)
* Description: The 829 images are grouped into their respective altitude directory.
* Recommended usage: Test and validation using images captured from different altitudes.

#### [SODA_Dataset_COCO.zip](https://drive.google.com/file/d/1NBoaCBWChLasjTb1LVHwj-w_A_9jfG5F/view?usp=drive_link)
* Descritpion: The 829 images are merged into one directory.
* Recommended uage: Training a small object detector using images captured at different altitudes. 

## Access the SODA Dataset from Roboflow
The SODA dataset is also hosted on Roboflow for public access. The SODA Data respository on Roboflow can be accessed from [here](https://universe.roboflow.com/danielpisani/).

## Dataset Classes
* Clear Plastic Bottles (clear_plastic_bottle)
* Drink Cans (drink_can)
* Drink Cartons (drink_carton)
* Glass Bottles (glass_bottle)
* Glass Jars (glass_jar)
* Other Plastic Bottles (other_plastic_bottle)

## SODA Dataset Composition
* 1m (Captured using an iPhone SE): 452 images | 720 annotations
* 5m: 202 images | 1853 annotations
* 10m: 50 images | 1142 annotations
* 15m: 35 images | 958 annotations
* 20m: 30 images | 768 annotations
* 25m: 30 images | 716 annotations
* 30m: 30 images | 612 annotations

Altitudes are all AGL (Above Ground Level). Aerial images were captured using a combination of DJI Mini 2 and a DJI Air 2S drones. 

## News
**January 27, 2024:** First upload of SODA dataset with 829 images and 6719 annotations. 
