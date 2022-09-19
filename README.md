# CONAN dataset in Spanish and Basque 

## Dataset description
These datasets are based on the CONAN (COunter NArratives through Nichesourcing) dataset, originally provided by [Chung et al., 2019](https://aclanthology.org/P19-1271.pdf). 
It provides 6654 HS-CN pairs in English, which consists of 1288 original HS-CN pairs, as well as 2576 augmented pairs and 2790 translated pairs. 
CONAN additionally provides 5157 pairs in French and 3213 in Italian. 

With the aim of providing data for CN generation in languages other than English, the English data in CONAN has been Machine Translated (MT) to Spanish and Basque, as well as manually post-edited. 

The following table includes a quantitative description of the MT and post-edited datasets, including the division between train and test sets. 

| Data source            | Total HS-CN count | Train/test division |
|------------------------|------------------:|--------------------:|
| Original               |              1288 |            Test set |
| Augmented + Translated |              5366 |           Train set | 


It needs to be noted that while the totality of the Spanish MT corpus was post-edited, this was not the case for Basque. 
Regarding the training set, only 2000 HS-CN pairs were post-edited, which is why the Basque post-edited dataset contains fewer examples. 
Additionally, while the CNs in the test set were post-edited, the HS were left unedited.  

## Download

These four datasets can be found in this repository: 

+ es_MT: Spanish MT dataset 
+ es_post: Spanish post-edited dataset
+ eu_MT: Basque MT dataset
+ eu_post: Basque post-edited dataset

Each dataset is divided into train and test set, as previously stated. We distribute the original and a shuffled version:

+ [original version](https://github.com/ixa-ehu/conan-e/raw/main/datasets-original-order.zip)
+ [shuffled version](https://github.com/ixa-ehu/conan-e/raw/main/datasets-shuffled.zip) 

## HS-CN example

The CONAN dataset includes HS-CN pairs, regarding the topic of Muslims and Islam. 
An example of a HS-CN pair is illustrated below: 

| HS                                                                                                                                                    | CN                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| Islamic are criminals: they rape, enslave and murder people. Islam is more a worship than a religion and we do not have anything to share with them.  | The myth that Muslims are dangerous and violent is a product of our vilifying media. Don’t believe everything you read. |
