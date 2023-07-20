<h1 align="center" id="title">AI-Object Detection</h1>

<p id="description">Welcome to our object recognition project! Our project is developed using Jupyter Notebook leveraging the power of PyTorch and Matplotlib to visualize Python code. We have also incorporated OpenCV and NumPy to aid in building our model. The primary objective of this project is to create an advanced object recognition model capable of identifying AirPods and water bottles from submitted images. Currently the model has been trained to perform this task effectively. However please note that for privacy reasons the training data will be deleted in the future. If you are interested in using our model to identify objects or wish to enhance the model further we provide detailed instructions on how to retrain it. By following these instructions you can adapt the model to recognize other objects or even improve its accuracy for AirPods and water bottles. Throughout the Jupyter Notebook we have extensively utilized PyTorch a powerful deep learning framework to construct the object recognition model. Additionally we've employed Matplotlib to create informative visualizations for a more comprehensive understanding of the data and model performance. Our project's reliance on OpenCV and NumPy enhances the model's capabilities by effectively preprocessing and manipulating image data. This ensures the highest possible accuracy when identifying AirPods and water bottles in new images. We are excited to share our work with you and encourage you to explore and experiment with the model's capabilities. Whether you are a beginner or an experienced data scientist this project provides valuable insights into object recognition and deep learning techniques. Let's embark on this journey together and unleash the potential of our object recognition model! Feel free to follow the instructions provided to retrain the model or extend its abilities for your specific use case. Happy coding!</p>

<p align="center"><img src="https://img.shields.io/badge/YOLOv5-Object%20Detection-blue" alt="shields"><img src="https://img.shields.io/badge/Torch-Deep%20Learning%20Framework-green" alt="shields"><img src="https://img.shields.io/badge/torchvision-Computer%20Vision%20Library-blue" alt="shields"><img src="https://img.shields.io/badge/Matplotlib-Data%20Visualization%20Library-orange" alt="shields"></p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Jupyter Notebook
*   Pytorch
*   os
*   labelImage
*   Real Time Recording

<h2>🛠️ Installation Steps:</h2>

<p>1. Torch Torchvision Torchaudio</p>

```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117
```

<p>2. if is in Jupyter notebook</p>

```
!pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117
```

<p>3. Install YOLOv5</p>

```
git clone https://github.com/ultralytics/yolov5
```

<p>4. Install YOLOv5 requirements</p>

```
!cd yolov5 & pip install -r requirements.txt
```

<p>5. Install image label tool from other git repository</p>

```
!git clone https://github.com/heartexlabs/labelImg
```

<p>6. Get the pyqt5 lxml</p>

```
!pip install pyqt5 lxml --upgrade
```

<p>7. Start label the image</p>

```
!cd labelImg && python labelImg.py
```
