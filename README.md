## Cancer Detection from Histopathologic Images using Transfer Learning and Convolutional Neural Network                                           
<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detected Cancer from Histopathologic images by retraining pretrained model “InceptionV3” with 250000+ images of X-ray (6GB).
2. For retraining, removed output layers, freezed first few layers and Fine-tuned model for two new label classes (Cancer and Normal).
3. Attained testing accuracy -- and loss ---.
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
                 : <a href=https://github.com/basveeling/pcam> PatchCamelyon (PCam) (GitHub)</a>
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
Number/Size of Images   : Total      : 220,025 (5.72 Gigabyte (GB))
                          Training   : 132,016 (3.43 Gigabyte (GB))
                          Validation : 44,005  (1.14 Gigabyte (GB))
                          Testing    : 44,004  (1.14 Gigabyte (GB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64/32
Number of Epochs        : 50
Training Time           : - Hours

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<!--<b>Validation</b>-->
<b>Testing</b>
Accuracy                : 83.44%> need better
Loss                    : 0.42///
<!--Precision               : -->
Recall                  : 94% (highest)//
<!--Specificity             : -->
</pre>

##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/images/result.png>See More Images</a>
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
Current Version         : v1.0.0.0
Last Update             : 11.27.2018
</pre>
