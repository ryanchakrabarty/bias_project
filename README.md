# Bias Project

This project aims to review and explain various types of bias among content targeted for teen and young adult. The project examines three typs of biases - racial, gender, religious biases. The sampled content are from various internet publications that spans five topics, science, health and wellness, lifestyle, social & politics, academia and career. A total of 100 content was used with 20 contnet for each of those categories. The content that is freely available can be found in the 'content' folder. Some of the content that is inside a paywall is not published here. 


## Methodology

For each bias type, a set of bias classes are used. A fixed set of words that are close or mean exactly that bias class is used as reference words. The reference words as well as the content is vectorized using Google's word embedding. Subsequently, the distances are measured from each reference word in each bias class and the words in the content. 

For the statistical analysis, the Anderson-Darling K-Sample test is used to identify if a specific types of bias exists. Then, the Kolmogorov-Smirnov test is used to test the presence of bias while comparing each pair of bias classes. Finally, the Mann Whitney test is used to identify the direction of bias within each document and for each class/bias type. 

## Key Findings

1. Gender bias, across all topics, is minimal.  This cannot be said about racial and religious bias. 

2. Racial bias is more pronounced in the lifestyle and health content. While one can understand racial bias is strong in the lifestyle content, as the lifestyle may often depend on specific cultural norms, health content seems to have wider racial bias variation.

3. Religious and racial bias is particularly pronounced against specific classes.  
