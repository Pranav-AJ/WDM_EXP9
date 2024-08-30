### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:

![image](https://github.com/user-attachments/assets/7cf3d649-2b7b-4918-b8a3-643b2e039905)

![image](https://github.com/user-attachments/assets/6ecb618d-8e31-4255-96f4-540549a359fb)

![image](https://github.com/user-attachments/assets/90d86001-75ef-475c-b2e9-8dd43fa0343b)

![image](https://github.com/user-attachments/assets/65ed65a8-278f-4260-ab44-7eb8a71e8163)

# Select
![image](https://github.com/user-attachments/assets/d28acb35-a0dc-488f-8328-4136b96edef1)

# Replace
![image](https://github.com/user-attachments/assets/0ba94aa8-e016-4c2f-b855-6f2c8a85cfb2)

# Tokenize
![image](https://github.com/user-attachments/assets/dfceb358-41ea-4b5d-89b9-830dbb6c80d1)

# Transform Cases
![image](https://github.com/user-attachments/assets/be4d3cce-9dca-4723-a9c7-ce6ea98d856b)

# Filter Tokens (by length)

![image](https://github.com/user-attachments/assets/115d1a8c-0d10-4fd8-920d-6b021b15f381)

# Filter stopwords
![image](https://github.com/user-attachments/assets/f619ff47-32ad-4707-9771-af84096066f9)

# Stem
![image](https://github.com/user-attachments/assets/ccbed6a7-8660-40ee-bfeb-ced304f3eb49)

### Result:

Thus the implementation of preprocessing technique on Twitter Data using Rapidminer is executed successfully.
