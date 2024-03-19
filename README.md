# project1-eye-for-the-blind
**Captioning Images using Deep Learning - Transformers &amp; TTS**

**Problem statement:** Explain the contents of an image in the form of speech through caption generation with a deep learning model utilizing attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

To solve this problem we need to apply both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

<img width="891" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/37eded7b-b425-4ca8-af61-087710b00081">

The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper.
Link: https://arxiv.org/abs/1502.03044

The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

**Dataset: **https://www.kaggle.com/datasets/adityajn105/flickr8k

**Project Pipeline**
The major steps that you have to perform can be briefly summarised in the following four steps:<br>
  <img width="866" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/ab0b9082-6ea2-493b-a673-078b5fcc4d71">

- Dataset Creation:<br>
   <img width="796" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/501d85e4-d07f-4c07-8df4-67e205222003">
  
- Model Building: This is the stage where you will create your image captioning model by building Encoder, Attention and Decoder model.<br>
  <img width="771" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/d53e55d7-6a18-4601-a76d-6409dd8c7aea">

- Model Training:<br>
  <img width="762" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/9a804873-4da9-4a02-aa38-10217fb349ed">

- Model Evaluation: Evaluate the models using greedy search and BLEU score.<br>
  <img width="760" alt="image" src="https://github.com/abhi120490/project-eye-for-the-blind/assets/31450904/f65a74a5-205e-455c-9aba-0e57bc78ebca">


