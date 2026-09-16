
# Kidney_Tumour_Semantic_Segmentation_Using_UNet Model and SAM Model
<img width="200" height="200" alt="9409-kidney-cancer" src="https://github.com/user-attachments/assets/0d97b817-e36a-4756-bfdb-ef85b5014c5c" />
<img width="500" height="350" alt="Kiney_Tumour_Image" src="https://github.com/user-attachments/assets/a2e97d4b-c891-4d58-b0e5-3d71df7779fd" />


A kidney tumour is an abnormal mass of cells on your kidney that can be noncancerous or cancerous.
**Common Symptoms:**
Early tumours often cause no symptoms at all. As they grow, signs may include: [(https://my.clevelandclinic.org/health/diseases/24321-kidney-tumor) Blood in your urine (pink, red, or dark color)Pain in your side or lower back that does not go awayUnexplained weight lossConstant tiredness or a low fever (https://www.mayoclinic.org/diseases-conditions/kidney-cancer/symptoms-causes/syc-20352664), (https://my.clevelandclinic.org/health/diseases/24321-kidney-tumor)Diagnosis and TestsDoctors find many kidney tumors by accident during scans for other health issues. Evaluation tools include: (https://www.kidney.org/kidney-topics/kidney-cancer). Imaging tests like ultrasounds, CT scans, or MRIs Blood and urine tests, a tissue sample (biopsy) if needed. 

In this project, Kidney Tumour Semantic Segmentation was performed using UNet architecture. (Encoder-Decoder Network).
Encoder compresses the image to make a latent space representation and Decoder expands the image back.
Also SAM model (Segment Anything model) was also used for semantic segmentation of Kidney stone images and both the 
results obtained by both the models were compared to perceive which model gave better accuracy and prediction results.

## Dataset Description
There are more than 400,000 new cases of kidney cancer each year, and surgery is its most common treatment. Due to the wide variety in kidney and kidney tumor morphology, there is currently great interest in how tumour morphology relates to surgical outcomes, as well as in developing advanced surgical planning techniques. Automatic semantic segmentation is a promising tool for these efforts, but morphological heterogeneity makes it a difficult problem.
(source: Kaggle) (Dataset Kaggle Link: "https://www.kaggle.com/datasets/orvile/kits19-png-zipped")
The goal of this challenge is to accelerate the development of reliable kidney and kidney tumour semantic segmentation 
methodologies. We have produced ground truth semantic segmentations for arterial phase abdominal CT scans of 300 unique 
kidney cancer patients who underwent partial or radical nephrectomy at our institution. 210 of these have been released 
for model training and validation, and the remaining 90 will be held out for objective model evaluation.

## Results
<img width="1479" height="511" alt="Kidney_Stone_Training_Image1" src="https://github.com/user-attachments/assets/11c0d5ea-ed83-4173-bab6-db1ec37ebf1a" />

<img width="1479" height="511" alt="Kidney_Stone_Training_Image2" src="https://github.com/user-attachments/assets/529b7f9d-98b3-4fc7-9348-8a6f9a01de19" />

<img width="1479" height="511" alt="Kidney_Stone_Training_Image3" src="https://github.com/user-attachments/assets/e4ea81b8-d6cc-49a9-af92-61080fcb2ed8" />

<img width="1479" height="511" alt="Kidney_Stone_Training_Image4" src="https://github.com/user-attachments/assets/ccad4359-e222-464a-a0c0-ce36e8fd29c3" />

<img width="1479" height="511" alt="Kindey_Stone_Training_Imge5" src="https://github.com/user-attachments/assets/6ce63220-413a-437b-ae4e-9c5e87b0f185" />






# Future Work
