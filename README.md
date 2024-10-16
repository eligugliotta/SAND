# Saudi Arabia Self-Narrative Dataset


This repository provides a brief description and houses the Saudi Arabia Self-Narrative Dataset (SAND)
* [Gugliotta, E. (2024). *Comparative Analysis of Textual and Visual Contents on Saudi Tourism Instagram Pages* forthcoming]()
* [Gugliotta, E. (2024). *Gender Representation in Saudi Tourism Social Media* forthcoming]()

### *Overview of SAND*


SAND has been created to examine Saudi Arabia's self-representation in its current tourism promotion policy. As shown in the table below, SAND comprises 249 Instagram posts collected over the first six months of 2024 from two official Saudi tourism Instagram accounts: 122 posts from the Arabic-language page and 127 posts from the English-language page. SAND includes both textual and
visual contents from these posts, with original post texts totaling 38,573 words (17,049 from the Arabic page and 21,524 from the English page). The dataset also incorporates images from the posts, automatically generated image captions using the [ViT-GPT2 model](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning) , and manually validated image captions totaling 9,849 words
(4,830 from the Arabic page and 5,019 from the English page). The Vision Transformer (ViT) combined with GPT-2 (ViT-GPT2), was pre-trained on the [COCO 2017 dataset](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset), which includes a diverse range of images and their corresponding captions. The primary objectives of using ViT-GPT2 were to increase the quantity of data available for analysis, translate visual communication into text to facilitate comparative analyses, and test the model's efficacy on images from the Arab world. 
Additionally, SAND includes an error analysis of the automatic image captioning, categorising errors into types such as object recognition, attribution, action, relation, context, and specificity issues. 
SAND was created to facilitate comparative analysis of Saudi Arabia's tourism promotion strategies across different target audiences, incorporating both visual and textual data to enable comprehensive multimodal analysis of the country's self-representation in tourism marketing

To access the SAND images, please contact me at **eli.gugliotta@gmail.com** to obtain the decryption key.
In this repository, you will find SAND data, *i.e.* a file containing both types of text, the natural textual ones (anonymised posts), and the automatically-generated texts for image captions, as well as their manual validation. 

Indeed, in the "SAND_texts.tsv" file we provide the following data:

* Image ID (ID_img): A unique identifier for each post/image.
* Natural texts (Natural_text): The original texts published with each image, anonymized using the "\_anonymized_" token.
* Generated texts (Generated_text): Automatically-generated texts for image captioning.
* Validated generated texts (Validated_generated_text): Manual validation of the previous level.
* Error analyses (Error_type): Classification of errors found in the generated captions.
* Language (Language): Classification of the texts in English or Arabic (en/ar).
* Processed text (Processed_text): The automatically processed version of the original texts.
* Translation (Translated_text): The automatically translated Arabic text into English.

<br />

* Analysis of the image contents (Image_activity, Image_object, Image_context).
* Gender classification (Gender_label): Classification by gender of the image subjects (male/female/mixed).

The last levels of analysis were performed only on the "human SAND sub-corpus". This subset includes posts where a human subject was recognized and classified in the "Gender_label" column. Posts without a human subject are labeled "No_human" in the "Gender_label" column. For these "non-human" posts, the three columns for image content analyses contain the token "_not_analyzed_" to indicate that these analyses were not performed.
  

<br />

SAND numbers:

<!--
||      **TOTAL NUMBER OF POSTS**       ||
|:----------------:|:-:|:----------------:|
|                  |249                 ||
| **Arabic posts** || **English posts** ||
|          122     || 127               ||
-->


|                  | **Posts** | **Original Texts (tokens)** | **Valid. Captions (tokens)** | **TOTAL** |
|:----------------:|:---------:|:--------------------------:|:---------------------------:|:---------------------------:|
| **Arabic page**  |    122    |          2.882             |           1.033      |   3.915    |
| **English page** |    127    |          4.118             |           1.103      |   5.221    |
| **TOTAL**        |    249    |          7.000             |           2.136      |   9.136    |


### *License*

Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0)

<!--
<br />

### *Citation* 

Please cite this work as: 

Asia in the mirror. Self-representations, Self-narratives, and Perception of the Other
Peter Lang.

````bibtex
@inproceedings{gugliotta-etal-wanlp2020, 
    title={An Empirical Analysis of Task Relations in the Multi-Task Annotation of an Arabizi Corpus}, 
    author={Gugliotta, Elisa and Dinarelli, Marco}, 
    booktitle={The 4th Conference on Language, Data and Knowledge (LDK 2023)}, 
    year={2023},
}

````
per decriptare: dovranno istallare gpg se non l'hanno già e poi lanciare questo comando: gpg -d SAND_images.tar.gz.gpg > SAND_images.tar.gz - la password da inserire nella shermata che uscirà è NomeConfANNO - su wp è salavata questa frase con la mot corretta.
<br />
-->

