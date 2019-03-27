# **Machine Learning Stanford**

### **Example Problems**:

* Database Mining using large datasets to turn records to knowledge through discovering otherwise hard to find patterns and insights
* application that can'rt be programmed by hand otherwise data with hard to find patterns ie
  * flying a helicopter
  * handwriting recognition
  * NLP
  * computer vision

### **what is Machine Learning?**
* Arthur Samuel (1959) Machine Learning is field of study that gives computer the abiity to learn without being explicitly programmed ie 
  * arthur samuel's checker's model that learned how to play checkers through playing aganist itself

* Tom Mitchel (1998). Well posed Learning Problem: A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T as measured by P, improves with experience E
  * ie experience of Arthur samuel checkers model would be playing itself for tens of thousands of hours
  * the task would be playing checkers
  * performance would the probability of winnning the next game of checkers aganist some player

### **Machine Learning Algorithms**
* Supervised learning
* Unsupervised learning
* Reinforcement learning
* recommender systems

### **what is supervised learning?** 
giving the algorithim the correct output initially,
feautres are charcteristics about the data 
  
* regression problems
  * housing price prediction, 
* classifications problems
* a model that depends on infinite features   

Concerns:
  * a regression problem can be turned into a classification problem anytime and vice versa, where do you draw the line between them other than we are trying to get a contious value as an answer for a dicrete one
  * the initial answer might be already in the question which is it depends on the preferred output

### **what is unsupervised learning**

* takes unlabeled data and tries to find structure too it, an example would be a clustering algorithm where given an unlabeled dataset, turns the dataset into clusters
* another example would be unclustering algorithms such as the cocktail party algorithm which is singles out similar voices from different input sources
* octave for sound segmentation

---

## **2nd week**

### **Linear regression algorithm**
 notation used involves 
 * m = Number for training examples in a traiing dataset
 * x's =  features associated with input data
 * y's = target variable

small hint x's and y's are both chosen from the features of the training dataset, simply by separating them features that will avaliable in the test data or x's and features that needs to be predicted or y's

the workflow involves feeding a training set of data to learning algorithm which in turn returns a function which when given the x's returns the y's, this function is also known as the hupothesis