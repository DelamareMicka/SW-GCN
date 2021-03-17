# SW-GCN

# Main page of Graph Convolutional Networks Skeleton-Based Action Recognition for Continuous Data Stream : A Sliding Window Approach done by [ESIGELEC](https://www.esigelec.fr/) and [SIATECH](https://www.siatech.fr/)


 


## Abstract :
<p style="text-align:justify";>
This paper introduces a novel deep learning based approach to human activity recognition. The method consists of a Spatio-Temporal Graph Convolutional Network  operating in real time thanks to a sliding window approach. The proposed architecture consists of a fixed window for train, validation and test process with a Spatio-Temporal-Graph Convolutional Network for skeleton-based action recognition. We evaluate our architecture on two available datasets of common continuous stream action recognition, the Online Action Detection dataset and UOW Online Action 3D datasets. This method is used for temporal detection and classification of the performed action recognition in real time.</p>

## OAD dataset

### Confusion matrix and statistics of Validation for OAD dataset : 

<p align="center">
<img src="Statistics_validation_OAD.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_validation_OAD.PNG">
</p>

### Confusion matrix and statistics of Test for OAD dataset : 

<p align="center">
<img src="Statistics_test_OAD.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_testOAD.PNG">
</p>

## UOW dataset
### SW-GCN method
### Confusion matrix and statistics of Validation for UOW dataset : 

<p align="center">
<img src="Statistics_validation_UOW.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_validation_UOW.PNG">
</p>

### Confusion matrix and statistics of Test for UOW dataset : 

<p align="center">
<img src="Statistics_test_UOW.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_test_UOW.PNG">
</p>

### SW-CNN method
 ### Confusion matrix and statistics of Validation for UOW dataset : 
<p align="center">
<img src="Statistics_validation_UOW_cnn.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_validation_UOW_cnn.PNG">
</p>

### Confusion matrix and statistics of Test for UOW dataset : 

<p align="center">
<img src="Statistics_test_UOW_cnn.PNG">
</p>
<p align="center">
<img src="Confusion_matrix_test_UOW_cnn.PNG">
</p>
## Paper :

Mickael Delamare<sup>1</sup><sup>2</sup>, Cyril Laville<sup>1</sup>, Adnane Cabani<sup>2</sup>,Houcine Chafouk<sup>2</sup>.  

<sup>1</sup>[siatech](https://www.siatech.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN,mickael.delamare@siatech.fr   
<sup>2</sup>[ESIGELEC](http://www.esigelec.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN, adnane.cabani@esigelec.fr

How to cite :

>@article{delamare122021graph,
 > title={Graph Convolutional Networks Skeleton-based Action Recognition for Continuous Data Stream: A Sliding Window Approach},
 > author={Delamare12, Mickael and Laville, Cyril and Cabani, Adnane and Chafouk, Houcine},
 > year={2021}
>}

DOI : 10.5220/0010234904270435

LINK : https://www.scitepress.org/Papers/2021/102349/102349.pdf

Submitted to VISAPP Conference

## Code :
You will find in repository two files : 
  -Data Processing for OAD  
  -Data Processing for UOW action 3D dataset  
  -The algorithm trained for OAD (SW-GCN-OAD.pt)  
  -The algorthm trained fot UOW action 3D dataset (SW-GCN-UOW.pt)  
  -The algorithm trained for UOW action 3D dataset (SW-CNN.pt)
  
if you have any question don't hesitate to contact : delamare.mickael5@gmail.com

## Result demo in movie for OAD dataset :

<p align="center">
<img src="final_dem_v2.gif">
</p>



