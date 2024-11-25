[Erdős Institute Data Science Boot Camp](https://github.com/TheErdosInstitute/data-science-fall-2024), Fall 2024.

- View our 5 mins presentation ....

<h1>Fake Image Detection</h1>

<h3>Team Members:</h3>

[Heba Bou KaedBey](https://github.com/hebabkb), [Navid Bahadoran](https://github.com/navidbahadoran), [Rajeev Gopensingh](https://github.com/RajeevGopeesingh), [Chase Wiederstein](https://github.com/ChaseWiederstein), [Jonathan Engle](https://github.com/J3ngle)

<h1>Project Description</h1>

Fake image detection is increasingly crucial in combating misinformation and ensuring online authenticity. The technology addresses challenges in journalism, social media, and digital security, helping to identify manipulated or AI-generated images. Our project explores traditional machine learning methods to detect fake images effectively.

We leverage the CASIA2 Ground Truth Dataset, which contains 7,491 real images and 5,123 fake images altered through techniques such as image splicing, blurring, and color adjustments.

<h1>Recall Results</h1>

In the evaluation of recall scores for detecting fake images, Model 1 (Stack 5, one-level stacking) and Model 2 (Stack 7, two-level stacking) both achieved an impressive recall of 83%:

![](https://github.com/hebabkb/FakevsReal/blob/main/Presentation_Images/Recall%20Scores.png)

<h1>PR AUC Results</h1>

The Precision-Recall AUC in our 11 models is shown in this graph. As it is obvious, Stack 5 (model 1) and Stack 7 (model 2) are giving high performance

![](https://github.com/hebabkb/FakevsReal/blob/main/Presentation_Images/PR%20AUC%20Scores.png)

<h1>ROC AUC Results</h1>

Here the ROC-AUC of our models is shown. Again Stack 5 (model 1) and Stack 7 (model 2) are giving promising performance.

![](https://github.com/hebabkb/FakevsReal/blob/main/Presentation_Images/ROC-AUC%20Scores.png)


<h1>Models Details</h1>


