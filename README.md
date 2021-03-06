<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#paper">Paper</a></li>
      </ul>
    </li>
    <li>
      <a href="#description">Description</a>
      <ul>
        <li><a href="#training">Training</a></li>
        <li><a href="#predict">Predict</a></li>
        <li><a href="#dataset">Dataset</a></li>
      </ul>
    </li>
    <li><a href="#model-state-dict">Model state dict</a></li>
    <li><a href="#Web-view">Web view</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
![alt text](https://github.com/SimonCao1207/Emoji-Recommendation/blob/main/img/pic1.png?raw=true)

Our team has designed a sentence-based emoji suggestion, along with an api so that other developers can utilize our model for their applications. Our model was fine
tuned on pre-train BERT, which has been widely used and performed well in many NLP tasks
including classification.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Description

### Training

Provide training code and detail guidline for specific pretrained-model and training method. (train on Kaggle)

### Dataset
Folder includes two txt files with link to Kaggle and Hugging Face Dataset used to train models.

### Predict

Produce the output of two best models.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Model state dict -->
## Model state dict

### Two best model
Best quanitative result: CustomBERT + HG

Best qualitative result: CustomBERT + Kaggle + Generator

- Provided links to 12 fine-tunning model state dicts of pretrained BERT and its variances
- The following table is quantitative/qualitative results for 12 mentioned models
  
![alt text](https://github.com/SimonCao1207/Emoji-Recommendation/blob/main/img/table.PNG?raw=true)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- WEB VIEW -->
## Web view

![alt text](https://github.com/SimonCao1207/Emoji-Recommendation/blob/main/img/webview.PNG?raw=true)

This web is built with:
- ReactJS
- socket.io
- ExpressJS
- FastAPI
  

<p align="right">(<a href="#top">back to top</a>)</p>
