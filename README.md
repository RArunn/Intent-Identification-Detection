This repository contains optimized code for running Qwen 2.5-VL-3B-Instruct on three major HOI detection datasets: HICO-DET, V-COCO, and SWiG-HOI. All code is designed for Google Colab with GPU acceleration.

# Quick Setup
Prerequisites  
Google Colab Pro (recommended for A100 GPU)  
Google Drive account (for HICO-DET dataset storage)

# Datasets
1. HICO-DET  
   Dataset: Access from https://drive.google.com/file/d/1dUByzVzM6z1Oq4gENa1-t0FLhr0UtDaS/view?usp=drive_link  
   Setup: Save hico_20160224_det.tar.gz to your Google Drive at /content/drive/MyDrive/hicodet/  
   Images: Uses test2015 split (~9,658 images)  
   Code: hicodet.ipynb
   
3. V-COCO (COCO val2014)  
   Dataset: Downloads automatically from COCO  
   Images: COCO validation 2014 (~40,000 images)  
   URL: http://images.cocodataset.org/zips/val2014.zip  
   Code: vcoco.ipynb
   
5. SWiG-HOI  
   Dataset: Downloads automatically  
   Images: 512x512 resolution subset  
   URL: https://swig-data-weights.s3.us-east-2.amazonaws.com/images_512.zip  
   Code: swighoi.ipynb
   
# Running the Code

For HICO-DET:  
Access hico_20160224_det.tar.gz from here https://drive.google.com/file/d/1dUByzVzM6z1Oq4gENa1-t0FLhr0UtDaS/view?usp=drive_link  
Save to Google Drive at path: /content/drive/MyDrive/hicodet/hico_20160224_det.tar.gz  
Upload hicodet.ipynb to Google Colab  
Mount Google Drive and run all cells  

For V-COCO:  
Upload vcoco.ipynb to Google Colab  
Run all cells - COCO val2014 downloads automatically  

For SWiG-HOI:  
Upload swighoi.ipynb to Google Colab  
Run all cells - dataset downloads automatically  

# Files
1. hicodet.ipynb - HICO-DET processing with Google Drive integration
2. vcoco.ipynb - V-COCO processing notebook with auto-download
3. swighoi.ipynb - SWiG-HOI processing with subset support
