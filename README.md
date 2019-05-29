# MRNet_Classification
MRNet classification using pre-trained model (Xception) from Keras.

# Problem Statement

### MRNet dataset
The MRNet dataset consists of 1,370 knee MRI exams performed at Stanford University Medical Center. The dataset contains 1,104 (80.6%) abnormal exams, with 319 (23.3%) ACL tears and 508 (37.1%) meniscal tears; labels were obtained through manual extraction from clinical reports.

### MRNet Details
The most common indications for the knee MRI examinations in this study included acute and chronic pain, follow-up or preoperative evaluation, injury/trauma. Examinations were performed with GE scanners (GE Discovery, GE Healthcare, Waukesha, WI) with standard knee MRI coil and a routine non-contrast knee MRI protocol that included the following sequences: coronal T1 weighted, coronal T2 with fat saturation, sagittal proton density (PD) weighted, sagittal T2 with fat saturation, and axial PD weighted with fat saturation. A total of 775 (56.6%) examinations used a 3.0-T magnetic field; the remaining used a 1.5-T magnetic field. 

### Splits
The exams have been split into a training set (1,130 exams, 1,088 patients), a validation set (called tuning set in the paper) (120 exams, 111 patients), and a hidden test set (called validation set in the paper) (120 exams, 113 patients). To form the validation and tuning sets, stratified random sampling was used to ensure that at least 50 positive examples of each label (abnormal, ACL tear, and meniscal tear) were present in each set. All exams from each patient were put in the same split.

### Objective
Classify exams using Deep CNN Model (We used: Xception) and illustarte how Sagittal/Axial/Coronal views help in MRI classification.


#### Note
This project is done for Pattern Recognition class (Spring 2019) with @NevineSaid (https://github.com/NevineSaid) using Google Colab.


