# Machine Learning

## Food Object Detection

## 1. Tools and Requirements
1. Python Programming Language
2. TensorFlow
3. Google Colaboratory
4. Roboflow
5. Makesense.ai

## 2. Datasets
Source of our dataset:
1. https://www.kaggle.com/datasets/robertusbagaskara/indonesian-food-image
2. https://www.kaggle.com/datasets/rizkashintaw/indonesian-food
3. https://www.kaggle.com/datasets/robertusbagaskara/indonesian-food-image 
4. https://www.kaggle.com/datasets/kmader/food41
5. https://github.com/abuwildanm/food-recognition 
6. https://github.com/lepuzz03/indonesian_food_datasets
7. https://github.com/Indra-RMT/Deteksi-Objek-Makanan-Indonesia
8. https://www.kaggle.com/datasets/trolukovich/nutritional-values-for-common-foods-and-products (Food Nutrition Dataset)

The total of our datasets is 20.605 datasets with 41 objects of Indonesian food.

## 3. Preprocessing
We labeled and augment our dataset using Roboflow and Makesense.ai tools

## 4. Model and Deployment
We use our datasets to retrain the Pre-trained model Faster R-CNN method and Inception V2 architecture from https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md to detect our objects and tune the parameters to adapt well with our datasets.

Model Performance: 
<img src="results/Model Performance.JPG">

Reference: 
1. https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/
2. https://blog.roboflow.com/training-a-tensorflow-faster-r-cnn-object-detection-model-on-your-own-dataset/

We saved our model using the SavedModel format.
