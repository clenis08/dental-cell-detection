# dental-cell-detection
🦠🧫🔬 Identification of dental pulp cells like fibroblast and odontoblast with Mask -RCNN, this is me degree project. 

## Description 

The dental pulp is a highly vascularized tissue containing different cellular elements such as fibroblasts and odontoblasts, cells involved in restoring the integrity and maintaining the dentin-pulp complex's vitality and functioning. However, obtaining an adequate histological characterization is difficult due to the complex cellular architectural organization; likewise, identify and manually classify microscopic samples. This research aimed to develop a system for the identification of cellular structures in histological images of the pulp tissue using deep learning techniques. The proposed methodology consists of the following steps: 

* Images were captured from the histological tissue samples, provided by the Biomaterials group, using a LEICA DM500HD microscope.
* Preprocessing techniques were performed, which consisted of manually segmenting and marking the regions of interest where the cellular structures under study (odontoblasts and fibroblasts) were located; as a result, the dataset for training and validation of the algorithm was obtained. 
* Once the data was generated, the ***Mask-RCNN*** model, a type of Convolutional Neural Network (CNN), which performs segmentation by instances, was trained. 
* The performance was evaluated using standard metrics, and the neural network was re-trained until the best performance was obtained. 
* Finally, we obtained a model with a classification accuracy rate of 80% and an IoU detection rate of 79%, and an error between classes less than 1.2%.

In the nootebook ***dental-pulp-cell-detection-maskrcnn***  you will find part of the code thath we use to develop the solution, we base our model on the implementation of  [matterport](https://github.com/matterport/Mask_RCNN). 

## 📑 Technologies uses:
* Python 3.0
* Mask-RCNN
* Keras
* Tensor Flow
* Tensor Board
* Git
* Open CV



If you need more information about this project no doubt in contact me.

## Contacto 
[Natalia Lenis](https://www.linkedin.com/in/natalia-lenis-6455b9214/)



**Cali - Colombia** 

## License
[MIT](https://choosealicense.com/licenses/mit/)
