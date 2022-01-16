# SDOVIS: A Vision Transformer Model for Solar Dynamics Observatory (SDO) Data 

Code Repository for SDOVIS - Submitted to [Machine Learning in Heliophysics](https://ml-helio.github.io/)
<br>

Authors:<br> 
[Paul Wright](https://www.wrightai.com/) Wright AI Ltd, Leeds, UK<br>
[Frank Soboczenski](https://h21k.github.io/) School of Life Course and Population Sciences, King's College London, London, UK<br>

## Abstract:<br>
<p>Transformer models have become the goto standard in natural language processing (NLP). Their performance is often unmatched in tasks such as question answering, classification, summarization, and language translation. Recently, the success of their characteristic sequence to sequence architecture and attention mechanism has also been noted in other domains such as computer vision and achieved equal praise on performance on various vision tasks. In contrast to, for example, Convolutional Neural Networks (CNNs), Transformers achieve higher representation power due to their ability to maximize their large receptive field. However, Vision Transformers also come with increased complexity and computational cost which may deter scientists from choosing such a model. We demonstrate the applicability of a Vision Transformer model (SDOVIS) on SDO data in an active region classification task as well as the benefits of utilizing the HuggingFace libraries, data as well as model repositories, and deployment strategies for inference. We aim to highlight the ease of use of the HuggingFace platform, integration with popular deep learning frameworks such as PyTorch, TensorFlow, or JAX, performance monitoring with Weights and Biases, and the ability to effortlessly utilize pre-trained large scale Transformer models for targeted fine-tuning purposes.</p>

## Structure of the repository

Data:<br> 

+ `SDO_Solar_Active_Regions.xlsx` (Main SDO data)<br>
              
Jupyter:<br>

1. `DataPrep & Descriptives` (distribution of the data, Wilcoxon significance tests, boxplots, scatterplots, mean, sd etc of timing data)<br>
2. `SDOVIS Training & Inferece` (Main training and inference notebook including model checkpoint save, restore and performance monitoring with Weights & Biases<br>
3. `Analysis` (data transformation and plots)<br>

Dissimination:<br>

1. `HuggingFace Repository` (upload, indexing, live inference)<br>

Deployment:<br>

1. `HuggingFace X Gradio` (Model Deploymment)<br>

## Citation:<br>

We welcome scientists and profefssionals to use our code examples and data but would kindly ask to refer to one of the following resorces:<br>

```
@sdovis{sdovis2022,
  author = {Paul J Wright and Frank Soboczenski},
  title = {SDOVIS: A Vision Transformer Model for Solar Dynamics Observatory (SDO) Data},
  url = {http://github.com/h21k/sdovis},
  version = {0.1},
  year = {2022},
}
```

