<h3 align="center">Using Teacher-Student Method for Semi-Supervised Learning to label the unlabeled data</h3>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>


<p align="left">What is Semi-Supervised Learning? Semi-Supervised Learning is using small portion of good labeled data to predict/label the large portion of unlabeled data</p>


<p align = "left">What are the advantages of Teacher-Student Method? The Teacher will generate the pseudo-label and calculate the accuracy with the good labeled data, if the score is desirable the Student will learn on the pseudo-labeled data to improve the Student's prediction. It will help the prediction of Student model consistently and stable. We also update the Teacher by EMA (Exponential Moving Average)</p>
