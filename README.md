# Wine-Quality-Prediction 🍷📊 

![image](https://user-images.githubusercontent.com/68503114/132919974-ecbeac72-ec16-402e-ba43-148049573917.png)

**Uncorking the Potential: Predicting Wine Quality**

Welcome to the captivating realm of wine quality prediction! This repository uncorks the secrets hidden within wine attributes using the power of machine learning. Whether you're an aficionado of fine wines or a curious explorer of data science, this project invites you to witness how predictive models can unveil the essence of wine quality.

Predicting the quality of wine on a scale of 0–10 when given a set of features as inputs.

## Sip-by-Sip through the Contents

- 🍇 [Introduction](#introduction)
- 🍷 [Vintage Dataset](#dataset)
- 🚀 [Embarking the Journey](#getting-started)
- 🧪 [The Alchemy - Model](#model)
- 📈 [Tasting the Results](#evaluation)
- 🍻 [Raising a Toast to Contributors](#contributing)

## Introduction

Step into the enchanting world of predicting wine quality – a challenge that has enthralled both oenophiles and data sorcerers. In this venture, we harness the prowess of data analysis and predictive modeling to decipher the enigma behind wine quality assessment. Join us in uncovering the correlations that influence the subjective perception of wine excellence.

[This project](https://github.com/Hritikgoswami/Wine-Quality-Prediction) is a case study for modelling taste preferences based on the [analytical dataset](https://github.com/Hritikgoswami/Wine-Quality-Prediction/blob/main/Wine-Quality-Dataset.csv) that we have from physiochemical tests of wines.

## Vintage Dataset

Our canvas is painted with data from [analytical dataset](https://github.com/Hritikgoswami/Wine-Quality-Prediction/blob/main/Wine-Quality-Dataset.csv), housing a splendid collection of red and white wines. Each bottle is an artwork, characterized by a symphony of attributes ranging from acidity and residual sugar to alcohol content. These attributes lay the foundation for the qualitative journey, as wines are rated on a scale from 1 to 10.

Input variables:  

- **fixed acidity:** No. of grams of tartaric acid per dm3
- **volatile acidity:**  No. of grams of acetic acid per dm3 of wine
- **citric acid:** No. of grams of citric acid per dm3 of wine
- **residual sugar:** Remaining sugar after fermentation stops
- **chlorides:** No. of grams of sodium chloride per dm3 of wine
- **free sulphur dioxide:** No. of grams of free sulphites per dm3 of wine
- **total sulphur dioxide:** No. of grams of total sulphite (free sulphite+ bound)
- **density:** Density in gram per cm3 
- **pH:** To measure ripeness 
- **sulphates:** No. of grams of potassium sulphate per dm3 of wine
- **alcohol:** Volume of alcohol in %
- **quality (target):** 1-10 value


Classification criteria:

The scores for quality(x) are set between 0-10 as follows:  
**Bad:** 0<=x<=4   
**Medium:** 5,6  
**Good:** 7<=x<=10 

## Embarking the Journey

As you step onto this voyage of discovery, here's your compass:

1. 🌐 Clone this repository onto your machine.

   
```bash
git clone https://github.com/Hritikgoswami/Wine-Quality-Prediction.git
```

2. 🧩 Install the spells we'll need - just cast.

```bash
pip install -r requirements.txt
```

## The Alchemy - Model

For making automated decisions on model selection we need to quantify the performance of our model and give it a score. Therefore, accuracy rate of the model is checked on each prediction. Here, [Random Forest](https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems.) has the maximum accuracy rate.

![image](https://github.com/Hritikgoswami/Wine-Quality-Prediction/assets/84679973/f08515c7-58c7-4b25-bdcf-6ba08ac40edc)

Behold the cauldron that shapes the future! Our [Random Forest](https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems.) is the ancient recipe we employ to predict the essence of wine quality. Crafted and honed through the ages, it is brought to life through the essence drawn from the dataset.


## Tasting the Results


![image](https://github.com/Hritikgoswami/Wine-Quality-Prediction/assets/84679973/0cd6dd84-4611-4d9d-b186-69e15abf020c)

Tasting the outcome: 84.3% accuracy achieved. Our model elegantly captures wine quality, a testament to data's subtle dance with flavors. Cheers to predictive prowess! 🍷📊🎉

## Raising a Toast to Contributors

🎉 We welcome contributions from the community! If you find a bug or have an enhancement in mind, please create an issue in the repository. If you'd like to contribute code, fork the repository, make your changes, and submit a pull request.

---

Pour a glass, take a sip, and immerse yourself in the art of predicting wine quality. If you have questions, musings, or tales to share, raise your voice! Here's to the intoxicating blend of data and vino! 🥂🍾


