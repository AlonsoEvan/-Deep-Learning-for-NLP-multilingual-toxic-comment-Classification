# -Deep-Learning-for-NLP-multilingual-toxic-comment-Classification
Kaggle project

Version 2.0 of this project made a while ago.

Kaggle project

So here's the Jigsaw Multilingual Toxic Comment Classification competition! I already participated on Jigsaw Toxic Comment Classification on Kaggle, my notebook is on GitHub and Linkedin if you want to take a look. Like is predecessor, in this competition, contestants are challenged to build machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion. This problem matters because one toxic comment is enough to sour an online discussion. By identifying and filtering toxic comments online, we can have a safer, more collaborative internet, leading to greater productivity and happiness. And that's very important.

In this kernel, I will explore the data. Then, I will explain and demonstrate how various deep learning models can be used to identify toxic comments with tensorflow.keras.

In this Notebook I will cover the following Deep Learning models 

Simple RNN's
LSTM's
GRU's
BI-Directional RNN's
I will also talk about seq2seq, Attention models and BERT.


Note that the aim of this notebook is not to obtained the highest score, I haven't the right computer for this nor the time. Instead, I want to fully undertand Deep Learning techniques used for NLP.

## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Future Development ](#Executive_Summary)
</details>

## File Descriptions
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
  
The primary data for the competition is, in each provided file, the comment_text column. This contains the text of a comment which has been classified as toxic or non-toxic (0...1 in the toxic column). The train set’s comments are entirely in english and come either from Civil Comments or Wikipedia talk page edits. The test data's comment_text columns are composed of multiple non-English languages.

The *-train.csv files and validation.csv file also contain a toxic column that is the target to be trained on.

The jigsaw-toxic-comment-train.csv and jigsaw-unintended-bias-train.csv contain training data (comment_text and toxic) from the two previous Jigsaw competitions, as well as additional columns that you may find useful.

*-seqlen128.csv files contain training, validation, and test data that has been processed for input into BERT.
</details>

## Technologies Used:
<details>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>NLTK</strong>
* <strong>Pipeline</strong>
* <strong>Scikit-Learn</strong>
* <strong>Keras</strong>
* <strong>Tensorflow</strong>
* <strong>LIME</strong>
</details>

## Structure of Notebooks:
<details>
<a name="Structure"></a>
<summary>Show/Hide</summary>
<br>
  

1. Import packages

2. Load Data

3. Data Exploration
   * 3.1 Workcloud for all the comments in train
   * 3.2 Number of words present in the comments
   * 3.3 WorkCloud for toxic comments
   * 3.4 WorkCloud for clean comments
   * 3.5 WorkCloud for Obscene/Severe Toxic/Threat/Insult comments

4. Modeling
    
5. Text preprocessing
    
6. Logistic Regression
    * 6.1 Basic Preprocessing
    * 6.2 Model
    * 6.3 Performances
    * 6.4 Model inteprretation with LIME
        
7. Simple RNN
    * 7.1 Basic Overview : What is a RNN?
    * 7.2 tokenizer and padding
    * 7.3 Designing RNN Architecture
    * 7.4 Model's performances
    * 7.5 Saving our model
    
8. LSTM
    * 8.1 Basic Overview 
    * 8.2 Word Embedding
    * 8.3 Designing LSTM Architecture
    * 8.4 Model's performances
    
9. GRU

    * 9.1 Basic Overview 
    * 9.2 Designing GRU Architecture
    * 9.3 Model's performances
    
10. Bi-Directional RNN's
 
    * 10.1 Designing Bi-Directional RNN Architecture
    * 10.2 Model's performances

11. Function to wrap-up

12. Conclusion

13. One step further with seq2seq/Attention/BERT
    
</details>  


<a name="Executive_Summary"></a>
## Future Development
    
* Il would like to try BERT and seq2sew when I have a most powerful computer.

