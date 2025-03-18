# **Password Strength Checker**

The project uses ML to classify paswwords in weak, medium and strong based in ther composition.

## **Objective** 

The password security is an esential point to preserve our data in securete way. The classifier is trained on character-based featured to determinate the strength of the password.
### **How it works** 
1. **Preprocessing**
   - Cleaning the data for null and duplicate values
   - Passwords are tokenized at the character level
   - TfidfVectorizer converts the characters into numerical values
2. ** Model training**
   - The X vector for the passwors and y vector for the strength are splitred into training and test sets
   - Random Forest Classifier is trained on the trai ning dataset
3. ** Prediction & Evaluation **
   - The model is evaluated using the mean accuracy in the test set
   - With a random example tests the model 

## **Technologies** 
* Python
* Pandas for data manipulation and data cleaning
* Jupyter notebook as IDE
* Radom Forest Classifier and TF-IDF vectorization for model building


**Dataset:** https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset?resource=download
