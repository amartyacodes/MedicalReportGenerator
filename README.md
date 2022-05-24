# MedicalReportGenerator

## Generates a report upon receiving a X-Ray image

The model was built as a part of the final year undergraduate project by Amartya Bhattacharya, Department of Computer Science and Engineering, 
University of Calcutta.


The model was built using [![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg?style=plastic)](https://badge.fury.io/py/tensorflow) and [![TensorFlow 2.8](https://img.shields.io/badge/TensorFlow-2.8-FF6F00?logo=tensorflow)](https://github.com/tensorflow/tensorflow/releases/tag/v2.8.0) 

Webapp Link:
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/amartyacodes/medicalreportgenerator/main/final.py)


## Dataset 
[Images](https://academictorrents.com/details/5a3a439df24931f410fac269b87b050203d9467d) and [Reports](https://academictorrents.com/details/66450ba52ba3f83fbf82ef9c91f2bde0e845aba9)

## Model Used
![download - 2022-05-24T190249 128](https://user-images.githubusercontent.com/44440114/170047687-a41fb8a6-a4e6-4ba4-9253-0da235e4a641.png)

## Results

# Results
| Sl No. | Model | BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4
| - | --------------------- | ----------- | -- | -- | -- |
| 1. | Attention Model (greedy search) | 0.306819 | 0.302596 | 0.339031 | 	0.383689 |
| 2. | Custom Final Model (greedy search) | 0.214501 |	0.243265 |	0.303785 |	0.36675 |
| 3. | Simple Encoder Decoder (greedy search) | 0.317412 |	0.308454 |	0.333496 |	0.366244 |
**So Attention Model Was used**

## Upload Files 
**You can upload 2 X-ray images. The first should be of the front view and second one of the side view (doesn't matter which side).**
**The 2nd image is optional**

### Sample X-ray image for 1st one
![CXR54_IM-2145-1001](https://user-images.githubusercontent.com/44440114/170045262-2979f0f1-6d06-45f8-9c49-4f74f86fd164.png)
### Sample X-ray image for the 2nd one 
![CXR54_IM-2145-1002](https://user-images.githubusercontent.com/44440114/170045320-6531b1a2-30fe-4135-a06c-171af8a85c6c.png)

### Sample Working Video
![screen-capture (1)](https://user-images.githubusercontent.com/44440114/170054551-ca75943d-7bcf-45e3-9f08-ade165d12a3a.gif)



## Acknowledgement
I would like to thank my supervisor [Dr. Rajib Das]( https://www.caluniv.ac.in/academic/Compsc/Rajib-Kumar-Das.pdf), Professor, Department of Computer Science and Engineering, University of Calcutta 
for giving me the opportunity to work on the project. I would also like to thank [Rupam Kumar Roy](https://www.linkedin.com/in/rupam-kumar-roy-346973192/) and [Hrithik Anand](https://www.linkedin.com/in/hrithik-anand-ab03831aa/) for collaborating with me.

**Detailed Report will be written later**
