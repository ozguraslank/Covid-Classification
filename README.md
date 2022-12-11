<h2 style ="text-align": center; "markdown="1"> Covid Classification Project With Chest x-ray Images </h2>

<h3> Abstract </h3> <br>
During the pandemic, we have many difficulties with Covid-19. One of them is classification the chest x-ray images of suspect patients. When the doctors are tired or lost their focus, they have high probability to make wrong decision and give the wrong information to patient.
So, i decided to code a artificial intelligence model to predict patients situation by looking to their chest x-ray images.

<h3> Categories </h3> <br>
In this project, we have 3 categories; Normal patient, Patient with Viral Pneumonia and Patient with Covid. <br>
<br>


Normal Patient             |  Patient with Viral Pneumonia | Patient with Covid    
:-------------------------:|:-------------------------:|:-----------------------:
![Normal-17](https://user-images.githubusercontent.com/56040583/206904778-40b7895c-2666-42a6-8362-78f558ee9161.png)  |  ![Viral Pneumonia-31](https://user-images.githubusercontent.com/56040583/206905036-736cfa9a-358f-415b-bac8-80904789f1ee.png) | ![Normal-17](https://user-images.githubusercontent.com/56040583/206905038-418bdec2-c544-4dac-908d-970c4c71c2f5.png) 
<br>

<h3> Libraries Used </h3>

<ul>
 <li>Numpy</li>
 <li>Pandas</li>
 <li>Seaborn & matplotlib</li>
 <li>os</li>
 <li>cv2</li>
 <li>Scikit-learn</li>
 <li>Tensorflow</li>
</ul>


<h3> Deep Learning Model Features </h3>

<ul>
 <li>Algorithm: CNN</li>
 <li>Activation Function for classifying: Softmax</li>
 <li>Optimizer: Adam</li>
 <li>Loss: Sparse Categorical Cross Entropy</li>
 <li>Callbacks: EarlyStopping</li>
</ul>


<h3> Required pip installs <h3>

```
pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
pip install opencv-python
pip install sklearn
pip install tensorflow
```


