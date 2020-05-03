## Care Green: Plant Disease Detector
A WebApp build using flask on platform Docker. This app will detect any disease which is present on the plant.
This app take picture of plant leaf as an input and provide name of the disease (if any) through which plant is infected.

<p align="center">
  FOR DOCKER PROJECT 1: <a href="https://github.com/shivam1808/Docker_Covid_Map"><strong>Covid-19 Map</strong></a>
</p>
 
<br>
<br>
<img src='https://raw.githubusercontent.com/shivam1808/Docker_Care_Green/master/Pic1.PNG' border='0' alt='Plant Disease Detection'/>
<img src='https://raw.githubusercontent.com/shivam1808/Docker_Care_Green/master/pic2.PNG' border='0' alt='Plant Disease Detection'/>
<img src='https://raw.githubusercontent.com/shivam1808/Docker_Care_Green/master/pic3.PNG' border='0' alt='Plant Disease Detection'/>
<img src='https://raw.githubusercontent.com/shivam1808/Docker_Care_Green/master/pic4.PNG' border='0' alt='Plant Disease Detection'/>
<br>
<p align="center">
  <sub>Created by <a href="https://github.com/shivam1808"><strong>Shivam Gupta</strong></a>
</p>
<hr noshade>
<br>


Training and evaluating state-of-the-art deep architectures for plant disease classification task using pyTorch. <br/>
Models are trained on the preprocessed dataset which can be downloaded [here](https://drive.google.com/open?id=0B_voCy5O5sXMTFByemhpZllYREU).<br/>
Dataset is consisted of **38** disease classes from [PlantVillage](https://plantvillage.org/) dataset and **1** background class from Stanford's open dataset of background images.
<br/>
**80%** of the dataset is used for training and **20%** for validation.
<br>


## Dataset Description:

|Name           | No of Classes | Class Names
| ------------- |:-------------:|:-----------------:|
| Apple     |     04        | 'Apple___Apple_scab','Apple___Black_rot','Apple___Cedar_apple_rust' 'Apple___healthy' |
| Blueberry |     01        | 'Blueberry___healthy' |
| Cherry    |     02        | 'Cherry_(including_sour)_Powdery_mildew', 'Cherry_(including_sour)_healthy' |
| Corn      |     04        | 'Corn___Cercospora_leaf_spot', 'Corn___Common_rust','Corn___Northern_Leaf_Blight','Corn___healthy' |
| Grape     |     04        | 'Grape___Black_rot','Grape___Esca_(Black_Measles)','Leaf_blight_(Isariopsis_Leaf_Spot)','Grape___healthy' |
| Orange    |     01        | 'Orange___Haunglongbing_(Citrus_greening)' |
| Peach     |     02        | 'Peach___Bacterial_spot','Peach___healthy' |
| Pepper    |     02        | 'Pepper,_bell___Bacterial_spot','Pepper,_bell___healthy' |
| Potato    |     03        | 'Potato___Early_blight','Potato___Late_blight','Potato___healthy' |
| Raspberry |     01        | 'Raspberry___healthy' |
| Soyabean  |     01        | 'Soybean___healthy' |
| Squash    |     01        | 'Squash___Powdery_mildew' |
| Strawberry|     02        | 'Strawberry___Leaf_scorch','Strawberry___healthy' |
| Tomato    |     10        | Tomato: 'Bacterial_spot','Early_blight', 'Late_blight', 'Leaf_Mold', 'Septoria_leaf_spot', 'Spider_mites','Target_Spot', 'Yellow_Leaf_Curl_Virus', 'Mosaic_virus', 'Healthy' |
