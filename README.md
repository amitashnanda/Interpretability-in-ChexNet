# Interpretability-in-ChexNet
Implemented CNN-based Deep-Learning model(s) to detect pneumonia from chest X-rays, also Incorporated model interpretability using Sample Handling and Analysis Plan (SHAP). Then used the above metrics to quantify training data based on quality for better model performance and reliability.


## Folder Structure

```
Interpretability-in-ChexNet
└───doc
└───results
|    
└───src
│   │   Unet.ipynb
|   |   multiclass_classification.ipynb
|   └───pneumonia_detection_shap.ipynb
|
└───LICENSE 
└───README.md
└───tools.yml


```

## Prerequisites
The dependencies are listed under tools.yml and are all purely python based. To install them simply run
```
conda env update --file tools.yml
```

## Dataset
The dataset can be found here ```https://www.kaggle.com/datasets/nih-chest-xrays/data```. But we have used a smaller set of this larger dataset.  

## Running
For a local installation, make sure you have pip installed and run: 
```
pip install notebook
```
For running jupyter
```
jupyter notebook
```

## Results
<p align = "justify">

</p>
  

![](/results/Picture8.jpg)
![](/results/2.png)
![](/results/Picture7.jpg)
![](/results/Picture15.png)
![](/results/Picture16.jpg)
![](/results/Picture17.jpg)
