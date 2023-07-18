# Pneumonia-Detection
Developing a model that detects chest x-rays with Pneumonia.

**The aim of the project is to develop/train/test a CNN or use and fine-tune a pre-trained CNN model (this will depend on the accuracies) for Pneumonia chest-xrays detection.**

**Members of the group:**
- Feras Rafeh

**Dataset info:**
- **Context**:
  
  Pneumonia is an infection of the air sacs in one or both lungs. It is characterized by severe cough with phlegm, fever, chills and difficulty in breathing. It is   usually caused by bacteria or viruses. Pneumonia is usually treatable with antibiotics (if bacterial). If it is untreated it can lead to serious complications,     such as bacteremia (infection that spreads to the bloodstream), lung abscesses (pus formation in the lung cavities), impaired breathing (trouble getting enough     oxygen; ventilator may be required), acute respiratory distress syndrome (severe form of respiratory infection), and pleural effusion (fluid build-up in tissue     that lines the lungs).
  
  Pneumonia is a serious condition that can lead to hospitalization and even death. It is especially dangerous for young children, older adults, and people with 
  weakened immune systems. It is the single largest infectious cause of death in children worldwide. It kills more children younger than 5 years old each year than 
  any other infectious disease, such as HIV infection, malaria, or tuberculosis.

  ![jZqpV51](https://github.com/ferasrafeh/Pneumonia-Detection/assets/122606184/c783da9f-3882-4c6d-9a5b-d39fbe16be0c)

  As we can see above, a normal chest X-ray shows clear lungs without any areas of abnormal opacification. Bacterial pneumonia usually appears as a white arrow in 
  the right upper lobe and has a focal lobar consolidation. On the other hand, viral pneumonia appears as a more diffuse ‘‘interstitial’’ pattern in both lungs.

- **Source**:
  
  [Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
  
- **Content**:
  
  The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images   
  (JPEG) and 2 categories (Pneumonia/Normal).

  Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and   
  Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

  For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The 
  diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, 
  the evaluation set was also checked by a third expert.
