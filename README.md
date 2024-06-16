**Facial Expression Recognition**

The main purpose of the project is recognition of emotions based on facial expressions. Detected 7 Facial Expressions based on several features like eyes , lips, cheek alignments.

Example:

![Em 1  The most relevant features](https://github.com/KattaAkki/Facial-Expression-Detection/assets/71118330/9cb27d71-dc2e-4128-a6b7-c09a3ca03db9)


Face images labeled for 7 expressions/emotions are:

* Anger
  
* Contempt
  
* Disgust
  
* Fear
  
* Happiness
  
* Sadness
  
* Surprise

The solution consists of versatile classifiers including Decision Tree, Random Forests, Support Vector Machines, DT based Binary Classifier, simple hybrid classifier.

Performance results, estimated by cross validation tests: 

* Multi-class Support Vector Machines (radial kernel, kernlab): 97.3% (st. deviation = 0.4%)
* Multi-class Support Vector Machines (linear kernel, e1071): 96.5%
* Decision Tree based classifier: 89.63% 
