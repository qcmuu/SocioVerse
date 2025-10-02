# User Pool Readme

### Sample Pool
The three sample pools contain all the agents used for three social simulations, namely President_Election_Prediction, Breaking_News_Feedback, and National_Economic_Survey.

Notice: user pool for the president election prediction is too large to upload directly to this repo. We release the full sample pools on HuggingFace Dataset.

### User Pool
We also release the full-size user pool from X, which contains around 1 million users.

HF Dataset: [Download Link](https://huggingface.co/datasets/Lishi0905/SimulateAnything)

**In compliance with X's data usage policies, we only provide the associated user IDs and the labels annotated by our demographic annotation system. Access to textual content must be obtained via the official X API using the corresponding user IDs.**

### Demographic Labels for the Rednote User Pool
- **influence** is calculated by the number of likes and comments;
- **GENDER** (a) Male (b) Female
- **Level of Consumption** (a) Low (b) Medium (c) High
- **Education** (a) high school and below (b) undergraduate and above
- **AGE** (a) Underage (0-18 years)(b) Young Adult (19-35 years) (c)Middle Age and Elder (36+ years)
- **income** and **spending** are generated according to prior distributions, which is detailed in the paper
