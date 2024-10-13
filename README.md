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

* Image ID.
* Original, but anonymised, texts published with each image.
* Automatically-generated texts for image captioning.
* Manual validation of the previous level.
* Error analysis.
* Language classification (en/ar).
* Classification by gender of the image subject (male/female/neutral).

SAND numbers:

<!--
||      **TOTAL NUMBER OF POSTS**       ||
|:----------------:|:-:|:----------------:|
|                  |249                 ||
| **Arabic posts** || **English posts** ||
|          122     || 127               ||
-->


|                  | **Posts** | **Original Texts (words)** | **Valid. Captions (words)** |
|:----------------:|:---------:|:--------------------------:|:---------------------------:|
| **Arabic page**  |    122    |          17.049             |           4.830             |
| **English page** |    127    |          21.524             |           5.019             |
| **TOTAL**        |    249    |          38.573             |           9.849             |



Numbers of Saudi Arabia Self-Narrative Dataset

Post
Original Texts (words)
Valid. Captions (words)
Arabic page
122
17.049
4.830
English page
127
21.524
5.019
TOTAL
249
38.573
9.849



<!---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table Example</title>
    <style>
        table {
            width: 50%;
            margin: auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center; /* Centro i contenuti delle celle */
        }
    </style>
</head>
    <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; text-align: center;">
        <tr>
            <th colspan="2">TOTAL NUMBER OF POSTS</th>
        </tr>
        <tr>
            <td colspan="2">249</td>
        </tr>
        <tr>
            <th>Arabic posts</th>
            <th>English posts</th>
        </tr>
        <tr>
            <td>122</td>
            <td>127</td>
        </tr>
    </table>
<br />
--->

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

