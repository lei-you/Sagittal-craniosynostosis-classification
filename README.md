# Sagittal-craniosynostosis-classification

## Objectigve:
Sagittal craniosynostosis (CSO) occurs when the sagittal suture of a growing child’s skull is fused prematurely. Surgery, which involves re-moving the affected bones and increasing the volume of the cranium by repositioning the bone segments or using external forces to guide, is the primary treatment for CSO. For preparation of the surgery, physicians usually classify sagittal CSO subtypes by examining the reconstruction of skulls from CT images or the laser scans of the patients’ 3D skull. We have proposed an automated sagittal CSO classification algorithm based on features extracted from projected 3D skull images. However, these features would become invalid if they were extracted from irregular skulls or skulls with completely closed sutures. In order to tackle this problem, we proposed a 3D skull multi-view images-based algorithm to classify the subtypes of sagittal CSO, like the physicians diagnosing these 3D reconstruction images of skulls or laser scans. Our innovations include: 1) the first to propose a multi-view learning algorithm to classify the subtypes of sagittal CSO cases, 2) 3D rendering and a patch-based erosion method are adopted for data augmentation to keep the original ratio
and shape of the images, and 3) utilizing a transfer leaning training strategy to train the convolutional neural network (CNN) and a multi-view-based prediction strategy for classifying the cases.
## Details

![cso](https://github.com/user-attachments/assets/eeb8b331-f794-4972-80d8-d19d8917e846)

## Tools

<img src="https://img.shields.io/badge/-Tensorflow-4D4D4D?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-OpenCV-006400?&style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/-3D rendering-000080?&style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/-3D reconstruction-3776ab?&style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/-Transfer Learning-EF5350?&style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/-data clearn and preprocessing-EE7600?&style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/-tSNE-0097A7?&style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/-Git-F05032?&style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/-data visualization-3776ab?&style=for-the-badge&logo=python&logoColor=white" />

## ourpaper:
You, L., Deng, Y., Zhang, G., Wang, Y., Bins, G. P., Runyan, C. M., ... & Zhou, X. (2022). A novel sagittal craniosynostosis classification system based on multi-view learning algorithm. Neural Computing and Applications, 34(17), 14427-14434.
You, L., Zhang, G., Zhao, W., Greives, M., David, L., & Zhou, X. (2020). Automated sagittal craniosynostosis classification from CT images using transfer learning. Clinics in surgery, 5.
