**Dental Disease Detection Using Image Processing**

Dental diseases are among the most common health problems worldwide and can 
significantly affect an individual’s quality of life if not diagnosed at an early stage. 
Panoramic dental X-ray imaging is widely used by dentists to examine teeth, jaw bones, 
and surrounding anatomical structures. However, manual interpretation of these images 
requires expertise, is time-consuming, and may be prone to human error, especially in 
large-scale screening scenarios. 
This project presents an automated system for dental disease detection using image 
processing and traditional machine learning techniques. The proposed system analyzes 
panoramic dental X-ray images and classifies them into healthy or diseased categories. 
Image preprocessing techniques such as grayscale conversion, resizing, and noise 
removal are applied to improve image quality. Data augmentation is used to increase 
dataset diversity. Histogram of Oriented Gradients (HOG) is employed for feature 
extraction, capturing important structural and texture information from dental images. 
These features are then classified using a Support Vector Machine (SVM) classifier, with 
Random Forest used for performance comparison. 
The results demonstrate that the SVM-based approach achieves good classification 
accuracy while remaining computationally efficient and suitable for CPU-based systems. 
The proposed system can serve as a supportive diagnostic tool for dentists and as a 
foundation for future advanced dental image analysis systems.

. **Dataset Description**

The dataset used in this project consists of panoramic dental X-ray images collected from 
publicly available sources and academic datasets. The images represent a variety of 
dental conditions and anatomical structures, making them suitable for disease detection 
tasks. 
The dataset is divided into two main classes: 
• Healthy: Images showing normal dental structures without visible signs of 
disease. 
• Diseased: Images containing dental abnormalities such as dental caries, periapical 
radiolucency, sinus mucosal thickening, and other pathological indicators. 
Each panoramic X-ray image includes several important anatomical regions: 
• Dental region (teeth and roots) 
• Maxillary sinus region 
• Jaw bone and tonsillar region 
The images vary in resolution, contrast, and noise levels, which reflects real-world 
clinical conditions. This variation makes preprocessing an essential step to ensure 
consistency across the dataset. The dataset is organized into separate folders for healthy 
and diseased images, enabling supervised learning.
