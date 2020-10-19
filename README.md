# Language-Classification-Problem
<p>In this language detection project, I worked 3 languages, namely English, Czech and Slovakian. The training data showed class imbalance. To counter the class imbalance, Multinomal Naive Bayes was used with adjusting 'Laplace smoothening hyperparameter' and setting `fit_prior` to False.
<p>Another key technique used was Creating Subwords. This breaks the words in the corpus into most frequently occurring sub-words.
 
``` 
Eg: Words:    play, playing, eating  
    Subwords: play, ing 
``` 

<p> Creating subwords decreased the unique word count in each class, and helped evening out the imbalance.

The notebook is divided into the following tasks: 
- Task 1: Exploratory data analysis, and basic visualization
- Task 2: Data cleaning and preprocessing
- Task 3: Training the Naive Bayes Model
- Task 4: Hyperparameter tuning to counter the shortcomings of the model and implementing small changes to improve performance
- Task 5: Use advanced Natural Language Processing techniques to improve model performance and address class imbalance (subword units) 
