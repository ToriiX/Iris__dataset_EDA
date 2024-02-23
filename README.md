# Flower Classification EDA and PCA - Iris Extended Dataset

## In this project I explored species feature variation within (intra) and between (inter) three species of Iris found in North America. The results can be used for species classification and further development of Machine Learning models for classification.

### Technical skills: Data Exploration, PCA, and Visualization

Background on the genus:

Iris is a genus of about 300 species in the monocot plant family Iridaceae. Plants within the genus are perennial, with grasslike leaves and showy flowers which are highly valued in the horticultural industry. The flowers consist of three petal-looking sepals which are usually spreading downwards, three (sometimes reduced) upright petals, and three broad pollen-receptive stigma branches. Most of the species within the genus are distributed in the temperate Northern Hemisphere where they predominantly are found in dry, semi-desert, or colder rocky mountainous areas. (souce: Wikipedia.com)

![plantnet](https://github.com/ToriiX/Iris__dataset_EDA/assets/156717220/b650ee93-6ccd-4b33-9431-3765a540a9c6)


The dataset is downloaded from Kaggle (https://www.kaggle.com/datasets/samybaladram/iris-dataset-extended/) and includes elevation, soil type and morphological data from three species of Iris:

Iris setosa. Native to: Alaska, Aleutian Is., Amur, British Columbia, Irkutsk, Japan, Kamchatka, Khabarovsk, Korea, Krasnoyarsk, Kuril Is., Magadan, Manchuria, North European Russi, Primorye, Sakhalin, Yakutskiya, Yukon

Iris versicolor. Native to: Central & E. Canada to N. Central & E. U.S.A. -rhizomatous geophyte, grows primarily in the temperate biome.

Iris virginica.
Native to: E. Canada to Central & E. U.S.A. -rhizomatous geophyte, grows primarily in the temperate biome.

(source:plantsoftheworld.org)

## Takeaways:

### There is a clear morphological differentiation between I. setosa and the two other species K. virginica, and K. versicolor. - I. setosa can easily be differentiated from the two other species due to a significantly smaller petal size. I. versicolor inhabit intermediate features of I. setosa, and I. virginica, but are closer to the latter, with which it overlaps in all of the measurements.

### By looking at the petals alone, it is possible to distinguish the majority of K. virginica and K. veriscolor plants. However, due to overlap, it will create a significant classification error. By including more features in the classification, the accuracy can be improved.
