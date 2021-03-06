## Deep learning methods for histopathology image analysis

Codes for deep learning-based pipelines for whole slide tissue image (WSI) analysis: 

### Segmentation of Nuclei: 

    Code Repository: 
       https://bit.ly/2IEMDp8 (https://github.com/SBU-BMI/quip_cnn_segmentation)
       Trained CNN model can be downloaded from
       https://bit.ly/3pBHQFE (http://vision.cs.stonybrook.edu/~lehhou/download/model_trained.tar.gz)
              
    Related Papers:
       Hou, L., Gupta, R., et al. Dataset of segmented nuclei in hematoxylin 
       and eosin stained histopathology images of ten cancer types. Sci Data7, 185 
       (2020). https://doi.org/10.1038/s41597-020-0528-1
              
       Hou L, Agarwal A, et al. Robust histopathology image analysis: to label or 
       to synthesize?. Proceedings of the IEEE Conference on Computer Vision and 
       Pattern Recognition 2019 (pp. 8533-8542).
              
    Datasets:
       https://tinyurl.com/yyqoq2n2
  
  ### Creating Tumor Infiltrating Lymphocyte (TIL) Maps:
  
    Code Repository:
       Recent codes and models developed using the VGG16 and Inception-V4 networks.
       These are the recommended models for use in TIL analysis. 
           https://bit.ly/38JSqEN (https://github.com/SBU-BMI/quip_classification) 
           Trained VGG16 and Inception-V4 models can be downloaded from
           https://bit.ly/3lArJWA (https://stonybrookmedicine.box.com/shared/static/bl15zu4lwb9cc7ltul15aa8kyrn7kh2d.zip)
          
       Codes used in the Cell Reports paper.
           https://bit.ly/3nnFXuq (https://github.com/SBU-BMI/u24_lymphocyte)  
              
    Related Papers:
       Saltz J, Gupta R,  et al. Spatial organization and molecular 
       correlation of tumor-infiltrating lymphocytes using deep learning 
       on pathology images. Cell reports. 2018 Apr 3;23(1):181-93.
              
       Abousamra S, Hou L,  et al. Learning from thresholds: fully 
       automated classification of tumor infiltrating lymphocytes for 
       multiple cancer types. arXiv preprint arXiv:1907.03960. 2019 Jul 9.
              
    Datasets:
       Dataset in the Cell Reports paper: 
            https://doi.org/10.7937/K9/TCIA.2018.Y75F9W1
       TIL analysis results from the VGG16 and Inception-V4 models:
       (The data is being uploaded, check back in a few days.)
            https://bit.ly/3kJJDVT (https://stonybrookmedicine.box.com/s/qb4gi6o1dihvds0tuieaclpdbcl03qzu)
            
  ### TIL/Tumor Quantification in TCGA Breast Cancer WSIs:
 
    Code Repository:
       https://bit.ly/2K8pmwh (https://github.com/SBU-BMI/quip_cancer_segmentation)
       Trained CNN model can be downloaded from
       https://bit.ly/3pzvqyo (https://stonybrookmedicine.box.com/shared/static/1hdfb06lgd08xfbpoly9tjp6c6i665nz.zip)
              
    Related Papers:
       Le, Han, Rajarsi Gupta, Le Hou, et al. "Utilizing automated breast 
       cancer detection to identify spatial distributions of tumor infiltrating 
       lymphocytes in invasive breast cancer." The American Journal of Pathology (2020).
              
    Datasets: 
       https://bit.ly/2UtZcpO (https://app.box.com/s/1qux9ub21zcvpwao1cf81ar4milxl25x)
 
 ### Segmentation of Tumor Regions in Pancreatic Cancer Cases
 
    Code Repository:
       https://bit.ly/2IJRLZp (https://github.com/SBU-BMI/quip_paad_cancer_detection.git)
       Trained CNN model can be downloaded from
       https://bit.ly/32Pcn9q (https://github.com/SBU-BMI/quip_prad_cancer_detection/tree/master/data/models_cnn)
    
    Related Papers: 
       Le H, Samaras D, Kurc T, Gupta R, Shroyer K, Saltz J. Pancreatic cancer detection 
       in whole slide images using noisy label annotations. InInternational Conference on 
       Medical Image Computing and Computer-Assisted Intervention 2019 Oct 13 (pp. 541-549). Springer, Cham.
