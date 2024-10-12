# SAND Repository

This repository provides a brief description and houses the Saudi Arabia Self-Narrative Dataset (SAND)
* [Gugliotta, E. (2024). *Comparative Analysis of Textual and Visual Contents on Saudi Tourism Instagram Pages* forthcoming]()
* [Gugliotta, E. (2024). *Gender Representation in Saudi Tourism Social Media* forthcoming]()

### *Overview of SAND*


SAND has been created to examine Saudi Arabia's self-representation in its current tourism promotion policy. As shown in the table below, SAND comprises 249 Instagram posts collected over the first six months of 2024 from two official Saudi tourism Instagram accounts: 122 posts from the Arabic-language page and 127 posts from the English-language page. SAND includes both textual and
visual contents from these posts, with original post texts totaling 38,573 words (17,049 from the Arabic page and 21,524 from the English page). The dataset also incorporates images from the posts, automatically generated image captions using the [ViT-GPT2 model](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning) , and manually validated image captions totaling 9,849 words
(4,830 from the Arabic page and 5,019 from the English page). The Vision Transformer (ViT) combined with GPT-2 (ViT-GPT2), was pre-trained on the [COCO 2017 dataset](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset), which includes a diverse range of images and their corresponding captions. The primary objectives of using ViT-GPT2 were to increase the quantity of data available for analysis, translate visual communication into text to facilitate comparative analyses, and test the model's efficacy on images from the Arab world. 
Additionally, SAND includes an error analysis of the automatic image captioning, categorising errors into types such as object recognition, attribution, action, relation, context, and specificity issues. 
SAND was created to facilitate comparative analysis of Saudi Arabia's tourism promotion strategies across different target audiences, incorporating both visual and textual data to enable comprehensive multimodal analysis of the country's self-representation in tourism marketing

In this repository, you will find SAND images and both kind of text, the natural ones (anonymised textual posts), and the automatically generated texts for image captions, together with their manual validation. 
Indeed, in the "SAND_texts.tsv" file we provide the following data:

* Image ID. 
* Original, but anonymised, text being publish together with each picture.
* Automatically-generated text for image captioning.
* The manual validation of the previous level.
* Error analyses.
* Language classification (En/Ar)
* Gender classification of image subject (Male/Female/Neutral).

SAND numbers:

|**TOTA NUMBER OF POSTS**|         
|:----------------------:|
|   	  249		 |       
|:----------------------:|
|**ARABIC**:|:**ENGLISH**|
|   122    :|:	127	 |
|:----------------------:|

<br />


### *License*

Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0)

<!--
<br />

### *Citation* 

Please cite this work as: 

````bibtex
@inproceedings{gugliotta-etal-wanlp2020, 
    title={An Empirical Analysis of Task Relations in the Multi-Task Annotation of an Arabizi Corpus}, 
    author={Gugliotta, Elisa and Dinarelli, Marco}, 
    booktitle={The 4th Conference on Language, Data and Knowledge (LDK 2023)}, 
    year={2023},
}

````


<br />
-->

