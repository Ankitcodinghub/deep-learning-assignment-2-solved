# deep-learning-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [Deep-Learning Assignment 2 Solved](https://www.ankitcodinghub.com/product/deep-learning-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93344&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Deep-Learning Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Task Description

</div>
</div>
<div class="layoutArea">
<div class="column">
The task of the assignment is known as (binary) gender recognition from face images. There are several papers focusing on this topic in the literature [1–4]. You will be using facial im- ages from two Kaggle datasets as described in Section 2.1. After downloading and preparing the datasets, your assignment is to:

<ul>
<li>Create a virtual environment and install tensorflow, SciPy, matplotlib, keras, seaborn libraries. These are the libraries we recommend but you can also install the ones of your choice.</li>
<li>Implement the baseline CNN algorithm that is shown in Fig. 1. It is a network consist- ing of: a convolutional layer with 16 filters of size 3 × 3 with ReLU activations followed by a max pooling layer of size 2 × 2; another convolutional layer identical to the first followed by a max pooling layer; a fully connected layer of size 64 and ReLU activation function; and finally, an output layer of size 1 with a sigmoid activation function. The pooling layers have a stride of 1.</li>
<li>Analyze the performance of the baseline by plotting: (i) the training and validation losses and accuracies on the training and test set, (ii) the Receiver Operator Character- istic (ROC) curve with the Area under the Curve (AUC) score and a confusion matrix for the validation and test set. Examples of accuracy and loss plots are shown in in Fig. 2, an example of a ROC curve and confusion matrix is shown in Fig. 3, respectively. Report performance measures (accuracy, sensitivity, specificity and F1-score).</li>
<li>Once you have a baseline model, adapt/fine-tune the network to improve its perfor- mance by: (i) changing the hyper-parameters (e.g. add more layers) and/or (ii) apply- ing data augmentation techniques. Illustrate the improvements of your new network over the baseline by: (a) plotting the ROC curve with AUC score and (b) reporting performance measures. Compare and explain the differences between the two models as well as potential reasons behind the increase in performance .</li>
<li>Next, train a new model using transfer learning. Utilize VGG16 architecture for feature extraction. Freeze the layers until the fully connected layer such that these layers will not be updated through training. Add your fully connected layers (as many as you like) and present the results that you obtained on the test set (ROC curve with AUC</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
score, performance measures and confusion matrix). Comment on the performance with respect to the baseline and the network that you designed in the previous step.

Figure 1: Baseline CNN Algorithm

2.1 Data set

The training and test data are available on Kaggle. The training data can be downloaded

using the following link:

https://www.kaggle.com/rashikrahmanpritom/gender-recognition-dataset

The dataset is provided in train, validation and test folders. Although there is a sepa- rate validation folder, the files inside that folder do not have labels. Hence, you should use the images in the test folder as your validation set. The traning folder contains 11135 RGB images of size 100 × 100 and the test folder contains 1279 RGB images of the same size – you will use those for validation.

It is important to have a test set that is from a different dataset. Test set can be down- loaded from:

https://www.kaggle.com/maciejgronczynski/biggest-genderface-recognition-dataset

The test set contains 27167 RGB images of varying size.

• You should resize your images to 100 × 100 while loading the images.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
(a) Training and validation accuracy (b) Training and validation loss

Figure 2: Examples of accuracy and loss plots

You should have the same labels as your training and validation sets. In training and validation sets, the label names are ‘Female’ and ‘Male’, so modify the test set folders accordingly.

</div>
</div>
<div class="layoutArea">
<div class="column">
Important Dates and Deliverables

A 4 page (excluding references, title page) group report should be submitted by Monday

October 4, 2021. The report should include the following information:

<ul>
<li>Title</li>
<li>Group Number</li>
<li>Student names and Student numbers</li>
<li>A summary of your models (excluding the baseline model) – similar to the one provided in Fig. 3.</li>
<li>A brief description of your experiments, including possible pre-processing steps, train- ing, hyperparameters, activation functions, optimizattion/regularization techniques…or any other changes you made.</li>
<li>The graphs/results requested in the task description, see Sec. 2.</li>
<li>A discussion of the performance of your solution and how it relates to the literature
used.
</li>
<li>All the .py code (that produces the results presented in your report).</li>
<li>A paragraph at the end of your report outlining the ethical concerns that arise from this task as well as its limitations.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

3.1 Report

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(a) Training and validation accuracy

</div>
</div>
<div class="layoutArea">
<div class="column">
3.2 Code

</div>
</div>
<div class="layoutArea">
<div class="column">
(b) Training and validation loss

Figure 3: Examples of ROC curve and confusion matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
Your code should be a plain Python script which can be run to generate your predictions. You do not need to include the training data or the trained model. We strongly recommend you to use Keras.

3.3 Submission format

Put the report and the code in a single zip file named with your group ID, e.g.

group 1.zip and submit it to the Canvas assignment page. References

<ol>
<li>[1] &nbsp;Xu, Ziyi, Li Lu, and Pengfei Shi. ”A hybrid approach to gender classification from face images.” 2008 19th International Conference on Pattern Recognition. IEEE, 2008.</li>
<li>[2] &nbsp;Yang, Zhiguang, Ming Li, and Haizhou Ai. ”An experimental study on automatic face gender classification.” 18th International Conference on Pattern Recognition (ICPR’06). Vol. 3. IEEE, 2006.</li>
<li>[3] &nbsp;Levi, Gil, and Tal Hassner. ”Age and gender classification using convolutional neural net- works.” Proceedings of the IEEE conference on computer vision and pattern recognition workshops. 2015.</li>
<li>[4] &nbsp;Yaman, Dogucan, Fevziye Irem Eyiokur, and Hazim Kemal Ekenel. ”Multimodal age and gender classification using ear and profile face images.” Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2019.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
