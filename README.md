## Cancer Detection from Histopathologic Images using Deep Learning (Auto ML, Custom Convolutional Neural Network, and Transfer Learning) 
<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, Transfer Learning, ImageNet, Auto ML, NASNetMobile
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detected Cancer using Auto ML model from Google (“NASNetMobile”) with 250000+ (6.5GB) cancer cell images (histopathologic).
2. For training, concatenated global pooling (max, average), dropout and dense layers to the output layer for final output prediction.
3. Attained testing accuracy of 87.99% and loss of 0.30.

</pre>

#### Code
<pre>
GitHub Link      : <a href=https://github.com/anjanatiha/Histopathologic-Cancer-Detection>Histopathologic Cancer Detection(GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Histopathologic-Cancer-Detection>Histopathologic Cancer Detection(GitLab)</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Histopathologic Cancer Detection
Dataset Link     : <a href=https://www.kaggle.com/c/histopathologic-cancer-detection>Histopathologic Cancer Detection (Kaggle)</a>
                 : <a href=https://github.com/basveeling/pcam>PatchCamelyon (PCam) (GitHub)</a>
                 : <a href=https://camelyon16.grand-challenge.org/Data/>CAMELYON16 challenge Dataset (Original Dataset)</a>
                 
Original Paper   : <a href=https://jamanetwork.com/journals/jama/fullarticle/2665774>Diagnostic Assessment of Deep Learning Algorithms for Detection of Lymph Node Metastases in Women With Breast Cancer </a> 
                   Authors: Babak Ehteshami Bejnordi, Mitko Veta, Paul Johannes van Diest 
                   JAMA (The Journal of the American Medical Association)
                   <cite>Ehteshami Bejnordi B, Veta M, Johannes van Diest P, et al. Diagnostic Assessment of Deep Learning Algorithms for Detection of Lymph Node Metastases in Women With Breast Cancer. JAMA. 2017;318(22):2199–2210. doi:10.1001/jama.2017.14585</cite>
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Histopathologic Cancer Detection
Number of Class         : 2

</pre>
| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | :-------------- | :--------------------------- |
| **Total**       | 220,025         | 5.72 Gigabyte (GB)           |
| **Training**    | 132,016         | 3.43 Gigabyte (GB)           |
| **Validation**  | 44,005          | 1.14 Gigabyte (GB)           |
| **Testing**     | 44,004          | 1.14 Gigabyte (GB)           |


### Model Parameters

<b>Machine Learning Library: Keras</b>

Model and Training Prameters

| Current Parameters   | Value                                                       |
| :------------------- | :---------------------------------------------------------- |
| **Base Model**       | NashNetLarge                                                |
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | categorical_crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 16                                                          |                                     
| **Number of Epochs** | 2                                                           |
| **Training Time**    | 4.5 hour (270 min)                                          |



<b>Model Performance Metrics (Prediction/ Recognition / Classification)</b>

| Dataset              | Training       | Validation    | Test      |                                 
| :------------------- | :------------- | :------------ | :-------- |
| **Accuracy**         | 94.74%         | 93.62%        | 93.72%    |
| **Loss**             | 0.14           | 0.30          | 0.30      |
| **Precision**        | ---            | ---           | 89.02%    |
| **Recall**           | ---            | ---           | 90.80%    |
| **Roc-Auc**          | ---            | ---           | 91.59%    |


<b>Other Experimented Model and Training Prameters</b>

| Parameters (Experimented) | Value                                                  |
| ------------------------- | :-----------------------------------------------------:|
| **Base Models**           | NashNet(NashNetLarge, NashNetMobile), InceptionV3      |
| **Optimizers**            | Adam, SGD                                              |
| **Loss Function**         | categorical_crossentropy, binary_crossentropy          |
| **Learning Rate**         | 0.0001, 0.00001, 0.000001, 0.0000001                   |
| **Batch Size**            | 16, 32, 64, 128, 256                                   |                                     
| **Number of Epochs**      | 2, 4, 6, 10, 30, 50, 100                               |
| **Training Time**         | 4.5 hour (270 min), 1 day (24 hours), 2 days (24 hours)|


##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/images/result.png>See More Images</a>
</kbd>

##### Confusion Matrix: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/report/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Anaconda
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Duration                : November 2018 - Current
Current Version         : v1.0.0.3
Last Update             : 12.24.2018
</pre>
