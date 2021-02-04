# Deep learning-based face mask status detection using automated GUI for COVID-19

The example of training image and training xml can be found in the respective directory. The six different augementation image and their corresponding xml file can be fournd in the augmented_image_example and augmented_xml_example folder.

# The basic overview of our face mask detection system is shown in Fig 1. 
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure1.PNG)

# The detailed statistics of our dataset without augmentation is shown in Table 1
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Table1.PNG)

# The front-end user interface of the proposed annotation and detection tool is shown in Figure 2.
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure2.PNG)

# The different augmentation of images obtained from our proposed GUI is shown in Figure 3

![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure3.PNG)

# The detailed statistics of our datasets after augmentation from the GUI is shown in Table 2

![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Table2.PNG)

# The schematic overview of our face mask object detection is shown in Figure 4

![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure4.PNG)

# The experimental results from four different object detection model using ResNet101 is shown in Table 3
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Table3.PNG)

# The experimental results from four different object detection model using ResNet50 is shown in Table 4
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Table4.PNG)

# The qualitative results from the test data is shown from Figure 5(a) to Figure 5(d)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%205(a).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%205(b).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%205(c).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%205(d).PNG)

# The visualization of the heatmap from the pyramidal feature of Feature pyramid network is shown in Figure 6
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%206.PNG)

# Failure analysis and discussion
## Our proposed mask detection system achieves 91% accuracy. We analyse why our system can't predict for remaining 9% of the test data. There are basically four reasons for not detecting accurately.
1)The data distribution of our face mask dataset is irregular in some cases, which makes the network confuse to accurately predict
2)The area of interest for the face mask object is far from the camera. This makes hard to detect for both man and machine
3) The third region is occlusion (some of the face mask regions are occluded by a person's face)
4) The background billboards/signboards of the person which we didn't consider during annotation results the false positive rates.
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%207(a).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%207(b).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%207(c).PNG)
![alt text](https://github.com/pratikshaya/face_mask_detection/blob/main/figures_from_paper/Figure%207(d).PNG)
